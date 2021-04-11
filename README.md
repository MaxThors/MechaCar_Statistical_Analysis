# MechaCar_Statistical_Analysis
Using R for vehicle analysis

## Linear Regression to Predict MPG
According to our summary, when we look at the Pr(>|t|) values, the variables for vehicle length and ground clearance in addition to the intercept (MPG), are statistically unlikely to provide random amounts of variance to the linear model. The slope of the linear model is not considered to be zero because the p-value of 5.35e-11 is much smaller than our assumed significance level of 0.05%. We can now say that there is enough evidence to reject our null hypothesis and conclude that the slope of our inear model is not zero. Looking at the r-squared value and p-value, we can conclude that the model is effective in predicting the mpg of MechaCar prototypes.

## Summary Statistics on Suspension Coils
If you look at the total summary of all the lots, the variance is 69.3 pounds per square inch (PSI) . This is comfotably under the 100 PSI threshold. When you look at the lot summary the variance is 1.0 PSI and 7.5 PSI for lots 1 and 2, respectively. However, when you look at lot 3 the variance is 170.3 PSI which is well above the 100 PSI maximum. So, in conclusion, the vehicles in lot 3 do not meet the design specification, but all of the other lots do.
