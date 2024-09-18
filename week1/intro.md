# Well come to Web Scraping with Python!
## What is Web Scraping?
Web scraping is a technique to extract data from websites. It is a way to automate the process of copying data from websites. Web scraping is also known as web harvesting or web data extraction. It
is a process of fetching data from a website and saving it in a local file on your computer. 

## Why Web Scraping?
Web scraping is used to extract data from websites. It
is a way to automate the process of copying data from websites. Web scraping is also known as web harvesting or web data extraction. It
is a process of fetching data from a website and saving it in a local file on your computer.

## Tools for Web Scraping
There are many tools available for web scraping. Some of the popular tools are:
- BeautifulSoup
- Scrapy
- Selenium
- Requests
- LXML

## Where we can Extract Data?
We can extract data from any website. Some of the popular websites are:
- Google
- Facebook
- Twitter
- Instagram
- Amazon
- Flipkart
- Wikipedia
- StackOverflow
- GitHub
- LinkedIn
- Quora
- Reddit
- Pinterest
- YouTube
- data.gov
- weather.com
- imdb.com
- espn.com
- cnn.com
- bbc.com
- nytimes.com
- washingtonpost.com
- ## From Databases
- MySQL
- PostgreSQL
- SQLite
- MongoDB
- Redis
- Cassandra
- CouchDB
- HBase

## How to Extract Data from Websites by BeautifulSoup?
To extract data from websites, we need to install BeautifulSoup. You can install BeautifulSoup using the following command:
```bash
pip install beautifulsoup4
```
```python
from bs4 import BeautifulSoup
import requests
# LESSON 1: Extracting Data from Websites using BeautifulSoup FROM wikipedia about Data  Mining
url = 'https://en.wikipedia.org/wiki/Data_mining'

# here url is the website from which we want to extract data
response = requests.get(url)
# here response is the data we get from the website in response to checking the request is valid or not
soup = BeautifulSoup(response.text, 'html.parser')
# here soup is the variable which contains the data of the website in html format
# BeautifulSoup is the function which is used to extract data from the website
# syntax: BeautifulSoup( response.text, 'html.parser')
# response.text is the data we get from the website in response to checking the request is valid or not
# 'html.parser' is the parser which is used to parse the data of the website like html, xml, etc.

