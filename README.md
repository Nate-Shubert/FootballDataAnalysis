# Football Data Analysis Portfolio

The purpose of this repository is to display data analysis projects I've made for potential positions as an analyist in the National Football League.

This repository contains the following projects:

1. Defensive Tendency Breakdown - 
I was lucky enough to recieve a csv file from an old position coach of mine that contained raw data from defensive film breakdown they performed on an upcoming opponent. I wrote a few functions in Python to analyze the game data and breakdown defensive tendencies for Coverage, Blitz, and Defensive Fronts. From this data I concluded that the opposing team was a heavy cover 3 team that brought pressure the most on first down, at a 10% rate. They also played with mostly 3 down linemen, but showed a bear front on 16% of plays. See the link below for all the data and breakdown. 

https://docs.google.com/spreadsheets/d/1lETUf_PasgCZeI4Lfm5_czovfRyKT7KTKWFH0-H0R4s/edit?usp=sharing

2. Win Prediction Model and Probability - 
This project took inspiration from the books "The Hidden Game of Football" by Bob Carroll and "The New Bill James Historical Baseball Abstract" by Bill James. I started this project by using the Beautiful Soup Python package to web scrape 19 years of NFL Regular Season Team Data. From this data, I used pythagorean thoerem, linear regression modeling, and multiple methods of distribution to create models for predicting win percentage over the course of an NFL season. In the end, I was able to use points for and against to predict winning percentage up to 95.5% accuracy and then use 8 other variables to expand on that model to predict points for and points against with 95% accuracy and winning percentage with 91% accuracy.

3. Oline_Analysis - 
In this project, I took multiple [Kaggle datasets](https://www.kaggle.com/competitions/nfl-big-data-bowl-2023/data) related to NFL offensive line players data. The ultimiate goal was to find a way to isolate EPA contributions by individual linemen. I used the basic EPA model introduced by Bob Carroll for this. The final product is an interesting function that breakdown a linemens performance into 4 buckets in one play - Allowing a Sack, QB Hit, QB Hurry, or Clean Pocket. Having determined an average EPA value for these events, I determined the overall EPA value of each offensive linemen in the dataset.

4. Tight End YAC EPA Per Target Analysis - 
This was an exercise to display my competency with R progamming and display a breakdown of the YAC ability for all qualifying 2021 tight ends. Using the NFLFastR R package, I was able to find data regarding tight ends during the 2021 season. As seen in the code, I found the YAC EPA per Target of every tight end in this dataset, and trimmed it to include only tight ends with 50 or more opportunities. I then plotted out every player in that new set to visualize who was performed above average in 2021 when it came to tight ends after the catch.

I have programing certifications saved on my [wiki](https://github.com/Nate-Shubert/FootballDataAnalysis/wiki).
If you have any comments or questions, please reach out at nate.shubert@gmail.com. 
