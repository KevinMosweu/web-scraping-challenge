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

---

## #Part2: Mars Weather

- ### Step 1: Visit the Website

Use automated browsing to visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html). Inspect the page to identify which elements to scrape.

- ### Step 2: Scrape the Table

Create a Beautiful Soup object and use it to scrape the data in the HTML table.

- ### Step 3: Store the Data

Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.

- ### Step 4: Prepare Data for Analysis

Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate `datetime`, `int`, or `float` data types.

- ### Step 5: Analyze the Data

Analyze your dataset by using Pandas functions to answer the following questions:

1. How many months exist on Mars?
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)?
4. Which months have the lowest and the highest atmospheric pressure on Mars?
5. About how many terrestrial (Earth) days exist in a Martian year?

- ### Step 6: Save the Data

Export the DataFrame to a CSV file.
