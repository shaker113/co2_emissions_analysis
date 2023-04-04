# Analysis of CO2 and Temperature Trends in Jordan

This repository contains the code and data for an analysis of CO2 and temperature trends in Jordan. The goal of this analysis is to examine the relationship between atmospheric CO2 concentrations and temperature in Jordan over the past few decades. The analysis was done using publicly available data from the World Bank and focuses on the period from 1900 to 2020.

## Data
The data used for this analysis was obtained from the World Bank's Open Data Portal (https://data.worldbank.org/).

* CO2 data: The yearly cumulative co2 emissions in jordan.

* Temperature data: The monthly temperature data for each governorate of Jordan.

* Precipitation data : The monthly Precipitation data for each governorate of Jordan.

* Agricultural land data : The yearly agricultural land (sq. km) in Jordan.

* Electricity consumption data : The yearly electricity consumption by sector in Jordan.

## Analysis
I started by importing the data into a Jupyter Notebook using the pandas library. I then cleaned and processed the data to ensure that it was in a usable format. This included removing missing data, converting data types, and aggregating the data by year.

Next, I created visualizations to explore the trends in CO2 emissions over time. I used line plots to show the overall trend in CO2 emissions and bar plots to show the yearly change in emissions.

Finally, I conducted a regression analysis to model the relationship between CO2 emissions and time. I found that there was a significant positive relationship between the two variables, indicating that CO2 emissions have been increasing over time in Jordan.


### CO2 Emissions and Temperature in Jordan
![CO2 Emissions and temperature](https://user-images.githubusercontent.com/112093285/229790956-9427cc2c-3b4e-4818-bda5-88bd17b8ed60.png)

### CO2 Emissions and Agricultural land
![CO2 Emissions and Agricultural land](https://user-images.githubusercontent.com/112093285/229790975-5c8fecbd-b423-48f9-a782-76b143acc8f1.png)


### Jordan Temperature distribution over time
![Temperature in Jordan](https://user-images.githubusercontent.com/112093285/229791030-23779636-19d3-444a-b693-b73af243460c.png)

### Jordan Temperature distribution for different time period
![Jordan temps distribution for different time period](https://user-images.githubusercontent.com/112093285/229791002-d8ee5121-9430-4f04-8c6e-2e18163ff94a.png)

### Jordan Precipitation distribution over time
![Precipitation in Jordan](https://user-images.githubusercontent.com/112093285/229791066-92f5a2a6-6dc6-4bdb-b873-4f74277e9721.png)

### Jordan precipitation Distribution for different time period
![Jordan precipitation Distribution](https://user-images.githubusercontent.com/112093285/229791047-b4f9d74b-9592-42a2-b6f8-f198ddd53034.png)

The other resulting visualizations and analysis are included in the Jupyter notebook 'notebook.ipynb'.

## Conclusion
The analysis shows a clear upward trend in atmospheric CO2 concentrations over the past few decades, and a corresponding increase in temperature in Jordan. The line plot suggest a strong positive correlation between CO2 and temperature. This indicates that as CO2 levels continue to rise, temperatures in Jordan are likely to continue to increase as well.

Furthermore, the analysis shows that precipitation and agricultural land in Jordan have decreased with the increasing temperatures. This highlights the potential impacts of climate change on Jordan's economy and agriculture sector. Overall, these findings emphasize the importance of taking action to mitigate the effects of climate change on Jordan's environment and society.
