# Web Scraping Project: Largest Companies in the United States by Revenue
This project involves scraping data from Wikipedia to obtain a list of the largest companies in the United States by revenue. The scraped data is then cleaned and transformed using Python and the Pandas library, followed by visualization and analysis using Power BI.

## Table of Contents
- Introduction
- Project Workflow
- Getting Started
- Data Extraction
- Data Transformation
- Power BI Dashboard
- Usage
- Contributing
- License
## Introduction
The goal of this project is to extract data from a Wikipedia page listing the largest companies in the United States by revenue, clean and transform the data, and finally visualize the insights using Power BI.

## Project Workflow
### Data Extraction: We use the requests library to fetch the HTML content of the Wikipedia page and BeautifulSoup for parsing it. We locate the relevant table containing the company data.

### Data Transformation: The scraped data is transformed using the Pandas library. We clean columns like 'Revenue growth', 'Revenue (USD millions)', and 'Employees' by removing symbols and converting data types.

### Data Loading: The cleaned data is saved as a CSV file in the specified directory using the Pandas to_csv() function.

### Power BI Dashboard: The data from the CSV file is loaded into Power BI, where it is visualized and analyzed to create insights.

## Getting Started
To get started with this project, you can follow these steps:

- Clone this repository to your local machine.
- Make sure you have Python and the required libraries (pandas, requests, beautifulsoup4) installed.
- Run the provided Python script to perform web scraping, data cleaning, and data loading.
## Data Extraction
The data extraction process involves fetching the HTML content of the Wikipedia page and parsing it using BeautifulSoup. We locate the relevant table containing the company data and extract the necessary information.

## Data Transformation
The scraped data is cleaned and transformed using the Pandas library. We convert columns like 'Revenue growth', 'Revenue (USD millions)', 'Employees', and 'Rank' to appropriate data types for analysis.

## Power BI Dashboard
The cleaned data is loaded into Power BI, where it can be imported, visualized, and analyzed. A dashboard is created using Power BI's visualization tools to provide insights into the largest companies in the United States by revenue.

## Usage
Run the provided Python script to perform data scraping, cleaning, and saving.
Import the generated CSV file into Power BI for visualization and analysis.
Contributing
Contributions to this project are welcome! Feel free to open issues or pull requests if you have suggestions, improvements, or new features to add.
