# Global Gasoline Price Analysis


## Table of content

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Collection](#data-collection)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)



### Project Overview
In this project, I scraped data on the price of gasoline by country worldwide to analyze global pricing trends and identify regional disparities.




### Data Sources
Data for this project was sourced from  [GlobalPetrolPrices.com](https://www.globalpetrolprices.com/), a comprehensive platform providing up-to-date fuel price information across countries worldwide. 




### Tools 
- Python (BeautifulSoup, Requests, and pandas) 
- Google Sheet
- Looker Studio




### Data Collection
The data was scraped using Python libraries Beautiful Soup and Requests to ensure accurate and detailed insights into global gasoline price trends. Specifically, the following tasks were performed: 
- Importing the Libraries
- Specifying the URL
- Sending an HTTP request to the website and retrieving the HTML content
- Parsing the HTML content to extract the relevant data fields
- Cleaning and structuring the extracted data into a tabular format using pandas
- Exporting the cleaned dataset to a CSV file for further analysis and visualization



### Data Preparation
The data was cleaned using Google Sheets. Specifically, the following tasks were performed:

- Importing the scraped data into Google Sheets
- Formatting columns for clarity, such as separating country names and currency format of gasoline prices
- Handling inconsistent data
- Adding country specific data to categorize countries by regions, GDP, population, and oil producing status (oil producing or non-oil producing) for comparative analysis



 ### Exploratory Data Analysis
  
In this phase, the dataset was explored to answer key questions about global gasoline price trends, including:
- What are the regional variations in gasoline prices across different countries worldwide?
- How do gasoline prices vary across oil-producing versus non-oil-producing countries?
- How do gasoline prices correlate with the GDP of countries across different regions?
- What role does population density play in gasoline price variations within specific regions?



### Findings
The findings derived rom this analysis are as follows:

- Regional variations in gasoline prices were evident, with North America and Western Europe experiencing higher prices due to factors like taxes and economic development, while Asia and Africa had lower prices.

- The gasoline prices of oil-producing countries were typically lower, whereas non-oil-producing countries faced higher prices due to imported crude oil costs.

- There was a positive correlation between a country’s GDP and its gasoline prices, with higher GDP per capita often leading to higher prices.

- Additionally, more densely populated regions showed higher gasoline prices due to increased demand for transportation.



### Recommendations 
In light of the findings from the data analysis, the following recommendations are proposed:
- For oil-producing countries, consider revising subsidies to better align domestic gasoline prices with international market rates, thereby reducing fiscal strain.

- In non-oil-producing countries, implementing taxes that reflect environmental and economic costs could better manage fuel consumption and improve revenue.

- For countries with higher gasoline prices due to economic factors, policies aimed at economic diversification could help alleviate fuel cost pressures.

- Developing public transportation infrastructure and promoting alternative fuel vehicles in densely populated areas can help reduce gasoline prices by lowering demand.

- Regularly updating subsidies and taxes based on global crude oil prices and domestic economic conditions can help maintain stable gasoline pricing.



### Limitations 

1. The analysis is based solely on the data available from [GlobalPetrolPrices.com](https://www.globalpetrolprices.com/), which may not capture the most up-to-date or comprehensive gasoline pricing data across all countries.
   
2. The dataset does not include factors such as geopolitical influences or environmental policies that could impact gasoline prices.
   
3. The analysis assumes that GDP and population data are accurate representations of economic and demographic conditions, which may not account for all regional nuances.
   
4. The study does not differentiate between temporary price fluctuations due to market volatility and long-term pricing trends, which could affect the findings.
   
5. The inclusion of oil-producing status might oversimplify the complexity of subsidies and pricing mechanisms within different countries.



### References
GlobalPetrolPrices.com. (n.d.). Retrieved from https://www.globalpetrolprices.com/

