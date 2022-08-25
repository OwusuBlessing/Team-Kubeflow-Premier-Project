# Team-Kubeflow-Premier-Project

## Objective:
Solving the issue of under-reporting cases of accident by predicting accident severity on a 3 step scale.

## Flow of Project:
Data Sourcing --> Data Preprocessing --> Model Training --> Model Evaluation --> Deployment

## Source of Data:
https://data.gov.uk/dataset/road-accidents-safety-data/resource/ceb00cff-443d-4d43-b17a-ee13437e9564

## Data Preprocessing:
LSOA of Accident Location column was dropped due to high number of missing values.
Missing values in Location_Easting, Location_Northing, Lattitude and Longitude columns were filled with their respective median.
Missing values in Time column were filled with the mode.

## Model selected for the project:
XGBoost

## Model Deployment:
Streamlit was used to deploy the model on Heroku.
https://accidentseverity.herokuapp.com

## Folders present in the project:
Images - Contains the EDA images
Input - Contains the dataset
Json_files - Contains the .json files for the app
Model - Contains the model building file
Notebooks - Contains the python notebooks for EDA of each feature, Model Selection and Feature Engineering
