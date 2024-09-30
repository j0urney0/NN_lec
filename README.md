# Applications and Practice in Neural Networks (2024-2)

## I. Project title
### ⚽Premier League Matches Prediction Modeling

---
## II. Project introduction

### 📌Objective
- Predicting wins with match information
    - Developing a model to predict the outcome of each match based on Premier League match data
        - Predicting the outcome of a match or score difference
        - Identify key variables that affect a match or team's performance
- Leverage for strategy
    - Create a betting strategy and analyze your returns
    - Enables strategy in Fantasy (Premier) League
    - Can be used in real-world match strategy

### 💡Motivation
- Increase the commercial value of accurate match prediction
    - Maximize your betting returns
- Sports games like Fantasy League
    - The growing importance of using real-world game data to make decisions
- Contribute to the evolution of sports analytics by leveraging real-world game data

---
## III. Dataset description
*Raw Data: Dataset of Premier League Matches from season 2020 to 2024*\
*Source: https://www.kaggle.com/datasets/mhmdkardosha/premier-league-matches/data*


### 📂Feature description
- date : the date of the game
- time : the time of the game
- comp : the competition of the game
- round : the round of the game
- day : the day of the week of the game
- venue : the venue of the game
- gf : the goals for the home team
- ga : the goals for the away team
- opponent: the opponent of the home team
- xg : the expected goals for the home team
- xga : the expected goals for the away team
- poss : the possession of the home team
- captain : the captain of the home team
- formation : the formation of the home team
- referee : the referee of the game
- sh : the shots of the home team
- sot : the shots on target of the home team
- dist : the average distance of the shots of the home team
- fk : the free kicks of the home team
- pk : the penalty kicks of the home team
- pka : the penalty kicks attempted of the home team
- season : the season year of the match
- team: the home team
- result : the result of the game (*🎯target*)

### 📎Details
- Data with pre-match information about the match, progress, results, and more.
    - This allows for predictability of future matches, not just wins, but a range of outcomes.

---
*baseline code source: https://www.kaggle.com/code/mhmdkardosha/premier-league-matches-manipulation-and-modeling#Neural-Network-model/*
