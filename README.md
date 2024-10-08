Mars News and Weather Data Web Scraping Project
Overview
This project consists of two main tasks:

Scraping Mars news articles from a static site and collecting titles and preview texts.
Scraping and analyzing Mars weather data from a provided table.
Initially, the assignment recommended using Splinter for web scraping, but due to complications and limitations, I switched to using the requests library for scraping and BeautifulSoup for parsing the HTML. This approach simplifies the process, makes the code more reliable, and works without needing a specific web driver like ChromeDriver.

Files
part_1_mars_news.ipynb: A notebook that scrapes Mars news titles and preview texts.
part_2_mars_weather.ipynb: A notebook that scrapes and analyzes Mars weather data.
mars_weather_data.csv: The exported CSV file containing the scraped Mars weather data.
Tools and Libraries
The project makes use of the following Python libraries:

requests: For making HTTP requests to fetch HTML content.
BeautifulSoup: To parse the HTML content and extract data.
pandas: For data manipulation and analysis.
matplotlib: For visualizing data as bar charts.

Make sure you have these libraries installed. You can install them via pip: pip install requests beautifulsoup4 pandas matplotlib
