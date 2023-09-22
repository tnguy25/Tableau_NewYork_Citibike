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
<img width="814" alt="image" src="https://github.com/tnguy25/tableau-challenge/assets/125770693/041bd965-0829-4cfe-b705-7011b7078ed8">


