#UCI Stats 170A/B Group 14 Predict-league-of-legends-match-outcome

Jerry Wrangled the Riot API data and run his files in this order:

  RiotApiTest.ipynb - Create Data Files from Riot's API. Redacted Riot API Key, takes ~6-8 hours to run. 
  
  JoinAllTables.ipynb - Joins Riot Data Files on matches csv to create CMWRLP1000.csv that Peter and Junyi also join on
  
  Visualization.ipynb - Creates the graphs used in presentations and report.
  
  Modeling.ipynb - Sklearn's logisitic model on final table 
  
  glmTest.Rmd - R's logisitic model using glm
  
  
 Jerry Data Files:
 
  playersV5.csv
  
  matchesV8.csv
  
  masteryTableV4.csv
  
  CMWRLP1000.csv
 
 
Final Table used for modeling is CMWRLP1_ChampStrength_ChampWR.csv


Last updated 06/07/2021 by Jerry
