Crawl Proposal: IMDb Data Collection
1. Objectives
Purpose: The goal of this project is to scrape IMDb to collect data on the most recent best movies and identify the most prominent genre.

Goals:
Extract the list of top-rated recent movies from IMDb.
Analyze the genre distribution of these movies to determine the most prominent genre.
2. Scope
Target Website: IMDb (https://www.imdb.com/)
Data Requirements:
Movies Data: Title, release date, rating, and genre(s).
Prominent Genre: Most frequently occurring genre among the top-rated movies.

Tools and Technologies:

BeautifulSoup: For parsing HTML and extracting movie data.
Scrapy: For managing the crawling process and handling multiple pages efficiently.
Selenium: For interacting with dynamic content and JavaScript-rendered data.
Crawling Strategy:

Page Identification: Start with IMDb’s top-rated movie pages from the 21st century.
Data Extraction: Use BeautifulSoup to parse movie details from the HTML content.
