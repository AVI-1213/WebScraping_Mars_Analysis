# Mars Data Web Scraping and Analysis
![21033014001](https://github.com/AVI-1213/WebScraping_Mars_Analysis/assets/156638175/d78b4fc8-2e03-48e5-bcef-2200b5239a1c)
-image source[https://www.cnn.com/2021/02/12/us/gallery/mars-best-photos/index.html]



## Overview
This project involves scraping Mars news articles and weather data, followed by data analysis.

## Deliverables
1. **Scrape Mars News:** Extract titles and preview text from Mars news articles.
2. **Scrape and Analyze Mars Weather Data:** Scrape weather data and perform analysis.

## Files
- `part_1_mars_news.ipynb`: Notebook for scraping Mars news.
- `part_2_mars_weather.ipynb`: Notebook for scraping and analyzing Mars weather data.
- `data/mars_weather.csv`: CSV file with scraped Mars weather data.
- `README.md`: Project documentation.


### Part 1: Scrape Mars News
1. Open `part_1_mars_news.ipynb` in Jupyter Notebook.
2. Scrape the [Mars news site](https://redplanetscience.com/) for titles and preview text.
3. Store results in a list of dictionaries and optionally export to `data/mars_news.json`.

### Part 2: Scrape and Analyze Mars Weather Data
1. Open `part_2_mars_weather.ipynb` in Jupyter Notebook.
2. Scrape the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) for weather data.
3. Assemble data into a Pandas DataFrame.
4. Perform data analysis and visualize:
   - Number of months on Mars.
   - Number of Martian days in the dataset.
   - Coldest and warmest months.
   - Months with lowest and highest atmospheric pressure.
   - Estimate the number of Earth days in a Martian year.
5. Export the DataFrame to `data/mars_weather.csv`.

## Tools and Libraries
This project uses the following tools and libraries:
- **Jupyter Notebook**: For interactive coding and analysis.
- **Splinter**: For automated browsing.
- **BeautifulSoup**: For parsing HTML and extracting data.
- **Matplotlib**: For data visualization.
- **Pandas**: For data manipulation and analysis.



---
## Contributors

- [Avinash K]([link to my GitHub profile](https://github.com/AVI-1213))

  
```python
from splinter import Browser
from bs4 import BeautifulSoup as soup
import matplotlib.pyplot as plt
import pandas as pd



