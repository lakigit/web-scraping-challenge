# web-scraping-challenge
Module 11 challenge

This assignment consists of two technical products.
  -  Deliverable 1: Scrape titles and preview text from Mars news articles.\
     **Mars news site:**\
             [https://static.bc-edx.com/data/web/mars_news/index.html]
  -  Deliverable 2: Scrape and analyse Mars weather data, which exists in a table.\
     **Mars temperature data site:**\
             [https://static.bc-edx.com/data/web/mars_facts/temperature.html]

# Background of the Analysis
- Part 1: Scrape Titles and Preview Text from Mars News
1. Use automated browsing to visit the Mars news site. Inspect the page to identify which elements to scrape.
2. Create a Beautiful Soup object and use it to extract text elements from the website.
3. Extract the titles and preview text of the news articles that were scraped. Store the scraping results in Python data structures as follows:
  - Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview.
  - Store all the dictionaries in a Python list.
4. Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file.
