# Machine Learning & Data Analysis  
**21.02.2025 Luzern**  

This project was motivated by my ÜK grade, which suffered due to a misunderstanding—I built two models for two problems instead of one. My teachers were strict with their feedback, pushing me to prove myself again. Additionally, I took on this challenge out of personal interest.

---

## Contents
- [How to Download](#how-to-download)
- [Usage](#usage)
- [Documentation (PDF)](#documentation-pdf)
- [Python Notebook (ipynb)](#python-notebook-ipynb)

---

## How to Download

To download the project, use the following command:
git clone <repository link>


After downloading, follow the instructions below to use the project.

---

## Usage

### Documentation (PDF)
The Documentation contains:
- **EDA** (Exploratory Data Analysis): This is the process of analyzing and summarizing a dataset to understand its key characteristics before applying machine learning models or statistical methods. It helps detect patterns, spot anomalies, and check assumptions using visualizations and summary statistics.
  
- **Hypotheses**: This study explores three hypotheses related to physical performance, body composition, and age-related health indicators. Using data analysis, correlation matrices, and machine learning models, the study explores the relationships between grip strength, body fat percentage, flexibility, and blood pressure.

- **Models**: Different machine learning models, including Random Forest, XGBoost, and Voting Classifiers, were used to test the accuracy of predictions such as gender and physical fitness. A Linear Regression model was created to analyze the relationship between age and blood pressure.

- **Summary**: The models provide valuable insights. For instance, the first model confirms that flexibility is a stronger predictor of physical fitness than body fat percentage. The second model showed a strong correlation between gender and grip strength. The third model revealed that age alone is insufficient to predict blood pressure accurately. While the results varied across models, they offer valuable conclusions for understanding the data and building accurate predictions.

### Python Notebook (ipynb)
#### Description:
This project analyzes world economic indicators and uses machine learning models to predict GDP growth based on features such as unemployment rates and GDP. The data contains various indicators from 1960 to 2022 for countries around the world, and we use these features to train and test different models. The notebook provides the full analysis process from data cleaning and preprocessing to model training and evaluation.

#### Usage:

1. **Data Preparation**:  
   The `world_economic_indicators.csv` file contains economic data. In this project, data cleaning was performed by handling missing values and ensuring the dataset is ready for analysis. 

2. **Data Visualization**:  
   Various graphs are generated to visualize the data distribution, trends, and correlations. These include heatmaps for correlation matrices and time-series plots for GDP and unemployment trends for specific countries.

3. **Modeling**:  
   We tested multiple models such as **Random Forest Regressor**, **XGBoost Regressor**, and **Linear Regression**. These models were trained to predict GDP growth based on various economic features like unemployment rate, GDP, and GDP growth rate.

---

### Results:

- **Mean Squared Error (MSE): 1.58**  
  The Mean Squared Error measures the average squared difference between the predicted values and actual values. In our case, an MSE of 1.58 indicates that the model predictions are, on average, off by approximately 1.58 squared units from the actual GDP growth values. A lower MSE indicates better predictive accuracy, and this value suggests that the model performs reasonably well.

- **R² Score: 0.95**  
  The R² score (coefficient of determination) represents the proportion of the variance in the dependent variable (GDP growth) that is explained by the independent variables. An R² of 0.95 means that 95% of the variation in GDP growth can be explained by the model, showing a very high level of predictive accuracy and suggesting a good fit of the model to the data.

These results demonstrate the model's strong performance, with the Random Forest Regressor accurately predicting GDP growth while minimizing errors.

---

Note: You do not need to run the code anymore, as all visualizations and model outputs (such as MSE and R² scores) have already been generated and are included in the notebook. You can refer to these results directly.

---



