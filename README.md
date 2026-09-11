# Books to Scrape - Web Scraper & Data Extractor

A robust Python-based web scraping application built to extract book details, pricing, and availability from online storefronts. This project serves as a demonstration of automated data harvesting, HTML parsing, and structured data serialization for portfolio purposes.

## 🚀 Key Features
*   **Dynamic Request Headers:** Implements randomized user-agents via `fake-useragent` to simulate organic browser traffic and bypass basic anti-scraping blocks.
*   **Precise DOM Parsing:** Leverages `BeautifulSoup` to navigate nested HTML layouts, target document segments, and isolate specific product attributes.
*   **Structured Data Export:** Automated pipeline that cleans raw text and serializes product data cleanly into a production-ready CSV format.

## 🛠️ Tech Stack & Dependencies
*   **Language:** Python 3
*   **Libraries:** Requests, BeautifulSoup4, Fake-Useragent, CSV

## 📊 Extracted Data Sample
The scraper parses target fields into a structured spreadsheet containing:
1.  **Title ID:** A sequential identifier for tracking records.
2.  **Book Title:** The full, unabbreviated title extracted from the HTML attributes.
3.  **Product Price:** The localized retail price of the item.

## ⚙️ How To Run
1. Download or clone this repository.
2. Install the required dependencies:
   ```bash
   pip install requests beautifulsoup4 fake-useragent
   ```
3. Run the Jupyter Notebook file to execute the scraper and automatically generate the `book_prices.csv` dataset.
