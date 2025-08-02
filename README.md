# Flipkart Phone Scraper

A simple Python script to scrape mobile phone data (name, price, rating) from Flipkart and save it to a CSV file.

## 🔧 Technologies Used

- Python
- BeautifulSoup (bs4)
- Requests
- CSV

## 🚀 Features

- Extracts phone name, price, and rating from Flipkart
- Saves data to `flipkart_phones.csv`
- Simple and lightweight

## 📝 How to Use

1. Install dependencies:
    ```bash
    pip install requests beautifulsoup4
    ```

2. Run the script:
    ```bash
    python flipkart_scraper.py
    ```

3. Check the `flipkart_phones.csv` file for the scraped data.

## 📌 Note

Flipkart may block bots or change HTML structure over time. Ensure to update class names or headers accordingly if scraping fails.

## 📁 Output Sample

| Name                  | Price   | Rating |
|-----------------------|---------|--------|
| iPhone 14 Pro         | 129999  | 4.6    |
| Samsung Galaxy S22    | 84999   | 4.4    |


