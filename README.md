# Life-Expectancy-Prediction

For my STATS 101A's individual project, I applied a linear regression model in R to the WHO Life Expectancy data set I found on Kaggle to predict a nation's average life expectancy based upon a variety of demographic indicators, economic performance, and health measures. 

After conducting an exploratory analysis to find the summary statistics for all variables and their correlation, I narrowed down the scope of my project by picking a few variables as predictors that I was interested in working with and had a high correlation with the response variable, life expectancy. Then, I fitted the model to the data set and verified that all model assumptions were met. When I realized that a few assumptions were not met, like linearity and normality of the error term, I applied Box-Cox transformation to the predictors and response variable. Afterwards, I used Backward Stepwise regression and all possible subsets method to eliminate two insigificant predictors, therefore improving the statistical significant of the transformed model. In the end, my model can explain 71% of the variation in life expectancy.

To read more about my project, please feel free to check out the full report attached!
