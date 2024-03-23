# ML-model-for-a-perfect-party-playlist
The project is focused on elaborating a regression model to predict tracks' danceability and craft the perfect summer party playlist.

The project involves the analysis of the **Spotify** dataset (modified from the [initial source](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) on Kaggle), containing 20 columns and 113,027 entries.

Initially, descriptive statistics and data visualization techniques were deployed to explore the dataset's characteristics. Subsequent steps included data cleaning, duplicate deletion, and outlier elimination to ensure data quality.

Numeric features' distributions were analyzed, and bivariate analysis was conducted to investigate potential linear relationships among variables. Categorical features were also examined to understand their distributions and impact on the target variable.

Four machine learning models were elaborated: Elastic Net as a linear model, Decision Tree Regressor as a tree-based model, Random Forest Regressor as an ensemble bootstrapping algorithm, and LGBMRegressor as an ensemble boosting algorithm. Model performance was evaluated through cross-validation, and the best-performing model was selected.

Residuals analysis was performed to assess model validity, and model outcomes were analyzed to gain insights into predictive performance. Finally, a playlist was crafted based on the model's recommendations and analysis findings.

