Predicting Obesity Using DASL Dataset
=======================================

Task
-------------------
DATA2002 Module 4 Report

July 2019 - November 2019

Description
-------------------
Excess weight, especially obesity, has become an epidemic in the 21st century. This study aims to investigate an alternative method to determine “overweight” individuals oppose to body fat percentage. Two alternative indicators are considered - BMI and body density. The results showed that BMI can be explained the best using simple body measurement and the measurement on abdomen is the most important predictor in estimating all three methods. A simpler predictive model for obesity has been developed using measurements on chest, abdomen and bicep. Limitations and implications are discussed.

Conclusion
-------------------
Through multiple regression and variable selection, a fitted model with solely body measurements was determined for each of the three obesity indicators. Using R2, BMI was identified as the best indicator as it has the highest proportion of variance that can be explained using only body measurements.

Abdomen was the most important body measurement for determining obesity because for all three indicators, it ranked the highest in terms of relative importance in prediction.

By separating the dataset with the binary variable for over-weight individuals, a simplified prediction model with 92% accuracy was built. The simplified model contains three body measurements - chest, abdomen and thigh, and should be relatively simpler to measure.

Challenges & Learning Points
-------------------
1. Analysis cannot be applied to whole population
   - gender bias (only men)

2. Multicollinearity - Variables waist (dropped) and abdomen are highly correlated

3. Using multiple regression to determine which variables to drop in order to attain the final fitted model

4. Using binary logistic regression to interpret relationship between overweight and other significant variables

Files
-------------------
1. DATA2002_Module_4_Report.html
   - Contains main R code and our study findings

2. presentation.html
   - 27 page slides created using xaringan

3. Executive_Report.html
   - A professional 3-page report in the form of a pinp document
