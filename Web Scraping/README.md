# Web Scraping Practice

This directory contains exercises and practices for extracting structured data from web pages using python.

## Contents

*   **[`practice.ipynb`](file:///d:/python/Web%20Scraping/practice.ipynb)**: A Jupyter notebook containing code examples for sending HTTP requests, bypassing basic anti-bot blocks, parsing HTML nodes, and organizing extracted data.

## Key Techniques Covered

### 1. HTTP Requests and Custom Headers
*   Using Python's `requests` library to fetch target web pages.
*   Resolving `403 Forbidden` status errors by appending customized headers like `User-Agent` to simulate a standard web browser connection.

### 2. HTML Parsing & Navigation
*   Utilizing **BeautifulSoup** (`bs4`) to parse and navigate the DOM tree.
*   Finding elements by HTML tags, CSS classes, and attributes.
*   Extracting raw text, links (`href`), and media elements.

### 3. Structured Storage
*   Using **Pandas** to compile scraped lists of items into tabular dataframes.
*   Exporting scraped data to clean CSV/Excel files for subsequent analysis.

## Setup Requirements

Install the necessary libraries before running the notebook:
```bash
pip install requests beautifulsoup4 pandas
```
