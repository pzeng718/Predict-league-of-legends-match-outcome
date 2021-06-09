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

<h4>Final Table used for modeling is CMWRLP1_ChampStrength_ChampWR.csv</h4>


Last updated 06/08/2021 by Peter
