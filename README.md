#UCI Stats 170A/B Group 14 Predict-league-of-legends-match-outcome

Jerry Wrangled the Riot API data and run his files in this order:
  \tRiotApiTest.ipynb - Create Data Files from Riot's API. Redacted Riot API Key, takes ~6-8 hours to run. 
  \tJoinAllTables.ipynb - Joins Riot Data Files on matches csv to create CMWRLP1000.csv that Peter and Junyi also join on
  \tVisualization.ipynb - Creates the graphs used in presentations and report.
  \tModeling.ipynb - Sklearn's logisitic model on final table 
  \tglmTest.Rmd - R's logisitic model using glm
  
  
Jerry Data Files:
  \tplayersV5.csv
  \tmatchesV8.csv
  \tmasteryTableV4.csv
  \tCMWRLP1000.csv
 
 
Final Table used for modeling is CMWRLP1_ChampStrength_ChampWR.csv


Last updated 06/07/2021 by Jerry
