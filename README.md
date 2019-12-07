![Screen Shot 2019-12-04 at 1 59 44 PM](https://user-images.githubusercontent.com/23482039/70368648-669f9580-187b-11ea-81b0-3bcdf9be7136.png)

 
 The data set named L&T Vehicle Loan Default Prediction can be retrieved from [Kaggle](https://www.kaggle.com/gauravdesurkar/lt-vehicle-loan-default-prediction). This data set comes from the company Larsen & Toubro from India and contains 233,154 rows and 41 features, where every row represents an individual loan. One of the features is named 'loan default' which will be used as the label. It's a binary field indicating if the borrower defaulted or not in the first EMI. The value is ‘1’ when the borrower defaulted.  Otherwise the value is set to '0'.  
 
 The algorithms used are:
 * Decision tree
 * K-nearest neighbor
 * Skope-rule
 * Multi-layer perceptron
 * Support vector machine
 * XGBoost
 * Random forest
 
 The best classifier was a hybrid ensemble using the top three classifiers (Random Forest, 1-Nearest Neighbor and XGBoost). 
 Results using this model were promising as it raised the average recall to **86.37%.**
