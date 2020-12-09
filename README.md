# MLBPredictor

# TODO:
 ***** Clean Data to get relavent features (starting with 2020 dataset that is here)


Mlb Betting Plan:
Problem statement: 
Make money betting on the outcomes of MLB games

Desired Feature Set
- Starting Pitcher (ERA, WHIP, WAR, ....)
- Starting Lineup (OBP, OPS, WAR, BB, HR, RBI, Defense stats etc..)
- Winning + Losing Team


Data Access
	- Need Vegas / Sportsbooks lines 
	- Need Game by Game winners, starting pitchers (Retrosheet)
	- Individual Player stats


Data Manipulation



Training
- Train on total data (lets say 2015-2020) using features that we will select (TBD)
- 


Algorithms / Ideas to seperate
- We want our algorithm to output a win probability for each team given data for each team starting lineup
	- Note: Input values do not have to be current stats of given players (We can determine later)
- The first month of each season is more difficult to predict (less certainty)
	- Use each players stats bucketed BY PAST MONTH
- Players / teams have hot + cold streaks
	- use more recent data / stats as indicators when inputting values into our final model




Models:
- RandomForest / Tree
- AdaBoost
- SVM
- Nueral Net Maybe?





# (Possibly) Useful Links
https://baseballsavant.mlb.com/leaderboard/statcast?type=batter&year=2020&position=&team=&min=50
