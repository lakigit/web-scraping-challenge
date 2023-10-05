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
- _**Part 1: Scrape Titles and Preview Text from Mars News**_
    1. Use automated browsing to visit the "Mars news site". Inspect the page to identify which elements to scrape.
    2. Create a Beautiful Soup object and use it to extract text elements from the website.
    3. Extract the titles and preview text of the news articles that were scraped. Store the scraping results in Python data structures as follows:
        - Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview.
        - Store all the dictionaries in a Python list.
    4. Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file.
- _**Part 2: Scrape and Analyse Mars Weather Data**_
    1. Use automated browsing to visit the "Mars Temperature Data Site". Inspect the page to identify which elements to scrape.
    2. Create a Beautiful Soup object and use it to scrape the data in the HTML table.
    3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:
        - id: the identification number of a single transmission from the Curiosity rover
        - terrestrial_date: the date on Earth
        - sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
        - ls: the solar longitude
        - month: the Martian month
        - min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
        - pressure: The atmospheric pressure at Curiosity's location\
    4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
    5. Analyse dataset by using Pandas functions to answer the following questions:
        - How many months exist on Mars?
        - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
        - What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:\
              -  Find the average minimum daily temperature for all of the months.\
              -  Plot the results as a bar chart.\
          ![image](https://github.com/lakigit/web-scraping-challenge/assets/138610916/5b641342-f408-4a22-88fc-4c8ce20631a7)

        - Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:\
              -  Find the average daily atmospheric pressure of all the months.\
              -  Plot the results as a bar chart.\
          ![image](https://github.com/lakigit/web-scraping-challenge/assets/138610916/9581a3b7-db56-4724-b0c4-c8c71edefbee)

        -  About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
              -  Consider how many days elapse on Earth in the time that Mars circles the Sun once.
              -  Visually estimate the result by plotting the daily minimum temperature.\
 ![image](https://github.com/lakigit/web-scraping-challenge/assets/138610916/ede7b627-ebc6-4f83-b952-1b9289eda385)

    6. Export the DataFrame to a CSV file.
