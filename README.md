# Superbowl_LVI_Prediction
Predicting the outcome of SuperbowLl LVI by taking into account Team performance, External Factors &amp; QB Performance

This project is divided into 4 key focus areas

1. Comparison Framework(File Name - Superbowl_Comparison_Framework)
   Since the Rams & Bengals have not played each other, we use KMeans clustering to determine Ram's performance against similar defensive teams to Benglas. This process is       repeated for the Bengals as well. The means of each cluster(Offensive & Defensive statistics) will be used as an input to the model that is trained on Offensive and Defensive statistics for the entire season
   
2. Team Statistics Model(File Name - Superbowl_Team_Statistics)
    We use data from the entire 2021-22 season to build a best predicting model, for the team score. This model will be used to predict based on the input generated from the comparison framework
    
3. QB Model(File Name - Stafford_vs_Burrow)
   This QB model is a standalon model, that is built on QB performance through the entire season. The predictions from this model and Team statistics model will be averaged to obtain a final score
   
4. Probabilistic Model based on External Factors(File Name - Superbowl_ExternalFactors)
   Based on betting, Home-Away advantage & Climatic conditions, we aim to predict a winner. Since the LA Rams are playing at home, this became an important aspect to track throughout the season
