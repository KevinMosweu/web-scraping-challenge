# web-scraping-challenge

# Description
This project makes use of python to scrape data and information off of webpages in two parts. The first part scrapes titles and previews from a website of news articles centered around Mars. The second part scrapes rows of Mars related data from a table on a website and stores the data in a pandas DataFrame for analysis and visualisation.

---

## #Part1: Mars News

- ### Step 1: Visit the Website

1. Use automated browsing to visit the [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html). Inspect the page to identify which elements to scrape.

- ### Step 2: Scrape the Website

Create a Beautiful Soup object and use it to extract text elements from the website.

- ### Step 3: Store the Results

Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:

*Store each title-and-preview pair in a Python dictionary. And, give each dictionary two keys: `title` and `preview`.

*Store all the dictionaries in a Python list.

*Print the list in your notebook.

