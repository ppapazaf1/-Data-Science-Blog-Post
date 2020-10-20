# -Data-Science-Blog-Post
 Data Science Blog Post - Project 1

Medium Post
https://medium.com/@panagiotis.papazafeiropoulos/athens-and-airbnb-in-the-pandemic-era-87f05def1ca0

This Notebook is related with the analysis of Airbnb data for Athens

Athens is one of the cities that the use of Airbnb by travelers had a huge increase the past years, 
while at the same time Greece experienced an increase in tourism overall. 
However the impact of Covid-19 pandemic in Greek tourism was dramatic, as for the rest of the world. 
We will try to analyze the current status of Airbnb with the latest data provided by insideairbnb.com.

In order to perform the analysis and due to the fact that the latest available data
from insideairbnb.com are from July, we will use this month's data and when necessary 
respective month's data from past years, where available, that is apart from 2020, also for 2015, 2018 and 2019. 
This seems a good month to be used for the analysis, since as of June 15 the international tourism period began in Greece. 

The issues in concern are:
The effect that pandemic had in the properties listed in Athens through the platform
The usage of the platform for travelers
The dispersion of available properties in the city


The following files were used:

- Summary information and metrics for listings in Athens
listings_sum_2007  (July 2020)
listings_sum_1907  (July 2019)
listings_sum_1807  (July 2018)
listings_sum_1507  (July 2015)

- Detailed Listings data for Athens
listings_2007.csv (July 2020)
listings_1907.csv (July 2019)
listings_1807.csv (July 2018)
listings_1507.csv (July 2015)

- Detailed Calendar Data for listings in Athens
calendar_2007.csv.gz  (July 2020)
calendar_1907.csv.gz  (July 2019)
calendar_1807.csv.gz  (July 2018)
calendar_1507.csv.gz  (July 2015)

- Summary Review data and Listing ID
reviews_2007.csv 

- Neighbourhood list
neighbourhoods.csv


The following libraries were used:
- pandas 
- numpy 
- matplotlib
- re
- seaborn 
- folium

An explorarion with descriptive statistics was performed throughout this notebook, by using the above datasets.

Conclusion
We analyzed the data to understand, in high level, the implication that the pandemic had on properties, 
airbnb users and the communities. 
Based on the fact that tourism in Athens had a huge increase during past year, the pandemic seems 
to have ceased further development and it remains to see how the coronavirus will be tackled in the near future, 
in order to recognize if the impact that is bringing in the tourist industry is permanent or not.
