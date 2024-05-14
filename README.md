# webscraping-challenge
The assignemnet challenge focusses on using the web-scraping tool 'beatiful soup' in jupyter notebook to scrape data from two different websites about Mars news and weather data. The output for this challenge is divided into two deliverables:

# Deliverable 1: Scrape titles and preview text (from news articles)
Under this delieverable I extracted new articles from a given website and stored it in a python dictionary. The extracted data was also exported to a json file named 'NASA_news.json'in the sub folder 'Output.  

# Deliverable 2: Scrape and analyse Mars weather data (from a table)
I scraped a table containing Mars temperature data, stored it into a python dictionary and then transfered the data into a pandas data frame. The different column data was then converted into appropriate data types for further analysis.


## Websites used for scraping data
https://static.bc-edx.com/data/web/mars_news/index.html
https://static.bc-edx.com/data/web/mars_facts/temperature.html

The above websites are operated by edX Boot Camps LLC. 

## Files
`part_1_mars_news.ipynb`
`part_2_mars_weather.ipynb`
  - `Output`
      -`mars_temperature_df.csv`
      -`NASA_news`.json
