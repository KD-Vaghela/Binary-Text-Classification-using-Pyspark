# Binary-Text-Classification-using-Pyspark
The aim of the project is to create a model that can classify the text as postive or negative. The dataset used for this proejct is the amazon food reviews dataset that contained the following information:
1.	Id
2.	ProductId
3.	UserId
4.	ProfileName
5.	HelpfulnessNumerator – number of users who found the review helpful
6.	HelpfulnessDenominator – number of users who indicated whether they found the review helpful or not 
7.	Score – rating between 1 and 5
8.	Time – timestamp for the review
9.	Summary – Brief summary of the review 
10.	Text – text of the review
Out of the available variables I used Text and Score variable for my project. The classification is done in Pyspark. I have used different algorithms like LinearSVC, Logistic Regression and Naive Bayes. The performance of LinearSVC was better than the other two algorithms.