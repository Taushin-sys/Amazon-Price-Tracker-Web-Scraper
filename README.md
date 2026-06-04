# Amazon Price Tracker — Web Scraper

A Python web scraper that monitors Amazon product prices 
and sends automated email alerts when the price drops 
below a set threshold.

---

## What It Does

- Connects to an Amazon product page using Requests and BeautifulSoup
- Extracts the product title and current price
- Stores price data with timestamps to track changes over time
- Automatically sends an email alert when price drops below target

---

## How It Works

1. Send HTTP request to Amazon product page with browser headers
2. Parse HTML response using BeautifulSoup to extract price and title
3. Append data with timestamp to a CSV file
4. Check if current price is below threshold
5. If yes, trigger email notification via smtplib

---

## Skills Demonstrated

- Web scraping with BeautifulSoup and Requests
- Data storage and automation with CSV and datetime
- Automated email notifications using smtplib
- Loop-based scheduling for continuous price monitoring

---

## Tools Used

- Python 3
- BeautifulSoup4
- Requests
- smtplib
- CSV
- Jupyter Notebook
