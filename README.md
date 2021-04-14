# Case_Study 
Author - Aayushi Rai
Date - 14th April 2021

## Overview:
    This Case Study deals with the Regression problem to predict the variable G3 from the given datasource.

## Files in the Folder
ipynb - it is the solution file for the Datasets to predict the target variable G3
dataset - there are two datasets - student-por.csv, student-mat.csv

#### Dataset
#### This project is meant to explore, analyse, visualize and predict the sales of the store:
      1. school
      2. sex 
      3. age 
      4. address 
      5. famsize
      6. Pstatus
      7. Medu
      8. Fedu
      9. Mjob
      10. Fjob 
      11. reason
      11. guardian
      12. traveltime 
      14. studytime
      15. failures 
      16. schoolsup 
      17. famsup 
      18. paid 
      19. activities 
      20. nursery
      21. higher
      22. internet 
      23. romantic
      24. famrel 
      25. freetime 
      26. goout
      27. Dalc
      28. Walc 
      29. health 
      30. absences 
      31. G1 
      32. G2 
      33. G3 -- Target Variable
      
#### Machine Learning Steps Follwed to acheve the objective.
    1. Import necessary Libraries
    2. Read the csv dataset
    3. Check for the null values and the unwanted values in the dataset
       - We checked for the null values and unwanted values in the dataset there were none.
    4. Preprocesss data to convert categorical columns into numeric ones 
    5. Scale the data to bring it to the normal distribution
    6. Train Test Split the dataset.
    7. Create a Linear Regression model.
    8. Performance of Train data
       - RMSE - 1.4948541
    9. Performance of Test data
       - RMSE - 1.636

#### How to use.
    Please download the dataset and ipynb files and run the files in using jupyter notebook in anaconda.
    Ensure to keep the ipynb files and the dataset files in the same folder else please update the path for the same in pd.read_csv file.
