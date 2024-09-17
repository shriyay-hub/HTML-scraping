# HTML-scraping



This repository contains code and data for a project on web scraping and data analysis. The project involves scraping data from two websites about Mars:

* [Mars news website](https://mars.nasa.gov/news/)
* [Mars temperature data site](https://static.bc-edx.com/data/web/mars_facts/temperature.html)

The scraped data is stored in two files:

* `mars.json` contains a list of dictionaries, each of which represents a Mars news article. The dictionaries contain the title and preview text of each article.
* `mars_data.csv` contains a table of Mars weather data. The columns in the table are `id`, `terrestrial_date`, `sol`, `ls`, `month`, `min_temp`, and `pressure`.

The code used to scrape the data is in two Jupyter Notebooks:

* `part_1_mars_news.ipynb` contains code for scraping Mars news articles.
* `part_2_mars_weather.ipynb` contains code for scraping and analyzing Mars weather data.
