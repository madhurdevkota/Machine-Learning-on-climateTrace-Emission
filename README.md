<h2>Machine Learning on Climate Trace Emission</h2>

A comprehensive analysis of the Climate Trace Emission Dataset, employing advanced techniques in data analytics, machine learning, and deep learning. The project showcased the power of geospatial analysis using Geopandas, enabling the visualization and interpretation of CO2 emissions across the United States at both raw and normalized levels. Through the development of sophisticated machine learning models, including Extreme Gradient Boosting (XGBoost) and Deep Neural Networks (DNN), the developed model was able to accurately predict CO2 emissions, with the DNN model outperforming XGBoost in terms of root mean squared error. The project also delved into model interpretation using SHAP (SHapley Additive exPlanations), providing valuable insights into the significance of various features in influencing CO2 emissions.

<br>

1. Introduction
   - Overview of the project: Data Analytics, Machine Learning, and Deep Learning on Climate Trace Emission Dataset

2. Data Gathering and Summarization
   - Automation of dataset gathering and summarization
   - Loading and preprocessing emission data from various sectors
   - Simplifying gas types and creating a summary of emissions by sector

3. Exploratory Data Analysis (EDA) and Data Visualization
   - Visualizing emission summary using stacked bar plots
   - Analyzing emission data from the power sector
   - Data cleaning and preprocessing of the power sector data
   - EDA plots for power sector emissions

4. Geospatial Analysis and Visualization using Geopandas
   - Converting power sector data into a GeoPandas DataFrame
   - Filtering CO2 emissions and creating a log-transformed emission column
   - Loading and preprocessing US state shapefile data
   - Visualizing CO2 emissions across the USA using GeoPandas and matplotlib
   - Spatial join to calculate total emissions per state
   - Normalizing emissions based on state area and population
   - Visualizing raw and normalized emission data on maps and bar plots

5. Feature Engineering and Data Preparation
   - Cleaning and simplifying the power sector data
   - Handling missing values using machine learning algorithms (Bayesian Ridge and Neural Network)
   - Visualizing missing data using missingno library
   - Feature normalization using Min-Max scaling
   - Converting categorical variables into one-hot encoded features
   - Splitting the data into training and testing sets

6. Machine Learning Modeling
   - Developing an Extreme Gradient Boosting (XGBoost) model for emission prediction
   - Training the XGBoost model and evaluating its performance
   - Interpreting the XGBoost model results

7. Model Interpretation using SHAP (SHapley Additive exPlanations)
   - Investigating the significance of features using SHAP
   - Visualizing feature importance using SHAP plots (waterfall, beeswarm, and bar plots)
   - Interpreting the SHAP plots and understanding feature impact on CO2 emissions

8. Deep Learning Modeling
   - Developing a Deep Neural Network (DNN) for CO2 emission prediction
   - Designing the DNN architecture with appropriate activation functions, number of nodes, and layers
   - Compiling the DNN using mean squared error loss and Adam optimizer
   - Implementing early stopping and model checkpointing
   - Training the DNN and saving the best model

9. Model Comparison: Deep Neural Network vs XGBoost
   - Evaluating the performance of DNN and XGBoost models using 1:1 scatterplots
   - Calculating evaluation metrics (RMSE, R-squared, MAE) for both models
   - Comparing the accuracy and performance of DNN and XGBoost models
