# Citi Bike Analysis with Tableau
![image](https://github.com/tnguy25/tableau-challenge/assets/125770693/8e31f583-7e74-44c2-8145-35a2dfb4eb42)

#Instructions
Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.

The following are questions you may wish to answer. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!

How many trips have been recorded in total during the chosen period?

By what percentage has total ridership grown?

How have the proportions of short-term customers and annual subscribers changed?

What are the peak hours when bikes are used during the summer months?

What are the peak hours when bikes are used during the winter months?

Today, what are the top 10 stations in the city for starting a journey? Based on data, why do you hypothesize these are the top locations?

Today, what are the top 10 stations in the city for ending a journey? Based on data, why?

Today, what are the bottom 10 stations in the city for starting a journey? Based on data, why?

Today, what are the bottom 10 stations in the city for ending a journey? Based on data, why?

How does the average trip duration change by the type of user? (This may be under "User Type" or "member_casual" depending on the period the data is from).

What is the average distance in miles for a bike trip?

Which bikes (by ID) are most likely due for repair or inspection in the timespan?

How variable is the utilization by bike ID?

Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.

Create one of the following visualizations for city officials:

Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.

Create your final presentation:

Create a Tableau story that brings together the visualizations, requested maps, and dashboards.

Ensure your presentation is professional, logical, and visually appealing.

#Data Sources:
The initial stage of the project involved acquiring all the monthly CSV files, covering the period from January 2023 to July 2023, from the Citi Bike Data webpage and organizing them in a designated folder named "data". The data used in this analysis specifically pertains to the New York citi bike.

Subsequently, I established a Jupyter Notebook file, named "citibike.ipynb", to systematically clean and combine all the monthly CSV files into a single CSV file, in preparation for importing into Tableau.

The following is a comprehensive overview of the data cleansing process:
January
<img width="814" alt="image" src="https://github.com/tnguy25/tableau-challenge/assets/125770693/041bd965-0829-4cfe-b705-7011b7078ed8">

February
<img width="718" alt="image" src="https://github.com/tnguy25/tableau-challenge/assets/125770693/5c0cc99d-8416-4c53-a0f2-1ecbaf4ac2f9">

March
<img width="689" alt="image" src="https://github.com/tnguy25/tableau-challenge/assets/125770693/1a89c0d3-d9eb-44f0-a882-2f9b43003b0f">

April
<img width="701" alt="image" src="https://github.com/tnguy25/tableau-challenge/assets/125770693/c282c6f6-2b27-4c17-bc07-c258df5c8c5e">

May
<img width="706" alt="image" src="https://github.com/tnguy25/tableau-challenge/assets/125770693/758eb34e-8756-4dad-a032-6aef9e3fa7f5">

June
<img width="688" alt="image" src="https://github.com/tnguy25/tableau-challenge/assets/125770693/258cd753-1dbf-4281-b61f-0c2d7d3148ae">

July
<img width="688" alt="image" src="https://github.com/tnguy25/tableau-challenge/assets/125770693/fe4f8bdb-3fa7-4139-aad6-def91b77d13e">

All combine together
<img width="742" alt="image" src="https://github.com/tnguy25/tableau-challenge/assets/125770693/776be7b0-20bf-4046-b516-ea112e1cff01">

+Results Dashborad:
Dashboard 1 presented the top and bottom 10 of start and ended station by ridership which determined the high and low volume of station based on the station name and the rider id.
<img width="1192" alt="image" src="https://github.com/tnguy25/tableau-challenge/assets/125770693/22b8b9c3-ac3b-4de7-a2ce-6a51e86fb4dd">

Dashboard 2 focused on the analysis of the average trips duration collarating with the rideable type, also the value was counted by ascending order with different colour to illustrate three types of bike such as classic_bike, docked_bike, electic_bike. Additionally, the heat map generated by ridership and month, hour; also the light to dark colour presented base on the minimum to maximum values.
<img width="704" alt="image" src="https://github.com/tnguy25/tableau-challenge/assets/125770693/69aae327-2eb4-49bd-800e-bd0d38269430">

Dashboard 3 evaluated the volume of rider based on seasonal (spring and summer); the sesonal counted on monthly (January to April was spring) and (May to July was summer). 
<img width="535" alt="image" src="https://github.com/tnguy25/tableau-challenge/assets/125770693/92d11549-2fff-4ea3-abd7-5f9fbb6bd5b9">

Dashboard 4 showed the value of rider id which counted by monthly. 
<img width="679" alt="image" src="https://github.com/tnguy25/tableau-challenge/assets/125770693/7012ad8f-d2db-4230-8eb8-053fda80d4ac">

#Conclution
This tableau analysis provides a comprehensive overview of the trends and patterns in Citibike usage over a specified time period. This analysis illustrated the citibike services in New York in 2023; also the Tableau story that brings together the visualizations and dashboards detail for anyone interested in understanding the usage of Citibike and exploring the data behind this popular bike-sharing service.




