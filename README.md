# Amazon-Samsung-A56-Price-Tracker

A simple Python project that scrapes product information from Amazon and stores the product title and price in a CSV file. The script can be scheduled to check the price periodically, making it useful for tracking price changes over time.

## 📌 Features

- Scrapes product title from Amazon.
- Scrapes current product price.
- Saves data to a CSV file.
- Appends new price records with date and time.
- Can automatically check prices at regular intervals.

## 🛠️ Technologies Used

- Python
- Requests
- BeautifulSoup (bs4)
- Pandas
- CSV
- Datetime




## 📦 Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/Amazon-Price-Tracker.git
```

2. Navigate to the project folder

```bash
cd Amazon-Price-Tracker
```

3. Install the required libraries

```bash
pip install requests beautifulsoup4 pandas
```

## ▶️ How to Run

Run the Jupyter Notebook or execute the Python script.

The program will:

- Connect to the Amazon product page.
- Extract the product title and price.
- Save the information into a CSV file.
- Repeat the process after a specified time interval (if using the loop).

## 📄 Sample Output

| Date       | Product                  | Price |
|------------|--------------------------|------:|
| 07-08-2026 | Samsung Galaxy A56 5G    | 31,999  |

## ⚠️ Note

Amazon frequently changes its website structure and may block automated requests. If the scraper stops working, the HTML elements or request headers may need to be updated.

This project is intended for educational purposes only.

## 🚀 Future Improvements

- Email notification when the price drops.
- SMS or Telegram alerts.
- Track multiple products simultaneously.
- Store data in a database.
- Visualize price history using Matplotlib or Power BI.

## 👨‍💻 Author

**Yasin Rafeeque**

GitHub: https://github.com/yasin-rafeeque
