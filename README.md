
"Decoding Demand Trends: A Data-Driven Analysis of Electric Bike Rentals in India"

Problem Statement:
Company has recently suffered considerable dips in its revenues. They have contracted a consulting company to understand the factors on which the demand for these shared electric cycles depends. Specifically, they want to understand the factors affecting the demand for these shared electric cycles in the Indian market.

Column Profiling: ● datetime: datetime

● season: season (1: spring, 2: summer, 3: fall, 4: winter)

● holiday : whether day is a holiday or not

● workingday : if day is neither weekend nor holiday is 1, otherwise is 0.

● weather: o 1: Clear, Few clouds, partly cloudy

o 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist

o 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds

o 4: Heavy Rain + Ice Pellets + Thunderstorm + Mist, Snow + Fog

● temp: temperature in Celsius

● atemp: feeling temperature in Celsius

● humidity: humidity

● windspeed: wind speed

● casual: count of casual users

● registered: count of registered users

● count: count of total rental bikes including both casual and registered

The company wants to know:

Which variables are significant in predicting the demand for shared electric cycles in the Indian market? How well those variables describe the electric cycle demands

#Step 1: Understanding the Data:
The journey began with exploring and preparing the dataset, which included variables such as datetime, season, weather, temperature, humidity, and bike counts. Basic data checks(missing values handling/duplicate rows/outlier handling/converting numerical columns to categorical columns) were performed to ensure data integrity and completeness.

#Step 2: Exploratory Data Analysis (EDA):
Univariate and bivariate analyses were conducted to understand the distribution and relationships between various factors and bike rental counts. Visualizations revealed intriguing patterns, such as higher demand during clear weather and weekdays, as well as seasonal variations in rental counts.

#Step 3: Hypothesis Testing:
To delve deeper into the factors influencing demand, hypothesis testing was conducted. Tests examined the effects of variables like day category (weekday/weekend), weather conditions, and seasons on bike rental counts. Results indicated significant relationships between weather conditions, seasons, and rental demand.

#Step 4: Insights and Recommendations:
Insights gained from the analysis provided valuable recommendations for the company. For instance, focusing marketing efforts on weekdays and during clear weather could optimize rental revenues. Additionally, understanding seasonal demand patterns could inform resource allocation and operational planning.

Conclusion:
The data-driven analysis offered a comprehensive understanding of demand trends for shared electric cycles in the Indian market. By leveraging insights from this analysis, company can make informed decisions to enhance user experience, optimize operations, and drive business growth.


