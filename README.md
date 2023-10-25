# Web Scraping from Nobroker.com using Selenium

Selenium is a popular open-source framework and web testing tool that is often used for web scraping, among other tasks. It provides a way to automate interactions with websites and retrieve data from them programmatically. Here are some key points about Selenium in the context of web scraping:

1. **Browser Automation:** Selenium allows you to automate web browsers, such as Google Chrome, Firefox, or Microsoft Edge. It can mimic human interactions with a web page, like clicking links, filling out forms, and navigating through a website.

2. **Dynamic Content:** Selenium is particularly useful for scraping websites with dynamic or JavaScript-driven content. Traditional web scraping tools might struggle with such websites, but Selenium can render and interact with dynamic elements effectively.

3. **Cross-Browser Compatibility:** You can use Selenium to scrape data from multiple web browsers, ensuring that your scraping scripts work across various platforms.

4. **Programming Languages:** Selenium supports various programming languages like Python, Java, C#, and more. This makes it accessible to developers with different language preferences.

5. **Community and Documentation:** Selenium has a large and active community, which means there is extensive documentation, tutorials, and online support available.

6. **Data Extraction:** Once you've automated browser interactions to navigate to the desired web pages, you can use Selenium to extract data from the page's HTML source code. You can parse this data using libraries like BeautifulSoup in Python.

7. **Complex Scraping Scenarios:** Selenium is valuable for scraping scenarios where other methods, such as sending HTTP requests and parsing the responses, are insufficient. This is especially true when dealing with sites that employ heavy JavaScript, AJAX, or user interactions.

However, while Selenium is powerful, it has some drawbacks. It can be slower and resource-intensive compared to other scraping methods. Additionally, it requires a web browser to be open during the scraping process, which may not be ideal for large-scale or continuous scraping.

In summary, Selenium is a versatile tool for web scraping, particularly when dealing with complex, dynamic websites that require interaction with a web browser. It is widely used by developers and data scientists to extract data from websites for various purposes, such as data analysis, research, and automation.



This project aims at extracting the description of the property, price per square feet, total squarefeet, property facing, number of bedrooms, number of baths, parking availability from the No-Broker.com website

Import the required packages:

import numpy as np
import pandas as pd
import requests
from bs4 import BeautifulSoup
!pip install selenium

Requesting access to the data from the website

Extracting the webpage data in html readable format

Scraping the data in the list format

Filtering the data using loop and conditions

Total price of the property can be calculated

Converting the lists into a dataframe.

The extracted data in the tabular format can now be used for analysis, model building and deployment to production.
