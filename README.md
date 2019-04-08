### FindMyCoffee - Project 1 
### Northwestern Data Science Bootcamp 

By Prathyusha Challa, Katelyn Burke, and Xuan He 

### Hypothesis:
If the coffee shop location has a higher population and more visibility then opening a coffee shop in that area will result in higher success and more business. 

### Overview of FindMyCoffee: 

After the global economic crisis that hit in 2008, business owners are trying to be smarter about where they open their next enterprise. Many enterprises today are using technologies like ‘GIS’ to determine where to build new outlets. In this project, we will be working with the Yelp API and Census data sets to determine where the next coffee shops should open in Chicago. It’s important for shop owners to be informed before choosing a location to open their business. Success of a business depends on several factors including the visibility (foot, car, and bike traffic) of the location, surrounding competitors, and consumer demographics. In this project, we work to understand the relationships between neighborhood population (by zip code) and the number of popular coffee shops in the neighborhood. We analyze the factors that promote business success in order to determine where future coffee shops should open. 

### Definitions: 
‘Popular’ Coffee Shop: More than 50 Yelp Reviews with an Average Rating of 3.5 stars or higher (out of 5 total stars possible)

‘Ready to Close’ Coffee Shop: Average Rating of 2 or fewer stars on Yelp (out of 5 total stars possible)

Chicago Neighborhood: based on Zip Code 

### Questions: 
Which neighborhood(s) in Chicago currently have the most coffee-shop competition? 

Does the population of an area in Chicago impact the success of a coffee shop?

How can coffee-shop owners predict where to open their next location/new shop in Chicago?

### Final integrated project: 

1. FindMyCoffee_DataExploration.ipynb	
"This is convereted notebool to --markdown format ipython nbconvert --to FORMAT notebook.ipnyb"
2. FindMyCoffee_Final.ipynb
"This file is a filter of top locations based on Visibility and popularity"
3. KB_US_Zip_Codes.csv
"Zip codes coordinating with latitudes and Longitudes data"
4. Population_by_Zip.csv
"Population by Zip codes data"
5. yelpapi.py
"Key for Yelp Fusion API"
6. gkey.py
 "Key for gmaps API"

### Data Sources: 

Yelp API Fusion API
Google Maps Platform 
“US Zip Codes from 2013 Government Data” -  CSV by Eric Hurst - Data from the US Census 
“US Census Population by Zip Code” - CSV by The Splitwise Blog - Data form the US Census



