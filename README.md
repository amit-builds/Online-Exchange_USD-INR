# 💱 USD to INR Currency Converter (Python)

## 📌 Overview
This is a simple Python project that converts USD (United States Dollar) to INR (Indian Rupee) using real-time exchange rates from an online API.

The program takes user input in USD, fetches the current exchange rate, and displays the converted amount in INR.

This project demonstrates API integration, JSON parsing, and HTTP requests in Python.

---

## 🚀 Features
- Accepts user input in USD
- Fetches real-time exchange rate using API
- Converts USD to INR instantly
- Displays today’s exchange rate
- Simple and beginner-friendly

---

## 🛠️ Technologies Used
- Python 3
- requests library
- ExchangeRate API

---

## 📂 Project Structure
currency_converter/
│
├── converter.py
└── README.md

---

## 🔧 Installation & Setup

### Step 1: Clone the repository
git clone https://github.com/your-username/currency-converter.git

### Step 2: Install required library
pip install requests


### Step 3: Run the program
python converter.py


---

## 💻 How It Works
1. User enters amount in USD.
2. Program sends a GET request to the ExchangeRate API.
3. It fetches the latest exchange rate.
4. USD amount is multiplied by INR rate.
5. Converted amount is displayed.

---

## 🧾 Example Output
Enter your amount in USD: 100
Today's rate is: 83.12
Total value for 100$ is: 8312 INR

---

## ⚠️ Important Notes
- Internet connection is required.
- Exchange rate changes daily.
- Currently supports only USD to INR conversion.

---

## 📈 Future Improvements
- Support multiple currencies
- Add proper error handling
- Add graphical interface (GUI)
- Convert into web application
- Add unit tests

---
