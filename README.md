
# Bulldozer Price Prediction

A machine learning project that predicts the sale price of bulldozers using historical auction data. The project explores data preprocessing, feature engineering, model training, and evaluation to estimate the price of heavy equipment.

## Overview

Predicting bulldozer prices can help buyers, sellers, and equipment dealers make more informed decisions. This project uses historical sales data to train a machine learning model that estimates bulldozer sale prices from relevant machine characteristics and sales information.

The project is based on the Blue Book for Bulldozers dataset, commonly used in machine learning practice to explore regression problems with real-world tabular data.

## Objectives

- Explore and understand historical bulldozer sales data.
- Clean and preprocess numerical and categorical features.
- Perform feature engineering to prepare data for machine learning.
- Train regression models to predict sale prices.
- Evaluate model performance using appropriate regression metrics.
- Practice an end-to-end machine learning workflow.

## Dataset

The project uses the **Blue Book for Bulldozers** dataset, which contains historical auction sales information for heavy equipment.

Typical features include:

- Machine model and configuration
- Manufacturing year
- Machine age at the time of sale
- Equipment usage and product details
- Auction sale date and other sales-related information

The dataset is associated with the Kaggle competition:

[Blue Book for Bulldozers — Kaggle](https://www.kaggle.com/competitions/bluebook-for-bulldozers)

Download the dataset from Kaggle and place the required files in the appropriate data directory.

## Technologies

- **Python** — Programming language
- **Jupyter Notebook** — Interactive experimentation
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computing
- **Matplotlib** — Data visualization
- **Scikit-learn** — Machine learning utilities and evaluation

## Machine Learning Workflow

1. **Data exploration** — Inspect the dataset, understand feature distributions, and identify missing values.
2. **Data preprocessing** — Handle missing data and prepare features for modelling.
3. **Feature engineering** — Extract useful information from dates and other relevant columns.
4. **Model training** — Train regression models using historical sales data.
5. **Model evaluation** — Evaluate predictions using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
6. **Prediction** — Use the trained model to estimate bulldozer sale prices for unseen examples.

## Project Structure

```text
bulldozer-price-prediction/
├── data/                  # Dataset files (not necessarily committed)
├── notebooks/             # Data exploration and experiments
├── models/                # Saved trained models, if applicable
├── README.md
└── requirements.txt
```

The structure may vary depending on the current implementation.

## Getting Started

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
cd bulldozer-price-prediction
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it:

**Linux/macOS**
```bash
source .venv/bin/activate
```

**Windows**
```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

If a `requirements.txt` file is available, use:

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

```bash
jupyter notebook
```

Open the project notebook and run the cells in order after downloading and configuring the dataset.

## Evaluation

Model performance can be evaluated using:

- **Mean Absolute Error (MAE):** Measures the average absolute difference between predicted and actual prices.
- **Root Mean Squared Error (RMSE):** Penalizes larger prediction errors more heavily.

The final metrics depend on the selected model, preprocessing strategy, and validation method.

## What I Learned

- Working with real-world tabular datasets.
- Preparing data for regression tasks.
- Exploring feature engineering and model evaluation.
- Applying Python's data science and machine learning libraries.
- Developing a structured approach to end-to-end ML projects.

## Future Improvements

- Compare multiple regression algorithms.
- Improve feature engineering and hyperparameter tuning.
- Evaluate models using a validation strategy that respects the chronological nature of the data.
- Build a simple interface for generating price predictions.
- Explore model deployment through an API.

## Author

**Herbert Ntim**

- [GitHub](https://github.com/HerbertNtim)
- [LinkedIn](https://www.linkedin.com/in/hntim/)
- [X](https://x.com/hntim0829)
