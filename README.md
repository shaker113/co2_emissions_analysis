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

The resulting visualizations and analysis are included in the Jupyter notebook 'notebook.ipynb'.

![CO2 Emissions and Agricultural land](https://user-images.githubusercontent.com/112093285/229786197-f0fb7a4b-d694-4e20-a685-e66fb5d6961c.png)
![Jordan temps distribution for different time period](https://user-images.githubusercontent.com/112093285/229786204-cdbdcd0f-0a64-45a0-8979-5cd80d4b89a4.png)
![CO2 Emissions and temperature](https://user-images.githubusercontent.com/112093285/229786205-a2015ae1-33fb-45c6-bc28-e6119d520023.png)
![Jordan precipitation Distribution](https://user-images.githubusercontent.com/112093285/229786208-98e1aeba-0ff6-4597-83a4-a7799ca2b334.png)
![Temperature in Jordan](https://user-images.githubusercontent.com/112093285/229786211-758ab9cb-81f1-48d5-b254-391f9b77e8d7.png)
![Precipitation in Jordan](https://user-images.githubusercontent.com/112093285/229786214-4bb4a28a-8a40-4f10-b709-6a4e4daa2d73.png)

## Conclusion
The analysis shows a clear upward trend in atmospheric CO2 concentrations over the past few decades, and a corresponding increase in temperature in Jordan. The line plot suggest a strong positive correlation between CO2 and temperature. This indicates that as CO2 levels continue to rise, temperatures in Jordan are likely to continue to increase as well.

Furthermore, the analysis shows that precipitation and agricultural land in Jordan have decreased with the increasing temperatures. This highlights the potential impacts of climate change on Jordan's economy and agriculture sector. Overall, these findings emphasize the importance of taking action to mitigate the effects of climate change on Jordan's environment and society.
