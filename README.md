# Tableau Projects
This repository contains Tableau dashboards and files related to a variety of topics. Each project and deliverable is explained in greater detail below.

## NBA.twbx
This file contains two dashboards, the first of which shows a NBA player's shooting efficiency based on their location on the floor and the second which provides a look at shooting efficiency across the season. Both dashboards can be filtered to the team level or for an indiviudal player and have the ability to drill deeper into the details of the selected team or players shooting efficiency by specifying additional parameters that include shot zone, shot type, quarter number, and amount of time remaining in the quarter. 

**Data Description and Feature Engineering**

The dataset used for this project was from the 2016-17 NBA season that includes shooting information for players such as where the shot was taken from on the court, shot zone, shot distance, and whether it was made or not. In addition to these metrics, the dataset included game information such as the date of the game and where the game was being played that was used to create a calculated field that determined whether the team was playing at home or away. Another feature that was engineered from the available data was total time remaining in the period to allow for users to filter the shot chart to a specific time frame within a quarter and provide more context on what type of shots the team or individual player are taking in that time interval.

**Project Process**

The first step of this project was to create worksheets that could be used in the dashboards. The worksheets that were created are a 'Home or Away' analysis that contains a bar chart of shooting efficiency based on what team and player is selected, a 'Player Photo' sheet that links a player's name to a game photo, and a 'Shooting Efficiency' sheet that overlays a shot chart on a basketball court based on the parameters specified for team or player. These worksheets and the features I engineered were used to create the two dashboards shown below, allowing for the visualizations to be dynamic based on player or team selections as well as the additional game data parameters that can be specified.

**Tableau Output**

![Image Alt text](/Tableau_Dashboard_1.png)
![Image Alt text](/Tableau_Dashboard_2.png)

## ForbesTop2000.twbx
The Tableau dashboard titled ForbesTop2000 is based on data from the Forbes Global 2000 which ranks the top public companies in the world. It contains information on company names, country of operation, sales, profits, assets, market value and industry. Calculated fields were created to determine whether a company was profitable, what their total expenses were, and a measure to effectively sort the visualizations in descending order of category selected. The types of graphs created to visualize this data in a variety of ways were a bullet graph (shown in the dashboard output), a treemap that illustrates the proportion of sales by country within each sector, and a ranked bar chart to compare market value to profits of each company in the dataset that were not included in the final dashboard.

**Tableau Output**

![Image Alt text](/Forbes_Dashboard.png)
