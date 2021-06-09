<h2>UCI Stats 170A/B Group 14 Predict-league-of-legends-match-outcome</h2>

<h5>Jerry Wrangled the Riot API data and run his files in this order:</h5>
<ol>

  <li><b>RiotApiTest.ipynb</b> - Create Data Files from Riot's API. Redacted Riot API Key, takes ~6-8 hours to run. </li>
  
  <li><b>JoinAllTables.ipynb</b> - Joins Riot Data Files on matches csv to create CMWRLP1000.csv that Peter and Junyi also join on</li>
  
  <li><b>Visualization.ipynb</b> - Creates the graphs used in presentations and report.</li>
  
  <li><b>Modeling.ipynb</b> - Sklearn's logisitic model on final table </li>
  
  <li><b>glmTest.Rmd</b> - R's logisitic model using glm</li>
</ol>
<h5>Jerry Data Files:</h5>

  playersV5.csv,  matchesV8.csv,  masteryTableV4.csv,  CMWRLP1000.csv

<h5>Peter Wrangled the Reddit API data and run his files in this order:</h5>
<ol>
  <li><b>redditPullPost.ipynb</b> - Obtain the data from Reddit API, wrangle the data into useful information (scores) we can use. Getting the data from Reddit takes less than 10 minutes, the whole notebook takes less than 20 minutes to run. </li>
  
  <li><b>randomForestModelBuilding</b> - Build and train the model. This takes about 4 minutes to run.</li>
</ol>
  
<h5>Peter Data Files:</h5>
  comments.csv,  posts.csv,  champion_strength.csv,  champions.txt

<h5>Junyi Wrangled the OP.GG data and run his files in this order:</h5>
<ol>
  <li><b>parse_top/mid/bottom/jg/sup.ipynb</b> - Parse raw data from OP.GG based on five champion roles.</li>
  
  <li><b>combineV2.ipynb</b> - combine five parsed data into one. Then add a column of corresponding maximum win rate a champion can have to our giant table.</li>
  
  <li><b>correlation_exp.ipynb</b> - experiment with correlation matrix heatmap.</li>
  
  <li><b>AdaBoost.ipynb</b> - Apply our AdaBoosting Classifier from sklearn and cross-validation.</li>
</ol>
<h5>Junyi Data Files:</h5>
  all_features_parsed_bottom.csv, all_features_parsed_mid.csv, all_features_parsed_sup.csv, all_features_parsed_top.csv. all_features_parsed_jg.csv
  all_features_parsed_concat.csv.


<h4>Final Table used for modeling is CMWRLP1_ChampStrength_ChampWR.csv</h4>


Last updated 06/08/2021 by Peter
