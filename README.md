# California Housing Price Prediction ML Models

This project aims to build machine learning models that can predict the price of homes in California given specific data attributes. The maximum achieved accuracy is approximately 81.13%.
## Setup
<details>
  
  Create a virtual environment venv in the directory
  ```
  python -m venv venv
  ```
  Activate the environment
    
  - for linux/mac
  ```
  source venv/bin/activate
  ```
  - for windows
  ```
  venv\Scripts\activate
  ```
  Install dependencies from requirements.txt file
  ```
  pip install -r requirements.txt
  ```
  Run the jupyter lab
  ```
  jupyter lab
  ```
</details>

## Table of Contents

- [Introduction](#introduction)
- [Libraries Used](#libraries-used)
- [Data](#data)
- [Data Analysis and Visualization](#data-analysis-and-visualization)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)

## Introduction

This project focuses on predicting the housing prices in California using various machine learning models. The primary dataset used includes attributes such as longitude, latitude, housing median age, total rooms, total bedrooms, population, households, median income, ocean proximity, and median house value.

## Libraries Used

The following libraries are used in this project:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

## Data

The dataset used in this project is sourced from a CSV file named `housing.csv`.

## Data Analysis and Visualization

Basic data analysis and visualization steps are performed to understand the distribution and relationships within the dataset.

## Data Preprocessing

Data cleaning and preprocessing steps are undertaken to prepare the data for model training. This includes handling missing values, feature scaling, and encoding categorical variables.

## Model Training

Several machine learning models are trained on the processed dataset. Details about the specific models used, their parameters, and the training process are documented.

## Model Evaluation

The performance of the models is evaluated using appropriate metrics. The best-performing model achieves an accuracy of approximately 81.13%.

## Conclusion

The project demonstrates the ability to predict housing prices in California with reasonable accuracy using machine learning techniques. The results indicate the potential of these models to assist in real estate pricing and decision-making.

---

*Note: For detailed code and step-by-step implementation, please refer to the Jupyter notebook `Main.ipynb` included in this repository.*
