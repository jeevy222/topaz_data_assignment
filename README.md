# Web Scraping with Python Code
## Overview
Scrapy is a fast high-level web crawling and web scraping framework, used to crawl websites and extract structured data from their pages. It can be used for a wide range of purposes, from data mining to monitoring and automated testing.

## Requirements
Python 2.7 or Python 3.4+
Works on Linux, Windows, Mac OSX, BSD

## Install
#### The quick way:

`pip install scrapy`
For more details see the install section in the documentation: https://docs.scrapy.org/en/latest/intro/install.html

#### Third party Packages
Python Requests : http://docs.python-requests.org/en/master/

`pip install requests`
Basically, it opens the webpage for us in this one.

BeautifulSoup 4 : https://www.crummy.com/software/BeautifulSoup/bs4/doc/

`pip install beautifulsoup4`
This allows us to search & extract content from an HTML webpage

steps:
  - import requests,pandas,BeautifulSoap
  - fetch URL
  - Soupify
  - extract Data into csv file named it as export11_df

##### Google Big Query Can be connected by 
1.  Web UI
2.  REST API
3.  Command Line.

go to https://bigquery.cloud.google.com/table/third-framing-242009:data_assignment.data_assignment

### My Project 7247
##### Data Assignment
- Click on the plus sign to create table
- In source Data select Create from Source
- File Upload in Locaton and keep the file type as csv.
- In destination table name it as dat_assignment.data
- Check in Automatically Detect in Schema field.
- It will give 8 columns with there respective data type and I have edited what they represents.
- Go to Query editor and type SELECT  FROM [third-framing-242009:data_assignment.data_assignment] LIMIT 1000
- Run the Query
- Take the Result in csv file and I have named it as results-20190528-165818.csv
