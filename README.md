### Overview of the Analysis: 
Fast-Lending, a peer-to-peer lending service, asked our team to create a machine learning model to predict risk and provide a more accurate indicator of good candidates for loans. We performed six supervised machine learning models: four logistic regression models with different sampling methods and two random forest models with two different classifiers to predict credit risk.

### Results: 
#### Logistic Regression Models: 
* conducted four different sampling methods: 
##### Naive Oversampling
* This method had an accuracy score of 0.67.
* The precision scores was 0.99.
* The recall score was 0.55.

![](https://i.imgur.com/S9Apprp.png)

##### SMOTE Oversampling
* This method had an accuracy score of 0.66.
* The precision scores was 0.99.
* The recall score was 0.61.

![](https://i.imgur.com/8Y5Aase.png)

##### Undersampling
* This method had an accuracy score of 0.54.
* The precision scores was 0.99.
* The recall score was 0.40

![](https://i.imgur.com/5UivQAj.png)

##### Combined (Over & Under) Sampling
* This method had an accuracy score of 0.54.
* The precision scores was 0.99.
* The recall score was 0.58.

![](https://i.imgur.com/S8loXkw.png)

#### Random Forrest Models:
##### Balanced Classifier Algorithim
This method had an accuracy score of 0.79.
* The precision scores was 0.99.
* The recall score was 0.87.

![](https://i.imgur.com/XCbDz8G.png)

##### Easy Ensemble Algorithim
* This method had an accuracy score of 0.93.
* The precision scores was 0.99.
* The recall score was 0.94.

![](https://i.imgur.com/GIT6Ujz.png)


### Summary: 
Overall, the random forest models had higher accuracy scores and recall scores. In particular, the random forest model with the easy ensemble algorithm performed the best out of all six models with an accuracy score of 0.93, a precision score of 0.99, and a recall score of 0.94. The four logistic regression models that evaluated different methods of sampling performed the worst. In particular, the Undersampling model had the lowest accuracy score of 0.54 and the lowest precision score of 0.44. Moving forward, I recommend the company to use the Random Forest model with the easy ensemble classifier to predict credit risk as it was the most effective.
