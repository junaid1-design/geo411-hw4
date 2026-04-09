# geo411-hw4
This assignment focuses on running regression analysis in R using two datasets: SAT scores vs GPA, and mosquito development sites vs pupae counts.

I started by loading both datasets into R and creating scatter plots to visualize the relationships. Then I ran linear regression models using the lm() function and reviewed the output using summary() to understand the coefficients, R-squared values, and statistical significance.

For the SAT model, I looked at how well SAT scores predict GPA and interpreted the slope and overall fit of the model. I also performed a hypothesis test to check if the relationship was statistically significant.

For the mosquito dataset, I first analyzed the linear relationship between development sites and pupae. Then I removed an outlier (observation 30) to see how it affected the model. After that, I applied a log transformation and then a log-log model to improve the distribution and better understand the relationship.

Throughout the assignment, I included all plots, regression outputs, and diagnostic plots, and answered each question based on the results from R.
