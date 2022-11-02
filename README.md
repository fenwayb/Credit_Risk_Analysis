<h1 align=center> Credit Risk Analysis </h1>

<h2> Overview </h2>
<p> For this project we were tasked with testing different supervised machine learning models to figure out which one best predicts credit risk from our dataset </p>
<h2> Results </h2>
<p> The results of each ML results are as follows </p>

***
* Random Over Sampling
  * Balanced Accuracy - .65
  * Precision - high risk .01, low risk 1.0
  * Recall - high risk .62, low risk .67
* SMOTE
  * Balanced Accuracy - .63
  * Precision - high risk .01, low risk 1.0
  * Recall - high risk .62, low risk .63
* Clustered Centroids
  * Balanced Accuracy - .52
  * Precision - high risk .01, low risk 1.0
  * Recall -  high risk .57, low risk .47
* SMOTEEN
  * Balanced Accuracy - .65
  * Precision - high risk .01, low risk 1.0
  * Recall -high risk .74, low risk .56
* Balanced Random Forest
  * Balanced Accuracy - .79
  * Precision - high risk .04, low risk 1.0
  * Recall -  high risk .67, low risk .91
* Easy Ensemble
  * Balanced Accuracy - .93
  * Precision - high risk .07, low risk 1.0
  * Recall - high risk .91, low risk .94
  ***
<h2> Summary </h2>
<p> Based on this testing Easy Ensemble has the highest balanced accuracy as well as both high and low risk recall. The downside is it has the highest rate of false positives. However when it comes to credit risk we'd rather tag too many people as high risk than tag someone high risk as low risk resulting in potential large losses if/when they were to default </p>
