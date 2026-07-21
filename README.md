# Saudi Aramco Stock Close Price Ridge Regression

### Description

This project predicts Saudi Aramco's daily closing stock price using historical market data (Open, High, Low). The dataset contains 1,164 trading days (Dec 2019 onward). After visualizing feature correlations via a seaborn heatmap, four regression models were trained and compared: Ridge, Ridge with PolynomialFeatures (degree=10), Lasso, and ElasticNet. The best-performing model was Ridge with polynomial features and standardization, achieving an R² score of **0.89** and MAE of **0.81** on the test set. The final model was serialized with `pickle`.

### The best model
the best model was ridge Regression with polynomial feature of degree 10

**Tech stack:** Python 3.11, pandas, scikit-learn, seaborn, matplotlib.  
**File:** `main.ipynb` | **Model:** `model.pkl` | **Dataset:** `saudi_aramco_data.csv`
