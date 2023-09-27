# Scrapy Web Crawler

This is a web crawling project built using the Scrapy framework in Python.

## Overview

This project contains a spider crawls through the /books.toscrape.com and collect the books data from all the page of the website, also as it scraps<stronge> I have created middleware and pipeline so it can directly get stored in mysql database </stronge>or run 
```
scrapy crawl booksider -O to-the-file.json or .csv
```
## Getting Started

### Prerequisites

- Python 3.6 or higher
- Scrapy (`pip install scrapy`)

### Installing

Clone this repository:

```bash
git clone https://github.com/yourname/scrapy-crawler.git
cd scrapy-crawler
```

