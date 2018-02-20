# Data-Analytics
Data Analytics Module Contents

The purpose of this repo is to store the contents of my project based on credit card fraud classification as part of my masters curriculum.
The main issue with this dataset, which was sourced from kaggle, was it was highly unbalanced. There are approximately 280,000 rows of valid transactions and approximately 492 rows of fraudulent transactions.

The purpose of this project is the analyse three classification algorithms to determine which is the most accurate and computationally efficient. The proposed classification algorithms for this project are KNN, Logistic Regression and Random Forests. It is expected that Random Forests will be the optimal algorithm in this case as it does not require normalisation of the data.

To date, only the KNN classifier has been implemented with an accuracy score of 99.61%. This score was achieved on a sample of approximately 10% of the dataset. As the datset was highly unbalanced all fraudulent transactions were included in this sample. The sample data was then split for training and testing with a stratified 75:25 partition.
