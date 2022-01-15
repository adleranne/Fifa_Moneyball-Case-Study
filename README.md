# Fifa_Moneyball-Case-Study
Case Study using the Fifa-Moneyball dataset

This is a case study as part of the Data Analytics Bootcamp.
The Fifa-Moneyball datafile is containing a lot of information about players, their demographics,
skills, ranking and their market value.

In this case study, I want to analyse which skills are the biggest drivers of the market value of a player.
In other words, if I am a football player, which skills I would need to focus on, to increase my market value.
Since the skills needed for certain positions in the game (e.g. forwards, midfielders, defenders and goalkeeper)
vary, the analysis will be split by position.

Note: this will not be a comprehensive analysis on how the market value can be derived or even predicted. It is solely
examining the influence of the soccer skills of the players given in the data file.
Not all data, that could influence the market value is available. For instance there is no information about previous
games/experience of the players or about possible other influencial factors that are not even related to the soccer game
itself (e.g. personality cult, popularity with sponsors etc.).

Steps taken in the analysis:
1. data cleaning (see data_cleaning python script)
--> done
2. exploration of the relevant data and descreptive statistics (see descriptive python script)
--> partially done
3. splitting the data set into the 4 major player positions forwards, midfielders, defenders and goalkeepers
--> done
5. for each player position: factor analysis of the skills to identify major skill sets and reduce data complexity
--> done for position forward, needs to be done for other three positions
6. for each player position: regression analysis of the skill sets on the market value to check their influence
--> done for position forward, needs to be done for other three positions
7. Presentation of results, comparing the results of the 4 different positions
--> tbd
