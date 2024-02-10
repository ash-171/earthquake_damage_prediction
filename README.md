# Earthquake Damage Prediction

## Overview

This repository contains Jupyter Notebook files for predicting the damage grade of buildings after an earthquake. The dataset includes various features related to buildings and their characteristics, and the target variable is the damage grade, which represents the severity of the damage (1, 2, or 3). The main file, `Earthquake_Damage_Prediction.ipynb`, includes exploratory data analysis (EDA), data wrangling, feature selection, and predictive modeling using machine learning algorithms. The analysis utilizes two data files: `train_labels.csv` and `train_values.csv`. 

## Files

1. `Earthquake_Damage_Prediction.ipynb`: This Jupyter Notebook is the main file containing the end-to-end analysis. It covers the following steps:
   - Exploratory Data Analysis (EDA) using AutoViz for visualization.
   - Data wrangling and preprocessing.
   - Feature selection to identify relevant predictors.
   - Application of machine learning algorithms for damage grade prediction.

2. `train_labels.csv`: This CSV file contains the labels for the training set, specifying the damage grade of each building.

3. `train_values.csv`: This CSV file contains the features and attributes of the training set, including information about the buildings.

## Contents

1. **Introduction:**
   - Brief overview of the problem statement and goals.
   - Description of the dataset.

2. **Exploratory Data Analysis (EDA):**
   - Visualizations of key statistics using the AutoViz library.
   - Insights into feature distributions and relationships.

3. **Data Wrangling:**
   - Handling missing values.
   - Encoding categorical variables.
   - Feature scaling and normalization.

4. **Feature Selection:**
   - Identifying and selecting relevant features.
   - Exploring correlations and importance.

5. **Modeling:**
   - Application of various machine learning models.
   - Evaluation of model performance.

6. **Conclusion:**
   - Summary of key findings.
   - Suggestions for further improvement.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/earthquake-damage-prediction.git
   cd earthquake-damage-prediction
   ```

2. **Install Dependencies:**
   - Make sure you have the required dependencies installed. You can use the following:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook:**
   - Open and run the Jupyter Notebook `Earthquake_Damage_Prediction.ipynb` using a Jupyter environment.

4. **Explore the Results:**
   - Review the visualizations, analysis, and modeling results in the notebook.
   - Understand the insights gained and model performances.

## Authors

Aswathi 
Akhil Sebastian

## Acknowledgments

Special thanks to the https://www.drivendata.org/competitions/57/nepal-earthquake/, from where the earthquake damage prediction dataset was obtained. The data was collected through surveys by Kathmandu Living Labs and the Central Bureau of Statistics, which works under the National Planning Commission Secretariat of Nepal. This survey is one of the largest post-disaster datasets ever collected, containing valuable information on earthquake impacts, household conditions, and socio-economic-demographic statistics. The analysis and code provided here serve as a guide for similar predictive modeling tasks.

Feel free to reach out for any questions or feedback!
