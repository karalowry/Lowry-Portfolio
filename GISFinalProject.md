# Assignment: Final Project

## Link to Final Project

[Using a Suitability Model for Improved Campaigning](https://arcg.is/1iSOvW2)

## Project Summary

*Client and Problem*
	The client is the Democratic Party of Alleghney County. The party is in need of assistance in prioritizing where to focus canvassing efforts throughout the County. The example campaign being used is a campaign that has a limited number of volunteers; therefore, they need to know which areas to make sure volunteers are sent in order to reach the most important and fruitful voters, while also saving their volunteers’ time and energy. The example candidate is a Black, middle-class woman with a progressive platform.

*Process and Final Product*
	The final product will be a suitability model created in ArcGIS Pro with sites located throughout Allegheny County where the campaign should focus its canvassing efforts. The sites will be based on multiple criteria based on reaching voters most likely to vote for the candidate and ease of canvassing for volunteers. The final project will include this specific campaign’s suitability model as an example and an explanation of how to change the model to work for other Democratic candidates’ needs. The final product will also include a little information about each site from the example suitability model.

To generate a suitability model, there are some basic steps:

- Define the Problem: The problem has been defined as the campaign not having enough volunteer staff to canvass every zip code in Allegheny County. This problem leds to a measurable goal of the suitability analysis of identifying top-priority areas to focus canvassing efforts.

- Identify the Criteria: The criteria that has been preliminarily identified to ensure the best use of the volunteers time and energy are: slope of area (for ease of walking), Black population in area (research shows Black voters as part of the candidate’s “base”), population with at least a Bachelor’s degree (research shows these voters as part of the candidate’s “base”), and population 20-49 (research shows these voters as part of the candidate’s “base”). This criteria will be used to find the best areas for the campaign to spend time canvassing in order to secure the most votes.

- Derive the Criteria: Most of the criteria will have data already collected; however, some criteria may need to be derived from other data.

- Transform Criteria Values: The criteria is measured on different scales; therefore, it must be transformed to create a common scale that can be used to create the suitability model. ArcGIS Pro will be used to transform the criteria; however, it will require some research and thought into how the data should be transformed.

- Weight and Combine Criteria: Some of the criteria will be important than others. In order to factor that into the suitability model, criteria will be weighted differently. It will be necessary to research and discuss with the campaign team which criteria should be weighted more heavily than others.

- Locate Sites: ArcGIS Pro will utilize the suitabiliy model created from the criteria to locate the best sites to spend time canvassing. This is an iterative process and it may take multiple attempts at creating the suitability model to receive locations that work best for the campaign.

- Analyze the Results: In order to ensure the sites are the best for the campaign, the results will be compared to each of the criteria. This analysis will ensure that the suitability model is producing the best locations for the campaign to focus on.

- Summarize and Present Work: The suitability model and location sites will be presented to the campaign staff for review and questions, and a guide on how to make adjustments if necessary will be prepared.

## Reflections

First, I greatly underestimated how long data cleaning and gathering would take. I had forgotten from the first GIS class how tedious it can be to clean data, upload it to ArcGIS Pro, calculate fields, and join to other features. I will remember in the future to budget more time for data cleaning and gathering, as that was the majority of my project. Second, I underestimated how long it would take to write-up the final StoryMap. Part of that was that StoryMaps was loading quite slowly, but it also took a lot of time to upload the maps to the web and format them on ArcGIS Online. I will also remember to budget more time for putting the project all together in the future as this is very important and time-consuming.

To reflect on the project itself, I was disappointed that I could not get the Locate function to work for the suitability map. I do not know why it would not work. It was loading; however, it was moving extremely slow, with it going up by 1% after two hours of loading. I am not sure if my raster cell size was too small or the area was too big, but it was frustrating trying to get it to work. I think that the suitability maps still offer some insight, but not as precisely as it would with the locate function.
