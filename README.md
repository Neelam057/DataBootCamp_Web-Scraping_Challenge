# Mars Web Scraping and Data Analysis Project

## Overview

This project involves scraping and analyzing data related to Mars news and weather. Using the web scraping techniques, extract titles and preview text from Mars news articles, and scrape weather data from a table of temperature and atmospheric pressure measurements.

---

## Project Structure

- **Part 1**: Scrape titles and preview text from Mars news articles.
- **Part 2**: Scrape and analyze Mars weather data from a table.
- **CSV file**: Mars weather dataframe was exported into a CSV file.

---

## Deliverables

### Deliverable 1: Scrape Titles and Preview Text from Mars News Articles

1. **Objective**: Extract the titles and preview texts from the Mars News website.
   
2. **Steps**:
   - Use automated browsing with **Splinter** to visit the Mars news site.
   - Inspect the page's HTML structure to identify the relevant elements (such as the titles and preview texts).
   - Create a **Beautiful Soup** object and use it to extract these elements.
   - Store each title and preview pair in a Python dictionary, where each dictionary has two keys: `title` and `preview`.
   - Store the dictionaries in a Python list.
   
3. **Files**:
   - `part_1_mars_news.ipynb`: Jupyter notebook for scraping Mars news.

### Deliverable 2: Scrape and Analyze Mars Weather Data

1. **Objective**: Scrape and analyze Mars weather data from a table on the Mars Temperature Data Site.
   
2. **Steps**:
   - Use automated browsing with **Splinter** to visit the Mars weather site.
   - Inspect the page’s HTML structure to identify the table elements containing the data.
   - Use **Beautiful Soup** to scrape the weather data from the HTML table.
   - Create a **Pandas DataFrame** to organize the data with the following columns:
     - `id`: Identification number of a single transmission.
     - `terrestrial_date`: Date on Earth.
     - `sol`: The number of elapsed Martian days (sols).
     - `ls`: Solar longitude.
     - `month`: Martian month.
     - `min_temp`: Minimum temperature in Celsius.
     - `pressure`: Atmospheric pressure at Curiosity's location.
   - Examine and, if necessary, convert the data types for proper analysis (e.g., convert date columns to `datetime`, or numerical values to `int` or `float`).

3. **Files**:
   - `part_2_mars_weather.ipynb`: Jupyter notebook for scraping and analyzing Mars weather data.



