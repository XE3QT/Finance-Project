# C$50 Finance Project

## Background
C$50 Finance is a web application that allows users to manage portfolios of stocks. Users can register for an account, look up real-time stock prices, buy and sell stocks, view transaction history, and track their portfolio's value. The project uses Flask, a Python web framework, and integrates with Yahoo Finance to fetch stock quotes via their API.

## Features
- User registration and login
- Stock lookup to get real-time stock prices
- Buy and sell stocks at current market prices
- View transaction history with buy/sell details
- Display portfolio information, including stock holdings and current values
- Real-time cash balance and overall portfolio value

## Technologies
- Flask (Python web framework)
- Yahoo Finance API (for stock quotes)
- SQLite (database for user registration and transactions)
- HTML, CSS, and JavaScript (front-end)

## How to Run the Application
1. Clone the project repository to your local machine.
2. Install the required Python packages using `pip install -r requirements.txt`.
3. Execute `flask run` in the terminal to start the development server.
4. Open your web browser and visit `http://127.0.0.1:5000` to access the application.

## How to Use the Application
1. Register for an account using a unique username and password.
2. Log in to your account using your credentials.
3. Use the "Quote" feature to look up real-time stock prices for different companies.
4. Buy and sell stocks by specifying the stock symbol and the number of shares.
5. View your current portfolio on the home page, showing stock holdings and overall value.
6. Check your transaction history for a detailed list of buys and sells.

## Acknowledgements
This project is a part of Harvard's CS50 Introduction to Computer Science course. It was completed as an assignment and implemented with the help of CS50's distribution code and API.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
