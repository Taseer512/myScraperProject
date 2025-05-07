# 📚 Book Scraper

A simple Python script that scrapes book titles and prices from the homepage of [Books to Scrape](https://books.toscrape.com/) and saves the data into a CSV file.

## 🔧 Features

- Scrapes book **titles** and **prices** from the first page of the website.
- Saves the extracted data into a file named `books.csv`.
- Uses `requests` for HTTP requests and `BeautifulSoup` for HTML parsing.
- Outputs a clean CSV file ready for use.

## 📁 Output Example (`books.csv`)

| Title                       | Price  |
|----------------------------|--------|
| A Light in the Attic       | £51.77 |
| Tipping the Velvet         | £53.74 |
| ...                        | ...    |

## 📦 Requirements

Install the required Python packages before running the script:

```bash
pip install requests beautifulsoup4
