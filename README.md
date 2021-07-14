# Academic Honesty
If you are taking Harvard's CS50 - Introduction to Computer Science course you **must follow the course's [Academic Honesty philosophy](https://cs50.harvard.edu/x/2021/honesty/)**.

It is not reasonable to access a solution to some assessement prior to (re-)submitting your own.

The essence of all work that you submit to the CS50 course **must be your own**. 

# CS50's Finance - Stock Trade Simulator
![](/finance_portfolio.png)

# Description
This is a basic web app via which you can manage portfolios of stocks. Not only will this tool allow you to check real stocks’ actual prices and portfolios’ values, it will also let you buy (okay, “buy”) and sell (okay, “sell”) stocks by querying IEX for stocks’ prices.

# Created with 
This application uses Flask: Python, HTML and styling with Bootstrap. It also uses IEX API to get the stocks values in real time and a SQL database to store users information, such as username, a hash of the password, the stocks they bought or sold and the history.

# Usage 
1. Press "Register" on the navigation bar to create an account;
2. You will receive US$ 10,000 simulation cash by default.
* Index: shows user's portfolio;
* Quote: shows the price after inputing a US stock symbol;
* Buy: input a US stock symbol with the amount of shares you want to buy;
* Sell: choose from drop down menu the stocks you own and input the amount of shares you want to sell;
* History: a list of all transactions you have made.

Don't use the same password that you would use in real-life to register. This is a toy app just for practice and I have not implemented a whole lot of security features.

# Access
You can access the webp app at: https://harvard-cs50-8-finance.herokuapp.com/login

# What I learned
Further learning of:

Python, Flask, HTML, CSS, Bootstrap, MVC, Heroku, Git commands

I learned to work within a Framework (Flask in this case) and on a fullstack project that applies the MVC (Model-View-Controller) pattern.

Besides that, deploying this app in Heroku was another challenge that teached me to plan the production environment ahead in order to not have inconsistencies deploying our applications. 

It was a great experience.
