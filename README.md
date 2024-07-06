# Web Scraping Project

## Description
This project involves creating a web scraper in Python 3.10 that extracts product data from a given URL, handles pagination, and outputs the data in JSON format. It includes the following operations:
- **Lister**: Extracts product URLs.
- **Crawler**: Collects specific data for each product.

## Requirements
- Python 3.10
- Libraries:
  - beautifulsoup4
  - requests
  - pillow
  - PyMuPDF

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/LucasGentry/web_scraping_project.git

2. Usage
python main.py -c <number_of_crawlers>
python main.py -c 5

3. Outut
products.json

## Optional Features
Parse PDFs for additional information (e.g., UN Number from section 14.1).
Convert product images to PNG thumbnails and save them in the images/ directory.