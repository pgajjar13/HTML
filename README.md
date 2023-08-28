# HTML

Module 11 Challenge

This project involves web scraping of [Mars news articles](https://redplanetscience.com/) and [Mars weather data](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html), and performing an analysis on the latter half.

## Deliverable 1: Scrape Titles and Preview Text from Mars News

In the *part_1_mars_news.ipynb* Jupyter notebook, automated browsing is used to visit the Mars NASA news site and extract text elements using a Beautiful Soup object. Titles and preview text of the news articles are extracted, each title-and-preview pair are stored in a Python dictionary, and each dictionary is given two keys: title and preview. Finally, all the dictionaries are stored in a Python list and the list is printed in the notebook. 

## Deliverable 2: Scrape and Analyze Mars Weather Data

In the *part_2_mars_weather.ipynb* Jupyter notebook, automated browsing is used to visit the Mars Temperature Data Site and extract data in the HTML table using a Beautiful Soup object. The scraped data is assembled into a Pandas DataFrame with columns having the same headings as the table on the website. The data types are examined and cast to the appropriate types as necessary. Finally, the dataset is analyzed using pandas functions and matplotlib in order to answer and visualize various questions about the data. The dataset is then exported as a csv file into the Resources folder.
