# Web Scraping using BeautifulSoup
Personal project for education

The idea is to extract information from a website and convert it for practical analysis. While there are several tools available for this purpose, in this article we’ll be using BeautifulSoup, a Python library designed for easily pulling data out of HTML and XML files.

Here, we’ll visit this Wikipedia page that contains several lists of best-selling books and extract the second table, for books between 50 million and 100 million copies sold.

**Libraries needed**

We only need 2 packages to handle the HTML file. We’ll be also using Pandas to create a data frame from the extracted data:
requests - Allows us to send HTTP requests and download the HTML code from the webpage;
beautifulsoup - Used to pull data out of the raw HTML file;
pandas - Python library for data manipulation. We'll use it to create our data frame.

**ressources**

https://www.crummy.com/software/BeautifulSoup/bs4/doc/
