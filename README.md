# HTMLscraping
Module 11 Challenge - CU Bootcamps


# Mars Web Scraping and Data Analysis Overview

This assignment involved web scraping data from the Mars News website and analyzing Mars weather information. The skills applied include automated browsing with Splinter, HTML parsing with Beautiful Soup, data extraction and storage, data analysis with Pandas, and data visualization with Matplotlib.

## Part 1: Scrape Titles and Preview Text from Mars News

### Automated Browsing and HTML Parsing
- Utilized Splinter for automated browsing to visit the Mars News website.
- Employed Chrome DevTools to inspect the page and identify HTML elements for scraping.
- Created a Beautiful Soup object to parse and extract text elements from the website.

### Data Extraction and Storage
- Extracted titles and preview text from Mars news articles.
- Stored the scraped information in Python dictionaries, each containing title and preview, and organized them in a list.


## Part 2: Scrape and Analyze Mars Weather Data

### Automated Browsing and HTML Parsing

- Used Splinter to visit the Mars Temperature Data Site.
- Created a Beautiful Soup object to scrape data from the HTML table.

### Data Extraction and Storage

- Assembled the scraped data into a Pandas DataFrame with appropriate column headings.

```python
id | terrestrial_date | sol | ls | month | min_temp | pressure

# Stack Overflow Articles:
# https://stackoverflow.com/questions/55192919/nonetype-object-is-not-callable-in-beautiful-soup-4
# https://stackoverflow.com/questions/23136157/browsing-parsing-html-pages-in-python/23136306#23136306
# https://stackoverflow.com/questions/52336057/web-scraping-html-table-with-certain-text-in-python

