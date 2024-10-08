# Mars News and Weather Data Web Scraping Project

### Overview
This project consists of two main tasks:
- Scraping Mars news articles from a static site to collect titles and preview texts.
- Scraping and analyzing Mars weather data from a provided table.

Initially, the assignment recommended using Splinter for web scraping. However, due to complications, I switched to using `requests` for fetching the data and `BeautifulSoup` for parsing the HTML. This approach simplifies the process and avoids the need for a specific web driver like ChromeDriver.

### Files Included
- `part_1_mars_news.ipynb`: A notebook that scrapes Mars news titles and preview texts.
- `part_2_mars_weather.ipynb`: A notebook that scrapes and analyzes Mars weather data.
- `mars_weather_data.csv`: A CSV file containing the scraped Mars weather data.

### Tools and Libraries Used
- `requests`: To make HTTP requests and fetch HTML content.
- `BeautifulSoup`: For parsing and extracting data from the HTML content.
- `pandas`: To manipulate and analyze the scraped data.
- `matplotlib`: To visualize the data using bar charts.

To install the required libraries, you can use the following command: pip install requests beautifulsoup4 pandas matplotlib
