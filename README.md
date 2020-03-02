# Global Financial Crisis
### Jack Harvey

# Overview
This file uses data from the USDA ERS and the Federal Housing Finance Agency to identfiy the civilian labor force, unemployment rates, birth rates, and median housing prices. This data is loaded and analyzed through the use of python to clean the data and create visualizations to identify the trends in the data found. 

## Libraries Used
* import csv
* import pandas as pd
* import matplotlib.pyplot as plt
* import re
* from scipy.stats import linregress

# Binned Data and Created Visualizations

The goal of our project was to compare the two states with the smallest and largest civilian labor forces to determine whether the Global Financial Crisis impacted them in similar ways. 
This first visualization groups the states by the size of their civilian labor force (< 1 million) and compares this to their unenployment rates.

![](Housing%20Data/Data/1m_CLF_unemp.png)
This next visualization groups states by their size (> 5 million) and compares their unemployment rates. 

![](Housing%20Data/Data/5m_CLF_unemp.png)

## Similar Trends in Data

We were then able to identify that both California and Rhode Island were in similar categories in regards to the median household price and found this interesting. 

From here we decided to compare their unemployment rates to their median household prices throughout the years to determine whether or not they were similar.

![](Housing%20Data/Data/unemp_house_price_rhode_island.png)

![](Housing%20Data/Data/unemp_house_price_cali.png)

![](Housing%20Data/Data/unemp_by_year_RI.png)

From this it can be said that throughout the years both states followed similar trends in response to the Global Financial Crisis and that the size of the state does not necessarily play a role in how the global financial cris effected each states. But it can be said that the cost of living in each state does play a role in the response to the Recession in 2007.

![](Housing%20Data/Data/unemp_by_house_price_5m.png)

![](Housing%20Data/Data/unemp_house_price_1m_2m.png)
