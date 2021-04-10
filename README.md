# Python-Web-Scraping

Web scraping is an automatic process of extracting information from web. This chapter will give you an in-depth idea of web scraping, its comparison with web crawling, and why you should opt for web scraping. You will also learn about the components and working of a web scraper.

## Web Crawling v/s Web Scraping
The terms Web Crawling and Scraping are often used interchangeably as the basic concept of them is to extract data. However, they are different from each other. We can understand the basic difference from their definitions.

Web crawling is basically used to index the information on the page using bots aka crawlers. It is also called indexing. On the hand, web scraping is an automated way of extracting the information using bots aka scrapers. It is also called data extraction.

## Components of a Web Scraper
A web scraper consists of the following components −

- Web Crawler Module
A very necessary component of web scraper, web crawler module, is used to navigate the target website by making HTTP or HTTPS request to the URLs. The crawler downloads the unstructured data (HTML contents) and passes it to extractor, the next module.

- Extractor
The extractor processes the fetched HTML content and extracts the data into semistructured format. This is also called as a parser module and uses different parsing techniques like Regular expression, HTML Parsing, DOM parsing or Artificial Intelligence for its functioning.

- Data Transformation and Cleaning Module
The data extracted above is not suitable for ready use. It must pass through some cleaning module so that we can use it. The methods like String manipulation or regular expression can be used for this purpose. Note that extraction and transformation can be performed in a single step also.

- Storage Module
After extracting the data, we need to store it as per our requirement. The storage module will output the data in a standard format that can be stored in a database or JSON or CSV format.

## Working of a Web Scraper

![image](https://user-images.githubusercontent.com/58425689/114261037-0c2ac200-99f8-11eb-833d-2690ef74659e.png)

We can understand the working of a web scraper in simple steps as shown in the diagram given above.

Step 1: Downloading Contents from Web Pages \
In this step, a web scraper will download the requested contents from multiple web pages.

Step 2: Extracting Data \
The data on websites is HTML and mostly unstructured. Hence, in this step, web scraper will parse and extract structured data from the downloaded contents.

Step 3: Storing the Data \
Here, a web scraper will store and save the extracted data in any of the format like CSV, JSON or in database.

Step 4: Analyzing the Data
After all these steps are successfully done, the web scraper will analyze the data thus obtained.

