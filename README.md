# Diabetes-Prediction

In today’s world, diabetes is one of the most prevalent problems that a human encounters. It can be because of various factors. Stress, Unhealthy eating habits, Less physical activity, Lack of sleep, Less intake of greens etc.

INFERENCE MADE FROM TABLEAU VISUALISATION 

In this case study, it can be witnessed that between the age of 20 – 40 has diabetes and the reasons are obvious, which are stated above. This case study also takes a dig on diabetes affecting with the number of pregnancies which has a different intake on the cause of diabetes. As we can see, woman who have had more pregnancies are less diabetic and vice versa. It can be also be witnessed that majority woman get pregnant at the age of 20 – 30 with an average no. of pregnancies between 1 - 2. As the age group increases, less woman get pregnant with an increase in the average no. of pregnancies, i.e. between 4-5. This is a very interesting result that was visualized. The scatter trend of Blood Pressure wrt Age has a very enthralling result. We can see that there is a varied pattern where between the age of 20 – 40, We have people having a moderate Blood Pressure level. This means that majority of people between this age group get their blood pressure checked because the trends goes down as the age group increases. We can also see large number of people having high blood pressure as there are high scatter peaks shown in the graph. The glucose trend looks to be moderate for all the age groups.

MACHINE LEARNING 

This case study also gave me the opportunity to work on various Machine Learning algorithms. Before the training and testing of the model, I have done Exploratory Data Analysis. A lot of outliers were removed using quantile technique, making the data more consistent. The following algorithms were used and I have mentioned their accuracy too.

S.No.	Algorithm used	Accuracy using Precision/Recall	Accuracy using ROC
1.	Logistic Regression 	60.4%	73.7%
2. 	KNN	53.4%	55.04%
3. 	Naives Bayes	62.77%	66.5%
4. 	SVM	62.7%	61%
5.	SVC	60.4%	59.6%
6.	Random Forest	60.4%	62.1%
7.	Decision Tree	58.1%	59%

As we can see, The best model is Logistic Regression as it has a better accuracy level when checked with ROC curve. When we compare KNN with other model, KNN has the least accuracy, making it the worst model for this case. 

Why is ROC curve better than Precision and Recall?

•	ROC Curves summarize the trade-off between the true positive rate and false positive rate for a predictive model using different probability thresholds.
•	Precision-Recall curves summarize the trade-off between the true positive rate and the positive predictive value for a predictive model using different probability thresholds.
•	ROC curves are appropriate when the observations are balanced between each class, whereas precision-recall curves are appropriate for imbalanced datasets.


