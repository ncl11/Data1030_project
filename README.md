# Forecasting NYC Public School Graduation Rates
### Project Overview
For this project we use the “2005-2010 Graduation Outcomes - School Level" dataset from NYC OpenData to build a model which predicts graduation outcomes for each subsequent year.  This model could be very useful for resource allocation purposes for the city.  In the src directory there are four notebooks- "data_cleaning_&_preprocessing", "EDA", "model_training & splitting" and "grad % project_master".  For a detailed report on the project and breakdown of the notebooks please see the report folder.  

### Language, Packages and Data
**Language:**  Python verion 3.7.8    
**Packages:** numpy version 1.18.5, matplotlib version 3.2.2, sklearn 0.23.1, pandas version 1.0.5, xgboost 1.1.1  
**Data:** https://data.cityofnewyork.us/Education/2005-2010-Graduation-Outcomes-School-Level/vh2h-md7a  

### Selections from EDA and model_building Notebooks
Below are a few selections from EDA, a chart of performances of each model tested and some plots relating to the performance of our best model.  The true vs pred plot and feature permutation plot are based off a SVM model with hyperparameters: kernel='rbf', gamma=0.0001220703125 and C=128. 
<img src="Figures/gradperc.png" width="400">
<img src="Figures/LinePlot.png" width="400">
<img src="Figures/regentsvsy.png" width="400">
<img src="Figures/modeldf.png" width="400">
<img src="Figures/truevpred.png" width="400">
<img src="Figures/svr_feature_perm.png" width="400">
