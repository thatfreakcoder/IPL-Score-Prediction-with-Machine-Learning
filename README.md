# IPL Score Prediction with Machine Learning
Open in [Google Colab](https://colab.research.google.com/github/thatfreakcoder/IPL-Score-Prediction-with-Machine-Learning/blob/master/IPL_Prediction_Model_Training.ipynb#scrollTo=9AjtN9yMEmT0)</br>
Predict the First Inning score of an Indian Premier League (IPL) Match using machine learning algorithms.</br>
## Dataset
The dataset can be downloaded from [Kaggle here](https://www.kaggle.com/yuvrajdagur/ipl-dataset-season-2008-to-2017).
#### Dataset Description
• mid: Unique match id.

• date: Date on which the match was played.

• venue: Stadium where match was played.

• battingteam: Batting team name.

• bowlingteam: Bowling team name.

• batsman: Batsman who faced that particular ball.

• bowler: Bowler who bowled that particular ball.

• runs: Runs scored by team till that point of instance.

• wickets: Number of Wickets fallen of the team till that point of instance.

• overs: Number of Overs bowled till that point of instance.

• runslast5: Runs scored in previous 5 overs.

• wicketslast5: Number of Wickets that fell in previous 5 overs.

• striker: max(runs scored by striker, runs scored by non-striker).

• non-striker: min(runs scored by striker, runs scored by non-striker).

• total: Total runs scored by batting team at the end of first innings.

## Algorithms Used
- *Decision Tree Regressor*
- *Linear Regression*
- *Random Forest Regression*
- *Lasso Regression*
- *Support Vector Machine Regression*
- *Neural Network Regression*

## Webapp Deployment
The final model is deployed [here](https://ipl-predict-score.herokuapp.com)</br>
Github Code of Webapp can be found [here](https://github.com/thatfreakcoder/ipl-predict-score).
