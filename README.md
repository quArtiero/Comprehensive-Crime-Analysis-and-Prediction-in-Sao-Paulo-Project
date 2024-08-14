Comprehensive Crime Analysis and Prediction in São Paulo

Project Overview
----------------
This project aims to analyze crime data in São Paulo, identify trends and patterns, and develop predictive models to forecast future crime occurrences.

Table of Contents
-----------------
1. Introduction
2. Data Collection and Preprocessing
   - Handle Missing Values and Inconsistencies
   - Data Cleaning
   - Standardize Timestamps and Address Formats
3. Exploratory Data Analysis (EDA)
   - Descriptive Statistics
   - Visualization
4. Predictive Modeling
   - Objective
   - Feature Engineering
   - Model Training and Evaluation
6. How to Run the Project
7. Requirements
8. Contributors
9. License

Introduction
------------
This project uses crime data from São Paulo to perform a comprehensive analysis. The analysis includes cleaning and preprocessing data, exploring data trends through visualization, and developing predictive models to understand and forecast crime patterns. 
Data Collection and Preprocessing
---------------------------------
Handle Missing Values and Inconsistencies

-----------------------------------------
The dataset is cleaned by addressing missing values and inconsistencies. Rows with critical missing data are removed, and placeholders are used where appropriate.

Data Cleaning
-------------
Duplicates are removed, and timestamps are standardized to ensure consistency in data analysis.

Standardize Timestamps and Address Formats
------------------------------------------
Timestamps are converted to a consistent format, and address formats are standardized.

Exploratory Data Analysis (EDA)
-------------------------------

Descriptive Statistics
----------------------
Descriptive statistics provide a summary of the numerical and categorical data.

Visualization
-------------
- Temporal Analysis: Visualizes the number of incidents per year.
- Spatial Analysis: Analyzes crime distribution across different neighborhoods.
- Category Analysis: Examines the distribution of different crime types.

Predictive Modeling
-------------------

Objective
---------
The predictive modeling aims to forecast the likelihood of being robbed and the value of items stolen in different neighborhoods.

Feature Engineering
-------------------
Features are extracted from timestamps, and categorical variables are encoded. The target variables for prediction are prepared.

Model Training and Evaluation
-----------------------------
Two models are trained and evaluated:
- Likelihood of Robbery: A Random Forest Classifier predicts the likelihood of being robbed.
- Value of Items Stolen: A Random Forest Regressor predicts the value of items stolen.

How to Run the Project
----------------------
1. Clone the repository.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Open and run the Jupyter Notebook in the repository to perform the analysis and predictive modeling.

Contributors
------------
- Pedro Quartiero (https://github.com/quArtiero)

License
-------
This project is licensed under the MIT License.
