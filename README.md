# ZoomCamp_Midterm_Project
## The aim of the project is to build a model that best predicts the amount of CO2 emissions per capita in different countries. To build this model, data from 2008 to 2014 by country were used. 

Indicators: 
'gdp_growth', 
'electricity_access',
'urban_population',
'population_growth',
'urban_population_growth_annual',
'live_stock_production',
'forest_area',
'renewable_energy_use',
'energy_use_kg_of_oil_per_capita',
'population_total'

**-CO2_emission_2008_13.csv and CO2_emission_2014.csv** Data from Kaggle was used to build various models (https://www.kaggle.com/datasets/atreyakatnam/co2-emission-prediction-data). This data is loaded in the project itself from my repository. Two datasets were given on the web-site, and later they were combined for a larger sample of data. 

**-notebook.ipynb** is a file with data preparation, EDA and training various models

**-train.py** is a file with the best model and testing this other model on other data

**-train&predict_bentoml** these files contains training the final model, saving it with BentoML, loading the model and serving it via a web serice. (There are two files with such name but different type, they are identical)  
