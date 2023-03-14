# data_collection_challenge
Module 11 Data Collection Challenge

By A.Narag

March 16, 2023

This project has two deliverables:

- Part 1: Scrape titles and preview text from Mars news articles.  See Jupyter Notebook 'part_1_mars_news.ipynb'

- Part 2: Scrape and analyze Mars weather data, which exists in a table. See Jupyter Notebook 'part_2_mars_weather.ipynb'

Part 1: Scrape Titles and Preview Text from Mars News
1. Visit the Mars news siteLinks (https://static.bc-edx.com/data/web/mars_news/index.html). Inspect the page to identify which elements to scrape.
2. Create a Beautiful Soup object and use it to extract text elements from the website.
3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures.
4. Optionally, store the scraped data in a file. Export the scraped data to a JSON file.

Part 2: Scrape and Analyze Mars Weather Data
1. Use automated browsing to visit the Mars Temperature Data SiteLinks (https://static.bc-edx.com/data/web/mars_facts/temperature.html). Inspect the page to identify which elements to scrape. 
2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. 
3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.
4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
5. Analyze your dataset by using Pandas functions to answer the following questions:
  - How many months exist on Mars? The number of months on Mars is: 12. 
  - How many Martian (and not Earth) days worth of data exist in the scraped dataset? The number of Martian days (sols) for which data was collected: 1867.
  - What are the coldest and the warmest months on Mars (at the location of Curiosity)?  The month with the lowest minimum temperature on Mars is: 3; and the month with the highest minimum temperature on Mars is: 8.
  - Which months have the lowest and the highest atmospheric pressure on Mars? The month with lowest average pressure on Mars is: 6; and the month with highest average pressure on Mars is: 9.
  - About how many terrestrial (Earth) days exist in a Martian year? The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.
6. See 'mars_data.csv' for export the Mars DataFrame to a CSV file.
