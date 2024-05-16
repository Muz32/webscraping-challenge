# webscraping-challenge
The assignment focuses on using the web scraping tool 'Beautiful Soup' in Jupyter Notebook to scrape data from two different websites about Mars news and weather data. Other tools used to analyse data include Pandas functions and Matplotlib. The output for this challenge is divided into two deliverables:

## Deliverable 1: Scrape Titles and Preview Text from News Articles
Under this deliverable, I extracted news articles from a given website and stored them in a Python dictionary. The extracted data was also exported to a JSON file named `NASA_news.json` in the subfolder `Output`.

## Deliverable 2: Scrape and Analyze Mars Weather Data from a Table
I scraped a table containing Mars temperature data, stored it into a Python dictionary, and then transferred the data into a Pandas DataFrame. The different column data was then converted into appropriate data types for further analysis.

The data analysis was performed using Pandas functions and Matplotlib, which provides the following insights:

- Months on Mars
- Martian Days in Dataset
- Temperature Analysis:
  - Coldest and Warmest Months: By calculating the average minimum daily temperature for each month, we can identify the coldest and warmest periods.
  - Temperature Plot: A bar chart visualizing the average temperatures across Martian months.

- Atmospheric Pressure:
  - Lowest and Highest Pressure: The average daily atmospheric pressure is computed for each month to find the months with the lowest and highest pressure.
  - Pressure Plot: A bar chart displaying the pressure trends over the Martian months.

- Martian Year:visual estimate terrestrial days in a Martian year.

Visualizations such as bar charts for temperature and pressure are included to provide a clear representation of the climate trends on Mars.

## Websites Used for Scraping Data
- [Mars News: Website containing the latest news articles about Mars](https://static.bc-edx.com/data/web/mars_news/index.html)
- [Mars Temperature Data: Website with a table of Mars temperature data](https://static.bc-edx.com/data/web/mars_facts/temperature.html)

## Python Packages Used
The following Python packages were installed in my Jupyter Notebook environment to complete this assignment challenge:

- `splinter[selenium4]`: Used for browser automation and interaction with dynamic web pages.
- `bs4` (Beautiful Soup 4): Utilized for parsing HTML and XML documents to extract data.
- `html5lib`: A Python library for parsing HTML data.
- `lxml`: Another library for processing XML and HTML in Python.
- `selenium`: Used for automating web browsers and performing web scraping tasks that require JavaScript execution.

## Files
- `part_1_mars_news.ipynb`: Notebook containing the web scraping code for Mars news.
- `part_2_mars_weather.ipynb`: Notebook with the web scraping and analysis of Mars weather data.
  - `Output/`
    - `mars_temperature_df.csv`: CSV file with the Mars temperature data.
    - `NASA_news.json`: JSON file with the scraped news articles.

