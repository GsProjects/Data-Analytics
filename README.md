# Data-Analytics
Data Analytics: Credit Card Fraud Classification

The purpose of this repo is to store the contents of my project based on credit card fraud classification as part of my masters curriculum.
The main issue with this dataset, which was sourced from kaggle, was it was highly unbalanced. There are approximately 280,000 rows of valid transactions and approximately 492 rows of fraudulent transactions.

The purpose of this project is the analyse three classification algorithms to determine which is the most accurate and computationally efficient. The proposed classification algorithms for this project are KNN, Logistic Regression and Random Forests. It is expected that Random Forests will be the optimal algorithm in this case as it does not require normalisation of the data.


Results:

In terms of performing an exploratory data analysis, there was not much that could be done. This was due to 28 out of the 31 features being the result of a PCA transformation which finds the directions of maximum variance within the data. These variables were then labelled from V1 to V28 making the process of looking at individual features in detail and extracting information about the entire process slightly redundent.

Having implemented and analysed all three algorithms, Random Forest was the optimal algorithm in this scenario. Despite Random Forest being a successful algorithm even on default parametes, its ability to model non linear patterns may have been the difference in this case. In terms of the user both KNN and Random Forest are relatively straightforward making the entire process much simpler overall. Despite Random Forests not requiring normalised data, the data used to train the model was normalised as both KNN and Logistic Regression required the data to be normalised.
