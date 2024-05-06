# Deadwood Prediction with Simple Water Balance Model

Aim of this project is, to include the Simple Water Balance Model (Source) in order to improve the deadwood prediction. 

The calibration for the Simple Water Balance Model was done for Germany in the following repository: 
https://github.com/JohannaTrost/MSC24-WBM/tree/main

The final paramenter combination for the model is found in the final_model.py script. 

Workflow for the project: 
1. Analyse water balance evolution for the Harz region
2. Show significance of soil moisture
3. Implement a machine learning model (Autogluon) with soil moisture as a predictor.
4. Further predictors can be included: soil data, NDVI, LAI, climate data

