# IBM-Data-Science-Professional-Certificate

[Certificate Link](https://coursera.org/share/3c79fa5386b3aec34b9651648e8b07dd)

These are some of the project notebooks that I have gotten to work on in my IBM Data Science Professional Certificate course:
* Analyzing US Economic Data and Building a Dashboard + index.html
  * More of a warm-up exercise that demonstrates ability to read a csv, use super-basic pandas, and plot using Bokeh.
  * Note: Github does not display the image made at the end of the exercise so it is uploaded separately as index.html, or you can download it and view run it yourself on Jupyter
* House Sales in King County, USA
  * Using statistical analysis to build a model for home prices in King County and evaluating that model through R^2.
  * Feature selection using correlation and model building using linear regression were the main focus of this lesson project.
  * Usage of the sklearn library and its Pipeline object, StandardScaler, PolynomialFeatures, LinearRegression tools, and Ridge model object.
  * Conclusion: High level of correlation between the price of homes and the features such as ["floors", "waterfront", "lat", "bedrooms", "sqft_basement", "view", "bathrooms", "sqft_living15", "sqft_above", "grade", "sqft_living"].
* Machine Learning with Python_ The Best Classifier ( Loan Repayments and Defaults )
  * Used KNN, Decision Tree, Support Vector Machine, and Logistic Regression to build models that predict loan repayments based on a number of features.
  * Evaluated each model's effectiveness by calculating their Jaccard Similarity Scores and F-1 Scores ( also Log Loss for Logistic Regression ) because we used split training and testing data sets.
  * Data pre-processing involved binarization (one hot encoding), numerization, visualization (Seaborn), and normalization. All to help with feature selection and data cleaning for feeding into the models.
  * Conclusion: The Logistic Regression model was the most accurate, but the Decision Tree turned out with the highest F1 score indicating a good harmonic mean of precision and recall ( low false positives, low false negatives).


TODO: Clean up Capstone Project and upload.
