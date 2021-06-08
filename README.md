# NbaModel

## Welcome to my first project!

As an aspiring data analyst and an Nba enthusiast, I created an multivariate logistic regressin model that predicts the outcome (Win/Loss) of nba games. It was a fairly challenging task since there are certain random factors that influences the outcome of the game. I achieved a prediction accuracy of 60-70% depending on the games I try to predict. It is important to keep in mind that my primary motivation for this project was not to create a model for Nba betters to take their game to the next level, but rather to put my coding and statistical knowledge on display. 

The excel file that includes the data from all the regular season games from 2020-2021 season was obtained from bigballdata.com through a subscription. 

#### The model

After preprocessing the data, I tested for multiple features such as; 

-the venue meaning whether the team is playing at home or away  
-the win streak of the team  
-the win percentage of the team from beginning of the season up until the game being played  
-the win percentage of the opponent team from beginning of the season up until the game being played  
-the last 7 game win percentage moving average of the team  
-the last 7 game win percentage moving average of the opponent team  
-the last 15 game win percentage moving average of the team  
-the last 15 game win percentage moving average of the opponent team  
-whether the impact player(s) such as LeBron James or Luka Doncic are playing for that game (1 for playing, O for not playing)  
-wheter the impact player(s) are playing for the opponent team  

After running a logistic regression, I obtained the significance levels for each variable. The most challenging part was while some variables were significant (having a p-value less than 0.05) for some teams, it was not as significant enough for others. Some teams did not even have a single variable that was significant enough on the outcome. However, some variables stood out compared the other ones across the board. The ones that were significant for most teams were;

-the win percentage of the team from beginning of the season up until the game being played  
-the win percentage of the opponent team from beginning of the season up until the game being played  
-the last 7 game win percentage moving average of the opponent team  
-the impact player  
-the opponent's impact player
