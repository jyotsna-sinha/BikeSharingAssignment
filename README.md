# Bike Sharing-Linear Regression Assignment
> A US bike-sharing provider BoomBikes wants a model for the prediction of demand for shared bikes after quarantine situation ends across the nation due to Covid-19

Essentially, the company wants to understand —
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
**So interpretation is important!**

## General Information
- Business Problem :US bike-sharing provider BoomBikes wants a model for the prediction of demand for shared bikes after 
  quarantine situation ends across the nation due to Covid-19
- What is the dataset that is being used?: day.csv file


## Conclusions
- temp,yr and season_winter have gigh coefficient values hence these features are most important in 
  determining the demand
-The r2_score for both train and test model are almost same
  - r2 score for train: 0.8352749595695672
  - r2 score for test : 0.7961390438459766
-VIF values are less than 5 which is good and also there is no multicolinearity.
- R-squared is 0.835
- All VIF are in range and no Feature has high p value
- Adj. R-squared:0.832
- F-statistic:253.0 -Prob (F-statistic):3.13e-188
- We can cosider the above model , as it seems to have very low multicolinearity between the predictors
  and the p-values for all the predictors seems to be significant.
- F-Statistics value of 253.0 (which is greater than 1) and the p-value of 3.13e-188 i.e 
  almost equals to zero, states that the overall model is significant
- AIC is -975.6 ,hence the model has better fit since it less than 0




## Acknowledgements
Give credit here.
- This project is done by Jyotsna Sinha



## Contact
Created by jyotsna.official5596@gmail.com - feel free to contact me!

