<h1 align='center'>Car Price Prediction ML Model</h1>
<h3>Steps followed to make the model:</h3>

- The ToyotaCoralla.csv file is taken from the Kaggle website.
- Analysed the dataset and visualized the numerical and categorical variables.
- Detected the outliers, most of them are present in the 'KM' and 'Price' columns of the dataset.
- Imputed the outliers with the median value of the respective columns.
- Multivariate analysis like constructing the pair plots.
- Applied transformation for the X variables such as Standardization for the numerical and Label Encoding for the categorical variables.
- Split the dataset into training and testing data with the test data size as 20% of the dataset.
- Fitting the model using Linear Regression as the target variable 'Price' is numerical.
- Obtained training and test R squared values as 75.4% and 75.3% respectively.
- By using Regularization methods like Lasso Regression, I have overcome the model from the Overfitting stage and removed 2 X variables.
- Observing the Q-Q plot of residuals, there are some outliers in the data. So, I have removed those outliers using leverage cutoff and cook distance.
- Finally training and testing R squared values are obtained as 81.5% and 78.7% respectively, where the training R squared value is increased by 6% and testing accuracy is increased by 3%.
