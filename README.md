# Systemic Crisis Prediction in African Countries

## Overview
The "Systemic Crisis Prediction in African Countries" project aims to predict the likelihood of systemic crises (including banking, financial, and inflation crises) in selected African countries using historical economic data from 1860 to 2014. By analyzing key indicators such as annual inflation rates and exchange rates, this project provides valuable insights for policymakers and stakeholders interested in economic stability.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Evaluation Metrics](#evaluation-metrics)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation
To run this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/systemic-crisis-prediction.git
cd systemic-crisis-prediction
pip install -r requirements.txt
``` 


## Dataset
The dataset used in this project is sourced from Kaggle and contains various economic indicators for 13 African countries, including Algeria, Angola, and Nigeria. Key columns include:

country_number                     
country_code                       
country                            
year                               
systemic_crisis                    
exch_usd                           
domestic_debt_in_default           
sovereign_external_debt_default    
gdp_weighted_default               
inflation_annual_cpi               
independence                       
currency_crises            
inflation_crises           
banking_crisis      

## Exploratory Data Analysis
During the EDA phase, the following tasks were performed:
Summary statistics were generated to understand the dataset's distribution.
Inflation trends and exchange rates were visualized using libraries such as Matplotlib and Seaborn.

## Modeling
This project employs a machine learning model to predict the likelihood of systemic crises. The algorithm implemented was:
Decision Tree Classifier

## Evaluation Metrics
Model performance was assessed using the following metrics:
Accuracy: The proportion of correctly predicted instances out of the total instances, indicating the overall effectiveness of the model.
Confusion Matrix: A table used to evaluate the performance of a classification model by comparing the actual versus predicted classifications, showing true positives, false positives, true negatives, and false negatives.
Classification Report: A summary of key classification metrics, including precision, recall, F1 score, and support for each class, providing a detailed view of the model's performance.
F1 Score: The harmonic mean of precision and recall, providing a balance between the two metrics and useful for imbalanced datasets where false negatives and false positives have different costs.
ROC AUC (Receiver Operating Characteristic Area Under Curve): A metric that quantifies the ability of a classification model to distinguish between classes, with a value ranging from 0 to 1, where 1 indicates perfect separation and 0.5 indicates no separation.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request. Contributions, feedback, and suggestions are welcome!

## License
This project is licensed under the MIT License - see the LICENSE file for details.

