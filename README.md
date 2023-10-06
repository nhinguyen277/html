# HTML
This repo is a place to save my coding and small lessons of HTML class.

![HTML](https://miro.medium.com/v2/resize:fit:900/0*2blaR2l8ZqJ-HAaV.gif)

### This Is A Sample Code

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <title>Forms and semantic layout tags</title>
</head>

<body>
    <header>
        <h2><a href="#">FAKE STORE</a></h2>

        <ul>
            <li>
                <a href="#">Account</a>
            </li>
            <li>
                <a href="#">Card</a>
            </li>

        </ul>
        <ul>
            <li>
                <a href="#">Home</a>
            </li>
            <li>
                <a href="#">Shop</a>
            </li>
            <li>
                <a href="#">About</a>
            </li>
            <li>
                <a href="#">Contact</a>
            </li>
        </ul>

    </header>
    <main>
        <h1>CHECKOUT ORDER #1234 - BILLING AND PAYMENT</h1>
        <p>Order total:$129.57 </p>
        <fieldset>
            <legend>Billing information</legend>
            <div>
                <label for="firstname">First name:</label>
                <input type="text" id="firstname" name="firstname" placeholder="Nhi">

                <label for="lastname">Last name:</label>
                <input type="lastname" id="lastname" name="lastname" placeholder="Nguyen">

            </div>
            <div>
                <label for="adress">Adress:</label>
                <input type="text" id="adress" name="adress" placeholder="123, Fake Street">
            </div>
            <div>
                <label for="city">City:</label>
                <input type="text" id="city" name="city" placeholder="Toronto">

                <label type="provinces">Province:</label>
                <select id="province" name="provinces">
                    <option disabled value="" selected>---Choose province---</option>
                    <option value="NB">New Brunswick</option>
                    <option value="ON">Ontario</option>
                    <option value="QC">Quebec</option>                   
                </select>

                <label for="post">Postal Code:</label>
                <input type="text" id="post" name="postcode" placeholder="A1A 1A1">
            </div>
            <div>
                <label for="phone">Phone number:</label>
                <input type="text" id="phone" name="phonenum" placeholder="555-555-5555">
            </div>
        </fieldset>
        <fieldset>
            <legend>Payment information</legend>
            <fieldset>
                <legend> Choose Card </legend>
                <div>
                    <input type="radio" id="mastercard" name="cards" value="master" checked>
                    <label for="mastercard">MasterCard</label>
                </div>
                <div>
                    <input type="radio" id="visa" name="cards" value="visa">
                    <label for="visa">Visa</label>
                </div>

            </fieldset>
            <div>
                <label for="cardnum">Card Number:</label>
                <input type="number" id="cardnum" name="cardnumber" inputmode="numberic" placeholder="1234 1234 1234 1234">

                <div>
                    <label for="ex">Card expiry:</label>
                    <input type="text" id="ex" name="expired" placeholder="MM/YY">
                </div>
            </div>

        </fieldset>

        <button type="submit">Pay now</button>
    </main>
    <footer>
        <p>&copy; Copyright HTTP5111, 2022</p>
    </footer>
</body>

</html>

## NOTE: PLEASE DO NOT TRY TO COPPY ALL MY CODE TO ADVOID PLAGIARISM.

## REPO RESOURSE 
https://github.com/nhinguyen277/html
