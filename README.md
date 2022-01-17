# Crimes Vancouver : An Exploratory Data Analysis of the Types of Crimes in Vancouver Under the VPD's Jurisdiction


### Table of Contents
   - [Background](#background)
   - [Data Source and Legal Disclaimer](#data-source-and-legal-disclaimer)
   - [Visualizations](#visualizations)


### Background
I have lived in Vancouver for the majority of my adolescence, splitting the other half with Hong Kong. I have been recently wondering where I would settle down as graduation is approaching soon. One of the most important factors on my list when choosing a city asides from transportation, food and job opportunities is safety. In this analysis I will try to answer the following questions regarding safety in the city of Vancouver: 

1. What's the most prevalent type of crime?  
2. What's the most crime intensive community? 
3. Does the time of day affect the type of crime commited?

### Data Source and Legal Disclaimer
The dataset used for this analysis is from the Vancouver Police Department GeoDash Open Data found at 
https://geodash.vpd.ca/opendata/. The analysis below is purely for my own interest and should not be used for any business related decisions. As the dataset states, "Users are cautioned not to rely on the information provided to make decisions about the specific safety level of a specific location or area". For more information regarding the legality and types of crimes about the dataset check the legal disclaimer text and the VPD's crime incident description pdf. 

### Visualizations

The most prevalent type of crime in the city of Vancouver is theft, so make sure you don't have valuables in your vehicles, and make sure to lock your vehicles and bikes.

![typevsneighbor](https://user-images.githubusercontent.com/73871814/149721803-f41afd09-5eae-41b8-8b86-2e1d43cf6b18.PNG)


As the stacked barplot shows, the most crime intensive community is the Central Business District followed by the West End, Strathcona, and Mount Pleasant neighborhoods.

![stackbarplot](https://user-images.githubusercontent.com/73871814/149719063-d2dc5900-0f1a-4465-8350-a6190c8a620c.PNG)


And for a visual representation of the crime intensity by neighborhood.

![map2](https://user-images.githubusercontent.com/73871814/149721985-33a20e7d-dc69-4a54-a7b4-fccb77de8625.PNG)



Does the time of day affect the type of crime? Yes, we can see that offence against another individual and homicides occur more frequently during midnight-3am. However this statistic may be inaccurate as the VPD legality text states that times will not be provided, meaning that the time variable may just be a random parameter.

![typevstime](https://user-images.githubusercontent.com/73871814/149721926-88ce896d-15fb-4946-b679-3a94d6d478a3.PNG)

