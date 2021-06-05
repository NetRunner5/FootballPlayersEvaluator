# FootballPlayersEvaluator

## Requierements
This scrapper has been programmed using RStudio and RMarkdown in R. These are the packages used:  
* ggplot2
* dplyr
* GGally
* corrplot


## Contents 
The contents of the **Fifa.csv** from https://www.kaggle.com/artimous/complete-fifa-2017-player-dataset-global are as follows:

Variable | Description
------------------ | -------------------
Name | Player name
Nationality | Nationality of the player
National_Position | Position in the national team
National_Kit | Equipment number on the national team
Club | Name of the club
Club_Position | Position of play in the club
Club_Kit | Equipment number at the club
Club_Joining | Date he started at the club
Contract_Expire | Year end of the contract
Rating | Overall rating of the player, between 0 and 100
Height | Height
Weight | Weight
Preffered_Foot | Little favorite
Age | Age
Preffered_Position | Preferred position
Work_Rate | qualitative assessment in terms of attack-defense
Weak_foot | rating of 1 to 5 control and power of the leg not preferred
Skill_Moves | rating of 1 to 5 of the player's ability to move
Etc... | The other variables refer to player attributes.
  
  
The contents of the **FifaNET.csv** are as follows:

Variable | Description
------------------ | -------------------
Name | Player name
Nationality | Nationality of the player
National_Position | Position in the national team
National_Kit | Equipment number on the national team
Club | Name of the club
Club_Position | Position of play in the club
Club_Kit | Equipment number at the club
Club_Joining | Date he started at the club
Contract_Expire | Year end of the contract
Rating | Overall rating of the player, between 0 and 100
Height | Height
Weight | Weight
Preffered_Foot | Little favorite
Age | Age
Preffered_Position | Preferred position
Work_Rate | qualitative assessment in terms of attack-defense
Weak_foot | rating of 1 to 5 control and power of the leg not preferred
Skill_Moves | rating of 1 to 5 of the player's ability to move
Ball Control | Control of the ball
clasificacion | Classification of the player based on the rating
clasificacion2 | Simple version of classification of the player based on the rating
porter | If the player position is Goalkeeper
internacional | If player is playing in the national team

**PRA2.Rmd**: R file used for the analysis
**PRA2.html**: Html of the analysis report
**PRA2.html**: Pdf of the analysis report

## Team members
Junjie Zhu and Antoni Sanchez Teruel

## License
The license chosen for the publication of this data set has been **MIT License**
