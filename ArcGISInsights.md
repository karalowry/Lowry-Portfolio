[Link Back to Advanced GIS Portfolio](AdvancedGISAssignments.md)

# Assignment: Using ArcGIS Insights to Investigate the DEA's Pain Pill Database

For this assignment, I utilized ArcGIS Insights to conduct an analysis on the DEA's pain pill database. ArcGIS Insights is a data analytics workbench that offers spatial and nonspatial analysis capabilities to explore data and deliver powerful results. It is available as a desktop application or online, and primarily works with “drag and drop” functionality. It is much cheaper and more intuitive than ArcGIS Pro; therefore, it may be a great option for small organizations.


## ArcGIS Insights Project
<iframe src="https://insights.arcgis.com/#/embed/2ad14144cf4046f8ab1bac27aa3ddf18" width="100%" height="100%" frameborder="0"></iframe>

To start, I downloaded the data for Mingo County in West Virginia from the DEA's pain pill database. After importing the data into ArcGIS Insights, I geocoded the address data that was available for the distributors and buyers. I then used that data to create a link map between the buyers and distributors. ArcGIS Insights automatically generated a link map from the data, which is quite helpful if you have data but do not know the best way to display it. I changed the map to reflect the sum of pill dosage units. To make the map more readable, I select a basemap to complement the data and add county boundaries to be able to more clearly visualize Mingo County.  

Next, I used the "Enrich Data" function to calculate how many people live in a five miles radius from each buyer. 2010 population data from the U.S. Census Bureau was utiized to create two tables that show the population within 5 miles of the buyer and the sum of dosage units by buyer. These two tables allow for a comparison between how many dosages of pain pills are in the area compared to the population, which is quite alarming.

## Assignment Reflections

I really enjoy how intuitive ArcGIS Insights is. I think for someone who does not have a lot of experience with analyzing large amounts of data, having the actions based on what questions you are trying to answer is really helpful. I also think it is really helpful if someone does not have a lot of experience with map making that the program will generate a pretty useful map, such as the link map, based on the data you are utilizing. This is not something that ArcGIS Pro does, and so it can be much more complicated to get what you want from the data on ArcGIS Pro than on Insights. On the other hand, it can be a downside if you know what type of map you want to make, but Insights makes something else.

For this particular exercise, I thought the link map was useful and not something I remember learning how to make on ArcGIS Pro. I think the Enrich Data feature is also very useful and interesting for spatial analysis. Being able to easily utilize another dataset and compare that to data you have been working with makes the analysis easy to do. Unfortunately, I could not get Enrich Data to work properly for me in this tutorial. Instead of creating a separate table of results, it just added the 2010 Population Data that we brought in to the existing data table. My population data did not match what was on the assignment, but I am not sure why that would be. If it had properly worked, I think that analysis is very telling and an interesting way of looking at the data. Comparing the doses of pain pills to the population within 5 miles of the buyer really offers a new view of how pervasive the opioid epidemic is. 
