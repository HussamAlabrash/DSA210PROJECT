# DSA210 Project: Conflict, Oil Prices, and Economic Performance in the Middle East

This project analyzes the relationship between conflict, oil prices, and economic performance in Middle Eastern countries.

## Research Goal

The main goal is to understand whether conflict-related variables and oil prices are associated with economic indicators such as GDP growth, inflation, and FDI. The final machine learning task predicts annual GDP growth using economic, oil price, and conflict-related variables.

## Data Sources

The project uses two public Kaggle datasets:

1. Middle East Economic Data 1990-2024 with Oil
2. MiddleEast 2015-2024 Nov01 conflict dataset

The conflict dataset was aggregated by country and year, then merged with the economic dataset.

## Methods Used

### Data Analysis

- Data cleaning
- Data filtering
- Dataset merging
- Exploratory data analysis
- Correlation analysis
- Hypothesis testing
- Data visualization

### Machine Learning

- Baseline Mean Model
- Linear Regression
- kNN Regression
- Decision Tree Regression
- Random Forest Regression
- Hyperparameter tuning
- Train / validation / test comparison
- Feature importance analysis

## Evaluation Metrics

The machine learning models were evaluated using:

- MAE
- RMSE
- R² Score

## Main Findings

- Conflict events are negatively associated with GDP growth.
- Oil price is positively associated with GDP growth.
- kNN Regression performed best on the test set based on RMSE.
- Negative R² scores show that GDP growth is difficult to predict accurately using the available variables.
- Random Forest feature importance was used to interpret which variables contributed most to prediction.

## Repository Contents

- `DSA210.ipynb`: Main notebook
- `Project Proposal.pdf`: Project proposal
- `Final_Report.md`: Final report
- `requirements.txt`: Python dependencies
- `AI_ASSISTANCE.md`: AI assistance disclosure

## How to Reproduce

Clone the repository:

```bash
git clone https://github.com/HussamAlabrash/DSA210PROJECT.git
cd DSA210PROJECT
