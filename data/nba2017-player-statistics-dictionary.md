# *Data Dictionary*
  
  
  
  
+ What is the data about?
    + The data is about NBA players and their in game performance statistics such as total points scored as well as facts about them, such as their salary, years of experience, and position.

+ How many rows/columns?
    + The data contains 441 rows and 24 columns.

+ What are the column labels?
    + In order (from left to right) : Player, Team, Position, Experience, Salary, Rank, Age, GP, GS, MIN, FGM, FGA, Points3, Points3_atts, Points2, Points2_atts, FTM, FTA,	OREB,	DREB,	AST, STL, BLK, TO
    
+ Abbreviations in column labels:
    + GP - games played during regular season
    + GS - games started	
    + MIN	- minutes played during regular season
    + FGM	- field goals made
    + FGA	- field goals attempts
    + Points3	- 3-point field goals
    + Points3_atts	3-point field goal attempts
    + Points2	- 2-point field goals
    + Points2_atts - 2-point field goal attempts
    + FTM	- free throws made
    + FTA	- free throws attempted
    + OREB - offensive rebounds
    + DREB - defensive rebounds 	
    + AST	- assists
    + STL	- steals
    + BLK	- blocks
    + TO - turnovers

+ Other unabbreviated labels
    + Player - first and last names of player
    + Team - 3-letter team abbreviation
    + Position - player's position
    + Experience - years of experience in NBA (a value of R means rookie)
    + Salary - player salary in dollars
    + Rank - rank of player in his team
    + Age - age of player at the start of February 1st of that season
    
+ Units of measurement (for applicable variables)
    + Salary - dollars
    + Experience - years
    + MIN - minutes
    + The rest of the variables' units are just units

+ How are missing values codified?
    + For players with missing experience values (i.e. no experience values), they are coded with `R`

Source : https://www.basketball-reference.com  
Sample link for a given specific team: https://www.basketball-reference.com/teams/GSW/2017.html (for GSW, for example)
    