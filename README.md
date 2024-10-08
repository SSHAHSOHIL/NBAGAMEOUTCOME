

# NBA Game Outcome Model


## The purpose of the NBA Game Outcome Model is to be able to build and train a model using TimeSeriesSplit and XGBoost to be able to predict game outcomes in the future. The model predictions would then be compared to future betting odds to evaluate possible profitability.

This project utilizes Python, Pandas, and advanced machine learning techniques to create the most optimized model that can be used on future data. To analyze performance trends and create the model itself, the project involved efficiently web scraping detailed team and player data for the entire 2023-2024 NBA season. Then, rolling averages for each of the teams' stats were implemented to see how teams were playing in previous games as well as an ELO system to evaluate each of the teams based on overall performance. 

## Creating CSV Branch

This branch contains the code that was used to web scrape the NBA 2023-2024 season data off the interent through Selenium. It also contains code that edits the season csv file creating factors like ELO, rolling averages, and form to increase the accuracy score through value predictors. 

## Model Testing

This branch contains the code that uses specific machine learning techniques like XGboost, TimeSeriesSplit, and GridSearchCV to optimize the model for future predictions. 

## IN PROGRESS

* Creating a team averaged PER (player efficiency rating) based on the weighted average of all the PERs of all the players on each team.
* Having this PER be updated by game to game to create yet another predictor for the model in the future.
* Comparing our model on betting lines to see if the model can predict favorable outcomes and create a profit.


