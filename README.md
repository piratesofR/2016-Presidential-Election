# 2016-Presidential-Election
This study uses supervised machine learning models to explain the share of votes for the Republican Party 
in the 2016 Presidential Elections with demographic data on county level. The data comes mainly from the U.S. Census Bureau. 
Using campaign promises and media coverage on election demographics, we developed 11 hypotheses, which we tested on two linear 
regression models, a regression tree and a random forest. We found that lower population density, higher percentage of the
population holding bachelor’s degrees, larger share of white population and more workers in labor-intensive industries increase 
the share of votes for the Republican Party. Based on the models’ R-squared, we found that the results from the second linear 
regression model and the random forest are valid, while the outcome from the first regression model and the regression tree is not.

Find the published document on Rpubs: http://rpubs.com/JohanSt_R/277762

The goal of this github page is to make our research reproducible. Please feel free to play with the data and the models and suggest improvements! To import the data and the report into R, please follow these steps:

1. The files "regression_data_v4.csv", "Variables_v9_raw.csv", the folder "Geospatial Data" and the markdown document "	groupwork_markdown_v11.Rmd" need to be in the same folder
3. Set the working directory in R to that folder
4. Install packages "knitr" and "rmarkdown", as well as dependencies
5. Install all packages specified in the markdown document
6. Run the model.  

If you have any questions, add our wechat accounts! You find us in the class wechat group

Introduction to rmarkdown: http://rstudio-pubs-static.s3.amazonaws.com/202429_acbbe794b27f4dffaac6047d1b6d5aa0.html
