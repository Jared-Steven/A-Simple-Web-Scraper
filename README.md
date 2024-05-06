# A Simple Web Scraper Using BeautifulSoup

## Overview

This project demonstrates a simple web scraper implemented using BeautifulSoup, a Python library for pulling data out of HTML and XML files. The web scraper is designed to extract quotes from the website "http://quotes.toscrape.com" and display them along with their authors and tags.

## Code Details

The code is provided in the Jupyter Notebook format (`A_Simple_Web_Scraper_Using_BeautifulSoup.ipynb`). It's developed using Python and relies on the `requests` and `BeautifulSoup` libraries for fetching web pages and parsing HTML content, respectively.

### Dependencies

Ensure you have the following dependencies installed to run the code:
- `requests`
- `beautifulsoup4`

### Code Workflow

The notebook follows these key steps:

1. **Fetching Web Pages:**
   - Sending HTTP requests to the website "http://quotes.toscrape.com" to retrieve its content.

2. **Parsing HTML Content:**
   - Using BeautifulSoup to parse the HTML content of the web pages and extract relevant information such as quotes, authors, and tags.

3. **Iterating Over Pages:**
   - Implementing a loop to scrape multiple pages of quotes, with each page containing a set number of quotes.

4. **Displaying Results:**
   - Printing the quotes along with their authors and tags in a structured format.

## Usage

To run the notebook, follow these steps:
1. Install the required dependencies listed above.
2. Open the notebook and execute each cell sequentially to perform web scraping and display results.
3. Ensure an active internet connection to fetch data from the website.

## Conclusion

The simple web scraper presented in this project illustrates the basic principles of web scraping using Python and BeautifulSoup. It can be further customized and extended to scrape data from various websites for different purposes.

For detailed implementation and results, refer to the notebook.

