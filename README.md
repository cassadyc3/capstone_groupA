# capstone_groupA
This repository holds our code for Raw Materials Order Forecasting for Industrias Duero.

The codes are split into three notebooks.
The first notebook "Capstone_Group_A_rawmaterials" includes how we set up our Time Series for each raw material and some exploratory data analysis on the complete raw materials data set. This notebook also splits our dataset in to separate CSVs based on raw material and their purchase frequency.

The second notebook "Prophet_and_XGBoost_combined_Jul10" defines functions to initiate train and test splits for each raw material with 100 or more purchase points, run param grids, and initialize the model. The final cell loops the functions for all raw materials.

The final notebook "" only runs XGBoost for raw materials with less than 100 purchase points.
