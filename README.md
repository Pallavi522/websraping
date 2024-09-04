# websraping
# Quote Scraper

This Python script scrapes quotes from the [Quotes to Scrape](http://quotes.toscrape.com) website and saves them into a CSV file. The script uses the `requests` library to fetch the web pages and `BeautifulSoup` from the `bs4` package to parse the HTML content.

## Features

- Scrapes quotes along with their authors from multiple pages of the website.
- Saves the scraped data into a CSV file.

## Requirements

- Python 3.6 or higher
- requests
- BeautifulSoup (`bs4` package)

## Installation

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/your-username/quote-scraper.git
2. Navigate to the project directory.

   ```bash
   cd quote-scraper
3. Create and activate a virtual environment (optional but recommended).
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
4. Install the required packages.
   ```bash
    pip install -r requirements.txt
5. Alternatively, you can install the dependencies manually:
    ```bash
    pip install requests beautifulsoup4
Usage
Run the script to start scraping quotes:

    ```bash
    python scrape_quotes.py
The script will scrape quotes from the website and save them to a file named quotes.csv in the current directory.

After the script finishes, you will see the message:

css

Scraped and saved [number] quotes to quotes.csv
## Important Notes
Ensure that you have a stable internet connection while running the script since it needs to access the website multiple times to scrape all the quotes.
The quotes.csv file will contain two columns: text (the quote) and author (the author of the quote).
Troubleshooting
If you encounter issues with data not being saved, ensure that the website is accessible and that your Python environment has all the necessary packages installed.
If the script fails to scrape data, it may be due to changes in the website's structure. In such cases, inspect the website using developer tools in your browser and update the selectors in the script accordingly.
