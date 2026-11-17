# House Price Prediction Using Linear Regression

A machine learning learning project that explores housing data and predicts house prices using **Linear Regression**.

## Project workflow
- Data loading and exploration
- Exploratory Data Analysis (EDA)
- Distribution, outlier, and correlation visualizations
- Categorical feature encoding
- Train-test split
- Numerical feature scaling with `StandardScaler`
- Linear Regression model training
- Regression evaluation
- **Actual vs Predicted House Prices** scatter plot

## Model performance

Results recorded in the submitted notebook:

| Metric | Result |
|---|---:|
| R² score | 0.6529 (65.29%) |
| Adjusted R² | 0.6054 (60.54%) |
| Mean Absolute Error (MAE) | 970,043.40 |
| Mean Squared Error (MSE) | 1,754,318,687,330.67 |

These results use the notebook's current split (`test_size=0.20`, `random_state=42`). They may vary if the data or split changes.

## Repository structure

```text
├── data/
│   └── Housing.csv
├── notebooks/
│   └── house_price_prediction.ipynb
├── project-poster.png
├── README.md
└── requirements.txt
```

## Dataset setup

The uploaded notebook did not include the dataset file. Add `Housing.csv` to the repository's `data/` folder. The notebook reads it using a relative path.

Only publish the dataset if its license allows redistribution. Otherwise, keep it local.

## Run locally

```bash
pip install -r requirements.txt
```

Then open `notebooks/house_price_prediction.ipynb` in Jupyter Notebook or VS Code and run the cells.

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook.

## Future improvements

- Use a `Pipeline` and `ColumnTransformer` for a cleaner preprocessing workflow.
- Compare Linear Regression with Ridge, Lasso, Random Forest, and Gradient Boosting.
- Add cross-validation and residual analysis.
- Investigate feature importance and model errors.

**Note:** This is a learning project. The reported metrics describe this particular test split and do not guarantee future prediction accuracy.
