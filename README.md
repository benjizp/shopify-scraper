# Shopify Store Scraper

A Python tool that scrapes product data from any Shopify store and exports it to Excel.

## What it does
- Accepts multiple store URLs as input
- Scrapes all products including title, vendor, price, description, availability and images
- Exports to Excel with an individual sheet per store and a combined sheet

## How to use
1. Install dependencies: `pip install requests openpyxl beautifulsoup4`
2. Run the script: `python shopify-general-scraper.py`
3. Enter store URLs one by one when prompted
4. Press Enter with no URL when done
5. Excel file saved as `shopify_scraped.xlsx`

## Requirements
- Python 3
- requests
- openpyxl
- beautifulsoup4
