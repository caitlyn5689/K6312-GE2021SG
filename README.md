# Wine Rating Prediction
An increasing number of people pay attention to the enjoyment of life because of the development of technology and economy. Therefore, people are more and more in pursuit of quality wine. However, most of people don’t have enough time to learn knowledge about wine. Thus, our group want to predict the rating of wine and attempt to train the four models: Logistic Regression, KNN(k-Nearest Neighbor), Support Vector Machine and Random Forest, and evaluate their classification effectiveness.
## 1. Exploratory Data Analysis
We downloads the raw data (can be find in the data file folder) from kaggele. In this part, we will display the distribution of the different columns of the raw data with bar chart, line chart, word cloud and other visulization methods.
## 2. Data Cleaning
Drop the features with high proportion of null valus or high cardinality. 
## 3. Feature engineering
Extract useful inforamtion from text features and imputate the null values of remaining featuresn with appropriate filling values.
## 4. Models Training and Evaluation
In this section, we split the data into training and testing sets and use SMOTE on the training data to solve imbalance problem. After that, we trained 4 models (LR, KNN, SVM, RF) and did hyperparameters tuning to optimize the models. Finally, we test the four models and evaluate them with multiple criterias.
