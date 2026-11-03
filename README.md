# Heavy Equipment Price Prediction

A machine learning project focused on predicting the sale prices of heavy equipment at auction using historical sales data.

The project explores data preprocessing, feature engineering, regression modelling, hyperparameter tuning, and ensemble learning to improve prediction accuracy.

## Project Overview

The objective was to predict the sale price of heavy equipment based on its characteristics and historical auction data.

The project was developed as part of a Kaggle machine learning competition, with **Root Mean Squared Logarithmic Error (RMSLE)** used as the evaluation metric.

## Tech Stack

- **Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Visualisation:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Gradient Boosting:** LightGBM, XGBoost, CatBoost
- **Environment:** Jupyter Notebook

## Workflow

The project followed an end-to-end machine learning workflow:

1. **Exploratory Data Analysis** – Examined feature distributions, missing values, categorical variables, and relationships between equipment characteristics and sale prices.
2. **Data Preprocessing** – Handled missing values, encoded categorical features, and scaled selected numerical features.
3. **Feature Engineering** – Created additional features to capture information such as transaction year, transaction quarter, asset age, and equipment description characteristics.
4. **Model Development** – Trained and evaluated multiple regression models, including Linear Regression, Random Forest, LightGBM, XGBoost, and CatBoost.
5. **Hyperparameter Tuning** – Experimented with model configurations to improve predictive performance.
6. **Ensemble Learning** – Combined predictions from multiple gradient boosting models using a weighted ensemble.

## Results

The final submission achieved the following result on the Kaggle public leaderboard:

| Metric | Result |
|---|---:|
| Public Leaderboard Score (RMSLE) | **0.1911** |
| Competition Rank | **368 / 2,593** |
| Percentile | **Top 14.2%** |

The weighted ensemble of gradient boosting models provided the strongest overall performance among the approaches explored.

## Repository Structure

```text
heavy-equipment-price-prediction/
│
├── Heavy_Equipment_Price_Prediction.ipynb
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

## Getting Started

Clone the repository:

```bash
git clone https://github.com/niharpanse/Heavy-Equipment-Machinery-Price-Prediction
cd Heavy-Equipment-Machinery-Price-Prediction
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the project notebook to explore the analysis, preprocessing, model development, and evaluation workflow.

**Note:** The dataset is not included in this repository. Access to the original competition dataset is required to reproduce the notebook results.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

The original dataset remains subject to its respective source and competition terms.
