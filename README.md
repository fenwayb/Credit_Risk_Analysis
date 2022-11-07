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
***
  ![ROS_BAS](https://user-images.githubusercontent.com/106105597/200404631-7b95ed77-58ec-439f-8312-e76875991129.png)
  ![ROS_class](https://user-images.githubusercontent.com/106105597/200404817-ef4b4e67-f3c8-4f54-969b-b81fdf862211.png)

***
* SMOTE
  * Balanced Accuracy - .63
  * Precision - high risk .01, low risk 1.0
  * Recall - high risk .62, low risk .63
***
![SMOTE_BAS](https://user-images.githubusercontent.com/106105597/200404893-7df26399-72d4-42f9-b675-2cbc5d054390.png)
![SMOTE_class](https://user-images.githubusercontent.com/106105597/200404949-01a79c4c-6eca-4485-97a9-2c92194d24c1.png)

***
* Clustered Centroids
  * Balanced Accuracy - .52
  * Precision - high risk .01, low risk 1.0
  * Recall -  high risk .57, low risk .47
***
![cc_BAS](https://user-images.githubusercontent.com/106105597/200405014-c8d83bac-bfa0-41ec-9762-2396766bc968.png)
![cc_class](https://user-images.githubusercontent.com/106105597/200405075-b2effd0e-17ba-40a6-af13-132d9ec0ac03.png)

***
* SMOTEEN
  * Balanced Accuracy - .65
  * Precision - high risk .01, low risk 1.0
  * Recall -high risk .74, low risk .56
***
![SMOTEEN_BAS](https://user-images.githubusercontent.com/106105597/200405124-7c71017b-0709-47d8-9a73-7037b394acd5.png)
![SMOTEEN_class](https://user-images.githubusercontent.com/106105597/200405173-c1f3e473-7628-43e3-909b-8d2b34d8b8c7.png)

***
* Balanced Random Forest
  * Balanced Accuracy - .79
  * Precision - high risk .04, low risk 1.0
  * Recall -  high risk .67, low risk .91
***
![BRF_BAS](https://user-images.githubusercontent.com/106105597/200405320-73aa2d2e-8423-4df6-a839-6fb3e5632ad4.png)
![BRF_class](https://user-images.githubusercontent.com/106105597/200405379-f1a803aa-8099-4a7f-80af-5ef6180e35d6.png)

***
* Easy Ensemble
  * Balanced Accuracy - .93
  * Precision - high risk .07, low risk 1.0
  * Recall - high risk .91, low risk .94
***
![EE_BAS](https://user-images.githubusercontent.com/106105597/200405438-54b02e08-3553-4d31-9ade-c4a2634c6094.png)
![EE_class](https://user-images.githubusercontent.com/106105597/200405531-5fb078d3-dbfb-4b58-a385-770fcfd26d36.png)

<h2> Summary </h2>
<p> Based on this testing Easy Ensemble has the highest balanced accuracy as well as both high and low risk recall. The downside is it has the highest rate of false positives. However when it comes to credit risk we'd rather tag too many people as high risk than tag someone high risk as low risk resulting in potential large losses if/when they were to default. So Easy Ensemble would be the recommended model for this project</p>
