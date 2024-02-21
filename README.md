Project Name: Supermarket Comparison

Description:
This project analyzes and compares prices and products across different supermarkets -  Mercadona and Dia. It aims to provide insights into product offerings, price variations, and potential cost savings.

Tools Used:
Python 3.7.9
NumPy
Pandas
Matplotlib
Seaborn
BeautifulSoup
Requests

Primary Objective:
Conduct a comprehensive analysis of specific supermarkets.
Compare product prices and availability across different stores.
Identify trends and patterns in product offerings and pricing strategies.

Challenges:
Accessing Mercadona's API: Due to lack of documentation, direct API access was not possible.
Data Acquisition: Web scraping was used to gather data from Dia's website, which employs anti-scraping measures.
Data Integration and Standardization: Products and categories were standardized for accurate comparison across stores.
Price Updates: Some product prices changed during the analysis period, requiring additional analysis.

Analysis Conducted:
Shopping Basket Analysis: 9 basic household products were analyzed in detail, comparing prices and providing summaries.
Expensive Items: The most expensive items were identified and categorized.
Product Availability and Categories: The number of products offered in different categories was analyzed.
Price Changes in Mercadona: Products with price changes during the analysis period were identified and further investigated.

Outcomes:
The project provides valuable insights into product offerings and pricing strategies of different supermarkets.
Consumers can use this information to make informed choices about where to shop for specific products.
The analysis methodology can be applied to compare other stores and product categories.

Files structure:
1_Mercadona_API - here you can see the code to obtain the information about Mercadona´s products via API.
2_DIA_Scraping - contains code to see get the data from Dia via web scraping.
Mercadona_analysis - basic descriptive information about the data.
analysis_DIA - basic descriptive information about the data.
comparacion - Houses all analysis scripts comparing products and prices across supermarkets.
Mercadona_precio_comparacion - Analyzes price changes of the week 05-11.02.2024 for Mercadona.


Note:
This README file provides a general overview of the project. Please refer to the project code and documentation for more details.