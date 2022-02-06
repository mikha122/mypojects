This file depicts the Football Project.
This project was an attempt to predict future matches between a home and an away team based on previous matches between those teams.
This was done using a neural network and then 2 SGDClassifiers which predict the score and then a loop would check whether the home team or the away team is the winner.


The original data used for this project and manipulated in the Football_project.ipynb file doesn't exist any more and would have to be downloaded from Kaggle to repeat my changes

The data used for the Football_project_NN, Football_project_ML and Football_project_new files is stored as all_merged.csv

Football_project_NN was an attempt to use a Neural Network with 3 deep layers in order to predict football matches.

Football_project_ML was an attempt to use 2 SGDClassifiers to predict the amount of goals scored by different teams. 
The accuracy may vary with your run, but mine was 44% accuracy for the home team after using GridSearch and the away team reached over 50%.
The total accuracy was better, having 59% accuracy on predicting correctly whether the home team would win/lose/draw a match.

The Football_project_new file creates a new example for the data. First, it takes the match that you want to play out, then searches the dataset for previous matches between the 2 teams. Then, takes the averages for the statistics in the dataset and produces a new example. You can then export the example and use it in the ML file to predict the score between the teams.
