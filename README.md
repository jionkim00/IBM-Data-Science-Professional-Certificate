# IBM-Data-Science-Professional-Certificate

[Certificate Link](https://coursera.org/share/3c79fa5386b3aec34b9651648e8b07dd)

In order of involvement and self-guided completion, these are some of the project notebooks that I have gotten to work on in my IBM Data Science Professional Certificate course:
* [Capstone Project: Car Insurance Claim Prediction Model](https://github.com/jionkim00/IBM-Data-Science-Professional-Certificate/blob/main/capstone-car-insurance-claims.ipynb)
  * Decision Tree and Logistic Regression are utilized to build models that predict cars that will file an insurance claim in 6 months based on given features.
  * Due to overfitting, the decision tree won out and was used to predict a total of 3,096 claims out of 39,063.
  * Conclusion: We could build a pretty accurate model when using both the decision tree and logistic regression models; however, the latter suffered from over fitting. 
* [Machine Learning with Python_ The Best Classifier ( Loan Repayments and Defaults )](https://github.com/jionkim00/IBM-Data-Science-Professional-Certificate/blob/main/Machine%20Learning%20with%20Python_%20The%20Best%20Classifier.ipynb)
  * Used KNN, Decision Tree, Support Vector Machine, and Logistic Regression to build models that predict loan repayments based on a number of features.
  * Evaluated each model's effectiveness by calculating their Jaccard Similarity Scores and F-1 Scores ( also Log Loss for Logistic Regression ) because we used split training and testing data sets.
  * Data pre-processing involved binarization (one hot encoding), numerization, visualization (Seaborn), and normalization. All to help with feature selection and data cleaning for feeding into the models.
  * Conclusion: The Logistic Regression model was the most accurate, but the Decision Tree turned out with the highest F1 score indicating a good harmonic mean of precision and recall ( low false positives, low false negatives).
* [House Sales in King County, USA](https://github.com/jionkim00/IBM-Data-Science-Professional-Certificate/blob/main/House%20Sales%20in%20King%20County%2C%20USA.ipynb)
  * Using statistical analysis to build a model for home prices in King County and evaluating that model through R^2.
  * Feature selection using correlation and model building using linear regression were the main focus of this lesson project.
  * Usage of the sklearn library and its Pipeline object, StandardScaler, PolynomialFeatures, LinearRegression tools, and Ridge model object.
  * Conclusion: High level of correlation between the price of homes and the features such as ["floors", "waterfront", "lat", "bedrooms", "sqft_basement", "view", "bathrooms", "sqft_living15", "sqft_above", "grade", "sqft_living"].
* [Analyzing US Economic Data and Building a Dashboard + index.html](https://github.com/jionkim00/IBM-Data-Science-Professional-Certificate/blob/main/Analyzing%20US%20Economic%20Data%20and%20Building%20a%20Dashboard.ipynb)
  * More of a warm-up exercise that demonstrates ability to read a csv, use super-basic pandas, and plot using Bokeh.
  * Note: Github does not display the image made at the end of the exercise so it is uploaded separately as index.html, or you can download it and view run it yourself on Jupyter




