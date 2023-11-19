# Flight-Price-Prediction-EDA
# Overview
Implemented a comprehensive data preprocessing pipeline for a Flight Price Prediction project using Python, Pandas, and Scikit-Learn.
# 1. Data Exploration and Feature Engineering
Merged training and testing datasets for a holistic analysis.
Extracted insightful features like Date, Month, Year, Arrival Hour, Arrival Minute, Departure Hour, and Departure Minute.
# 2. Handling Date and Time
Engineered features from 'Date_of_Journey', 'Arrival_Time', and 'Dep_Time'.
Converted data types for enhanced computational efficiency.
Dropped unnecessary columns to streamline the dataset.
# 3. Processing Stops and Route Information
Mapped 'Total_Stops' to numerical values for easy interpretation.
Dropped 'Route' column, extracting relevant information from 'Total_Stops'.
# 4. Label Encoding
Applied Label Encoding to categorical features such as 'Airline', 'Source', 'Destination', and 'Additional_Info'.
Transformed categorical data into numerical form for machine learning compatibility.
# 5. Dummy Variable Creation
Utilized one-hot encoding through pd.get_dummies for categorical columns.
Created dummy variables to enhance model performance.
# 6. Data Transformation
Prepared the dataset for model training, ensuring all features are in numerical format.
