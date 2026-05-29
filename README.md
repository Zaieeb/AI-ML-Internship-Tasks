# AI/ML Internship Tasks

## Task 1: Exploring and Visualizing the Iris Dataset

### Objective
Load, inspect, and visualize the Iris dataset to understand data distributions and feature relationships.

### Dataset
- **Name**: Iris Dataset
- **Source**: Built-in via Seaborn (`sns.load_dataset('iris')`)
- **Size**: 150 samples, 4 features, 3 species classes

### Steps Performed
- Loaded dataset using pandas
- Inspected shape, columns, .info() and .describe()
- Created scatter plots, histograms, and box plots

### Key Findings
- Setosa is linearly separable from other species
- Petal features show stronger class separation than sepal features
- No missing values; dataset is clean and ready for ML modeling

### Tools Used
Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook


---

## Task 2: Predict Future Stock Prices (Short-Term)

### Objective
Use historical stock data to predict the next day's closing price using regression models.

### Dataset
- **Source**: Yahoo Finance via `yfinance` library
- **Stock**: Apple Inc. (AAPL)
- **Period**: 2019–2024

### Models Applied
- Linear Regression
- Random Forest Regressor

### Key Results
- Both models achieved R² ≈ 0.99 on test data
- Random Forest outperformed Linear Regression (lower MAE & RMSE)
- Today's closing price is the strongest predictor of tomorrow's price

### Tools Used
Python, Pandas, yfinance, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook
