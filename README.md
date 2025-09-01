# Introduction to Machine Learning (IML) - CS 3410

This repository contains machine learning assignments and projects for the CS 3410 Introduction to Machine Learning course.

## Repository Structure

```
shivansh_verma_A1/
├── life_expectancy_task/       # Assignment 1 - Problem 1
├── laptop_price_task/          # Assignment 1 - Problem 2
└── retail_task/               # Assignment 1 - Problem 3
```

Each task follows a standardized project structure:

```
task_name/
├── data/                      # Training and test datasets (ignored by git)
├── models/                    # Saved trained models
├── notebooks/                 # Jupyter notebooks for exploration
│   └── data_exploration.ipynb
├── results/                   # Model performance metrics and outputs
│   └── train_metrics.txt
├── src/                       # Source code
│   ├── data_preprocessing.py  # Data cleaning and feature engineering
│   ├── predict.py            # Prediction pipeline
│   └── train_model.py        # Model training pipeline
├── requirements.txt          # Python dependencies
└── README.md                # Task-specific documentation
```

## Assignment 1 - Three Regression Tasks

### 1. Life Expectancy Prediction (WHO Dataset)

- **Type**: Regression Task
- **Description**: Health, economic, and demographic data from WHO member states
- **Target**: Life expectancy in years
- **Location**: `life_expectancy_task/`

### 2. Laptop Price Prediction

- **Type**: Regression Task
- **Description**: Laptop specifications including brand, CPU, RAM, storage, GPU, OS
- **Target**: Laptop price (continuous)
- **Location**: `laptop_price_task/`

### 3. Retail Analytics

- **Type**: Regression Task
- **Description**: Large retail dataset with 70+ customer, product, and transaction variables
- **Target**: Average purchase value per customer
- **Location**: `retail_task/`

## Results and Metrics

Each task includes:

- Training performance metrics in `results/train_metrics.txt`
- Saved model artifacts in `models/`
- Exploratory data analysis in Jupyter notebooks

## Author

**Shivansh Verma**

- Course: CS 3410 - Introduction to Machine Learning
- Assignment: A1 - Regression Tasks

---

_Last Updated: September 2025_
