# Uber_And_Lyft_Car_Prices_Analysis


Overview
Over the past few years, ride sharing apps have been on the rise across many cities in the world. While this has happened, Uber and Lyft's ride prices are not constant like public transport. They are greatly affected by the demand and supply of rides at a given time. 

As a Data Scientist working to understand this market, you have been tasked to come up with a descriptive analysis report to help a Ride Sharing Startup coming into the space, understand the various patterns on how pricing works for the existing ride sharing company. 

Luckily, you were able to access some real-time data from Uber & Lyft's API and weather data from a Weather API conditions.
You build a custom application in Scala to query data at regular intervals and saved it to DynamoDB. The queried cab ride estimates are done after every 5 mins and weather data after every 1 hr. 

The cab ride data covers various types of cabs for Uber & Lyft and their price for the given location. Weather data contains weather attributes like temperature, rain, cloud, etc for all the locations taken into consideration.

Now that you have your data in the given dataset, write sql queries to perform descriptive analysis highlighting key insights that would be helpful in helping the startup develop a new product. 


Dataset
Weather Dataset URL = https://bit.ly/cabsweatherdata
Cabs Dataset URL = https://bit.ly/cabsdataset
