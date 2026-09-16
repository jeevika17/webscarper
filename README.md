# Book Scraper

A Python web-scraping project that extracts book titles and prices from [Books to Scrape](https://books.toscrape.com/) and saves the results into a CSV file.
Project Format

This project is implemented in a Jupyter Notebook (.ipynb) using Google Colab. The notebook contains the scraping logic, pagination handling, data extraction, and CSV export steps.

## Features

* Extracts book titles and prices.
* Handles pagination automatically.
* Collects books from multiple pages.
* Stores the scraped data in a structured format.
* Exports the results as a CSV file.

## Technologies Used

* Python
* Requests
* BeautifulSoup
* Pandas

## How It Works

1. Sends a request to the website.
2. Parses the HTML using BeautifulSoup.
3. Extracts book titles and prices.
4. Follows the next-page link until all pages are scraped.
5. Saves the collected data into `books.csv`.

## Output

The scraped data is saved as:

```text
books.csv
```

The CSV contains the following columns:

| Column | Description       |
| ------ | ----------------- |
| title  | Title of the book |
| price  | Price of the book |


## Future Challenges and Improvements

Real-world websites may introduce challenges such as:

* JavaScript-rendered content requiring Playwright or Selenium.
* Network errors, timeouts, and rate limiting.
* Anti-bot protection, including CAPTCHAs and IP blocking.
* Changes in website structure and CSS selectors.
* Missing or incorrectly formatted data.
* Storing large datasets in a database instead of a CSV file.


## Disclaimer

This project is created for learning and educational purposes using the Books to Scrape practice website.
