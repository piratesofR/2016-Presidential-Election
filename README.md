# 2016-Presidential-Election
This study uses supervised machine learning models to explain the share of votes for the Republican Party 
in the 2016 Presidential Elections with demographic data on county level. The data comes mainly from the U.S. Census Bureau. 
Using campaign promises and media coverage on election demographics, we developed 11 hypotheses, which we tested on two linear 
regression models, a regression tree and a random forest. We found that lower population density, higher percentage of the
population holding bachelor’s degrees, larger share of white population and more workers in labor-intensive industries increase 
the share of votes for the Republican Party. Based on the models’ R-squared, we found that the results from the second linear 
regression model and the random forest are valid, while the outcome from the first regression model and the regression tree is not.

1. The files "regression_data_v4.csv", "Variables_v9_raw.csv" and the markdown document need to be in the same folder.  
2. Put all files beginning with "cb_2015_us_county_500k" in a folder called "Geospatial Data" and put that folder in the folder where you saved the csvs and the markdown document.  
3.Set the working directory in R to that folder.   
4.Run the model.  
