Order of code

1. API_data_extraction_and_analysis
import pandas as pd
import requests
import json

The first part pulls data from the API. The required data is then accessed using dictionary methods, 
A new data frame is populated using these extracted values.

The difference between total count for gender for UK overall is calculated and stored.
The data is checked for seasonality and stationarity to prepare for modelling.
ARIMA model is used to train and test the data to produce a forecast for gender count difference for the UK.

Trends are plotted to show total count for gender in technology by region and by year (2016-2021).
Bar charts are plotted to show differences between regions and years.

Choropleth mapping is used to show the difference between genders and regions for the UK for 2021.

2. Occupation_Gender_Cleaned_Final (1)
import pandas as pd
import numpy as np
import datetime
import random

3. Occupation_gender_analysis

Project summary:

Gender Disparity in the Technology Industry: a deeper look at the UK situation
Team: Betty Abate, Kamile Sudziute, Monaliza Wohlers, Rachel Cunningham and Safia Elmi


Research suggests that between 10-30% of roles in technology roles are held by women, and even less in senior positions (Harvery Nash Tech Survey, 2021; Office for National Statistics, 2021). Therefore, we decided to investigate the disparity between the genders in the technological field while assessing if there is an increase of people working in said field and if the number of women also increased proportionately. Furthermore, it will examine if there is a disparity in the UK, whether there are any regional differences and at the gender of those in different occupations within the technology industry to assess whether differences exist depending on the occupation. It is also pertinent that the trends in gender disparity be analysed to assess if changes are taking place over time, rather than simply assessing the proportion of females in technology roles for a single year.

Our aim was to investigate gender disparity in the UK technology industry, across all UK nations, in the past 5 years. And using Python, matplotlib, pandas, plotly express, numpy, seaborn, statsmodels, sklear,  geojson as tools and libraries, and also using an API and successfully extracting data from it, we were able to set our objectives and answer all the questions we wanted to answer. Those question included a few such as if there is any disparity in between males and females in the UK and how wide is the gap withing certain roles in the industry.

Additionally, we were able to analyse this over a 5 year period and based on that we used predictive modelling to anticipate future trends that represent the participation and distribution of females and males in the UK technology industry.  

The purpose of this analysis is to inform organisations of where gaps still exist in terms of gender disparity within the technology industry and also to highlight if the gap is narrowing. It is also to identify how things have changed over time and therefore allow for predictions on future patterns in this trend.

Data was sourced from the Annual Population Survey via the ONS data hub. We also took gender pay data from national labour and workforce resources. To gather data on overall trends of males and females in the technology industry, we used the ONS API. We collated data for total count in all regions of the UK from 2016 - 2021.

Our conclusion was that looking at the trends in values for the difference in total males and females in the technology industry, and comparing year to year, the gap between genders is decreasing overall. Our data shows that the technology industry comprises a majority of males relative to females. The gap between males and females saw a small decrease in 2018, and then an upward trend from 2018-2021. This difference between genders increases in line with the overall numbers of males and females increasing in Technology.. This suggests that although the total difference is increasing, the change in the difference from year to year is decreasing.


Some challenges we faced was trying to find the time to meet and discuss the project when we were all available.  Also, extracting the API was also challenging due to it being a list of dictionaries, this required a few extra steps in data cleaning and preprocessing.



REFERENCES
We are tech women: https://wearetechwomen.com/campaigns/

https://www.ons.gov.uk/employmentandlabourmarket/peopleinwork/employmentandemployeetypes/datasets/employmentbyindustryemp13

https://www.hntechsurvey.com/
