# Player Scouting

<img src= "https://github.com/gotica462/Player_Scouting/blob/test/Images/Title.png">


## Overview of the Project

The year is 2017, and  your boss has just being named the new general manager of an English soccer team that has just being sold to a conglomerate worth billions of dollars. The good news is that they want to improve the team for next year competition, and they have asked the general manager to come up with a list of players that could improve the team right away. 
Since the team was lacking goals last season, we are going to focus on attacking players. We'll use pandas and machine supervised learning to create a table to show the results of our analysis, and we'll use Tableau to visualize those analyisis. 
Luckily for us Kaggle has provided us with a data set containing the information for the past 5 years of the most important leagues in Europe. 

### Reasons for Selecting the topic

Soccer is the most exciting sport in the world, and altough is lived with passion and emotions, we can also use data analytics to make informed decision about players. Nowadays every professional team use data analytics to improve their performance and having more information can only be benficial for us.

### Description of the source data
events.csv contains event data about each game. Text commentary was scraped from: bbc.com, espn.com and onefootball.com
ginf.csv - contains metadata and market odds about each game. odds were collected from oddsportal.com
dictionary.txt contains a dictionary with the textual description of each categorical variable coded with integers

(https://github.com/gotica462/Player_Scouting/blob/main/Resources/dictionary.txt)

For starting the project. We'll only need the column"Player", "Event-Type", and "Is_Goal" This will help us determine at first glance the efectivness of the striker.

![image](https://github.com/gotica462/Player_Scouting/blob/main/Images/Data%20Description.png) 


I selected a simple data since I am doing the project by myself and I want to keep it as simple as possible, and also the data is very detailes and it comes with a text file explaining it. 


### Question that we want to answer for our project

- Who are the most effective strikers in Europe?

- Can we use a machine supervised model to predict the efectivness of a striker?

- Could we look into other aspects of the player and compare them between them so we can have the most data possible to make an informed decision?




