
# Nigeria COVID-19 Data Analysis Using Python
 
  Covid-19 pandemic hit many countries hard and it affected almost all countries directly or in directly.
  Be it in the economy of the country or the live of it citizen which were been lost within the hit of the virus. 
  Pandas analytics was been used to extract data from  external data which where been store both by the **NCDC**
  and [Johns Hopkins University Center for Systems Science and Engineering](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv).
  The data provided by the NCDC site couldn't by extracted by web scraping because the NCDC Website was down for maintanance. 
  Budget data were also made available which was gotten from [Ustacky github respository](https://github.com/Ustacky-dev/Nigeria-COVID-19-Data-Analysis-Using-Python). After collecting all this data and performing proper data cleaning and analyses on it. 
  Certain conclusion we be taken as it was observed that the state which got the most hitt in Nigeria was Lagos, factors influencing it was because of  it very dense population density and it also been the economic capital of the nation with an out standing budget due to how big the economy of the state is . As a result of the pandemic , it was noticed that the state budget reduce in the second quarter of the second year of the hit of the virus, Which means the  pandemic affected economy negatively and also the livelyhood of the population. Aside from that it was notice that the maximum number of confirm lab cases which were recorded within a day was 6158 cases and it was recorded on the 2023-03-09.That was just to name a few, the are more conclusion we derived from the data after we properly analyse it . 

# Project Steps:

### Step 1:
   
   The various libraries which were been needed to carry out the analyses using python  on the data been provided were been imported. 
   This are the list of all the imported libraries which were been imported below. 
   * **import requests**
   * **import numpy as np**
   * **import urllib.request**
   * **import pandas as pd**
   * **import csv**
   * **from bs4 import BeautifulSoup**
   * **import seaborn as sns**
   * **sns.set_style("darkgrid")**
   * **import matplotlib.pyplot as plt**
   * **%matplotlib inline**
   * **plt.style.use('fivethirtyeight')**  
   * **import warnings**
   * **warnings.filterwarnings('ignore')**

### Step 2:
   
   After importing all the libraries which were been needed, The data were been extracted from the various data source which were been made available. The data was supposed to be extracted from the **NCDC** website through web scraping but because the website was down, it wasn't possible . so we use an alternative data which was provided in **Ustacky Github** repository. All the data source are listed below. 

   * [Ustacky Github](https://github.com/Ustacky-dev/Nigeria-COVID-19-Data-Analysis-Using-Python)
   * [Johns Hopkins University Center for Systems Science and Engineering](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)
   * Got more information for the [Real Domestic Gross Product Data](https://www.aljazeera.com/news/2020/11/21/nigeria-slips-into-recession-blamed-on-covid-19-and-oil-prices)


### Step 3:
   
   After getting all the data from the data source which were been made available , the next step involved was to clean all this data which we collected and make it ready to perform analyes on it. 

   * **The various data were been read into their corresponding data frames.**
   * **The data were been view to make sure the were been read properly**

# Data Transformation:

   Most of the data which was been read from all the data source where not clean. The data needed to be clean after been read from the data source before proper analyses could be carried out on each of them. Below is a list of steps which  were been used to clean the data and get it ready for analyses. 

   * **The data were observe using the head function to get few row of the data**
   * **Keys and values were been reorder for proper analyses using the pandas melt function**
   * **Once the data were available in a good format , Nigeria data was been extracted from it.**


# Analyses Of Data:

   Once all the data was been clean and ready to be analyse . Nigeria data was been extracted from each of the data which were made available. after extracting Nigeria data from each of the data frames after cleaning , more analyses was been carried out by extracting just the date and number of cases in each unique situation for all the data which were been made available. 


# Data Visualization: 
   
   After performing all the analyses on the data which were been presented, conclusion were be gotten from the data by visualizing each of the scenarios which was been required . 

   * **Using a barplot , The state with the most hit on covid lab confirm cases was known**
   * **Line plot was been plotted to see the relationship between the vunerability index and top 10 states**
   * **Regresion Was use to see the relationship between the number of covid cases and population density.**
   * **Using a barplot to sea how covid affected Nigeria REAL GDP**



# Insights:
  I had difficulties working with some seaborn plot . The regressionplot and also ploting all Real GGD values on the same graph 
  gave me some difficulties too. 


# Future Work:
  I am looking at working more on seaborn plot types. some of the plot available both in seaborn and matplotlib are still quite unfamiliar to me. 

# Stand Out Section
  More analyses and plot were been view in other to get detail information regarding the various states budget . It was been depicted 
  that **Cross River State** suffer allot in terms of how the state budget was been revise and reduce due to the pandemic impacts. 

  Also  from the standout section it was noticed that more patients were been admitted and hospitalize in FCT rather than Lagos state which had the most recorded covid confirmed lab cases.





















































































