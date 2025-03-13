# ML_AI_20_1_Assignment
# Assignment 20.1 - Initial Report & Exploratory Data Analysis

## Project Overview
This repository contains the initial report and exploratory data analysis (EDA) for my capstone project on housing prices. Housing prices is a topic of deep interest to me as I'm an active real estate investor myself. I wanted to explore a good data set on house prices and use it to build a predictive model.

## Dataset Selection
After evaluating multiple sources such as:
- Kaggle
- U.S. Census Data
- Federal Economic Data Reports from the Bank of Missouri**

I ultimately chose a dataset on California housing prices from Kaggle. The primary reason for this choice was the dataset's size. Other datasets I found were either too small (e.g., ~200 rows) or too huge (e.g., ~1,000 columns). The selected dataset, containing ~20,000 rows and 10 columns, struck a balance between manageability at my current skillset and depth of analysis.

## Objective
The goal of this project is to predict housing prices using the datset's other columns as explanatory variables. Since housing prices are both continuous and numerical, I choose a regression model as my primary approach for this analysis.

## Repository Structure

📂 Assignment_20_1
│── 📜 README.md  # This file
│── housing.csv        # Contains the dataset used for analysis
│── Assignment 20.1 Capstone Initial Report.ipynb   # Jupyter notebooks with EDA and model training


## Getting Started
### Prerequisites
To run the notebooks, install the required dependencies using:
```
pip install -r requirements.txt
```

### Running the Analysis
1. Clone this repository:
   ```
   git clone https://github.com/yourusername/assignment-20-1.git
   ```
2. Navigate into the project folder:
   ```
   cd assignment-20-1
   ```
3. Open Jupyter Notebook:
   ```
   jupyter notebook
   ```
4. Open and run the notebooks inside the `notebooks` folder.

## Next 
- My current exploratory analysis showed that both the MSE and MAE were quite high using a linear regression model that used 4 of the existing columns in the dataset. What I will do next to is explore a few other types of regressions namely: 1)improved Linear Regression (RIDGE, Baysian, LASSO), 2) SVM regressor, 3) Random Forest regressor.

- Depending on how these go, I may also delve into feature engineering and come up with a few more columns to fit into my model. As shown in this notebook, I used OneHotEncoder to be able to use the category column, but so far I haven't fed these columns into my model. I will explore more feature engineering depending on how the other models go. 

## Contact
For any questions, feel free to reach out or open an issue in the repository.

