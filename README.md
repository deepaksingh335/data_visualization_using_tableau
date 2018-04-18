# Flight data visualization using Tableau 

## Author : Deepak Singh 

## Date : 04/17/2018 

## Link to my Tableau Workbook 
https://public.tableau.com/profile/deepak.singh1476#!/vizhome/Flights_Delay_Causes_2008_V2/Story

## Summary 

This dataset is obtained from the RITA website which contains information about flight delays and performance. The dataset I used is for 2008. I used two additional datasets carrier.csv and airports.csv. The datasets can be found in the following website:
http://stat-computing.org/dataexpo/2009/the-data.html

The dataset contained approximately 7 million observations along with 29 columns. I cleaned the data using python in jupyter notebook. After cleaning the data, I joined the data with carrier.csv – to get the carrier names and the resultant dataset I joined with airports.csv to get the city and state information for the airport code.

I have created the visualizations in Tableau that answer the following questions:

1.	What are the busiest states and cities in those states where the flights originate?

2.	What are the cities with most delays when all the airports are considered and what are the causes that contribute for these delays?

3.	What are the carriers that cause the most average delays when all the flights are considered?

4.	What is the overall Monthly trend for the several types of delays? Is there any correlation among the causes for delays?
