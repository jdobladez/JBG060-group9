# South Sudan Project 

Welcome to our repository, housing the culmination of our efforts in response to the challenge presented by the Zero Hunger Lab (ZHL) within the framework of the JBG060 class. Our mission was to enhance ZHL's approach to developing a predictive model for anticipating food crises in South Sudan, leveraging news articles as a key feature. In the following section you will find a description of each notebook's purpose.

## File Descriptions
| File Name | Description |
|--|--|
| topic_modelling.ipynb | Contains our exploration into topic modeling using BERTopic |
| guided_topic_modeling.ipynb | Contains our implementation of topic modeling using a guided learning approach with seed topics |
| Assylum Seekers.ipynb | Contains the exploration of data on refugees coming in, going out and internally displaced in South Sudan | 
| openai_sentiment.ipynb | Our brief exploration of implementing sentiment analysis using ChatGPT |
|logistic_regression.ipynb|Contains the Regularized Logistic Regression model and plot regarding number of occurrences|
| RFC_RFR_GBR.ipynb | Contains the Random Forest Regressor, Random Forest Classifier, and Gradient Boosting Regressor and plots on performance and overfitting|
| oil_data_plots.ipynb | Contains our exploration on oil production, consumption, revenue, and usage in South Sudan 
| missing_data_exploration.ipynb | Explores the trends & distribution of missing IPC data on a quarterly basis; IPC correlation with other food crisis variables; Food_price_index exploration across regions and years; Implementation of KNN imputation test |
| reg_imputation.ipynb | Implements and evaluates the Regression Imputation method using the data file food_crises_updated.csv on each of the 3 administrative regions separately and on a quarterly basis over the years, starting 2009. Additionally, checks for changes in district and population dynamics over the years and then implements IPC Generalization over administrative regions using 2 weighted mean approaches - population wise weights, population density wise weights. |


## Requirements
To install the requirements open Terminal (macOS)/Command Prompt (Windows) and run pip install -r requirements.txt. If you create a new environment in PyCharm, an icon should appear to install requirements. The code runs with Python 3.12.
