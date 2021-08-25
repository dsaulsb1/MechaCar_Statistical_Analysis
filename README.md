# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/82469032/130708820-47d5eb43-37c8-4c2d-b336-d8e7f8f3ba8c.png)

### Answers
-Variance of a non-random variable is normally 0. Given this, the intercept, vehicle_length, and ground_clearance coeeficients provide a non-random amount of variance to the mpg values.
-At a significance level of 0.05, we can reject the null hypothesis because of the extremely small p-value. Thus, proving that the slope is not 0.
-Multiple R-squared increases as more variables are passed through the regression. However, adjusted R-squared controls against this increase, and adds restrictions for the number of predictors in the model, thus making it the more accurate predictor of how effective the linear model is. The adjusted R-square here concludes that this linear model predicts the mpg of MechaCar prototypes pretty well.

## Summary Statistics on Suspension Coils

![image](https://user-images.githubusercontent.com/82469032/130709641-7610ee49-e311-4d38-bb74-9bc283b1eb88.png)
![image](https://user-images.githubusercontent.com/82469032/130709653-567c4ac9-a363-4d22-b4c9-ff164cca8d97.png)

### Answers

-The overall variance for the entire dataset indicates that the current manufacturing data meets the 100 pounds per square inch variance limitation, but that doesn't give the full story. When separated into three lots, the third lot shows a much higher variance. With the lots being chosen randomly, there is a possiblity that a third of the lot does not meet the necessary requirement.

## T-Tests on Suspension Coils

![image](https://user-images.githubusercontent.com/82469032/130709919-fba99f3a-f9ea-4b34-97ec-4ee92ef1fef6.png)

### Answers

-Lot 1. At a significance level of 0.05, we fail to reject the null hypothesis since the p-value equals 1. 
-Lot 2. At a significance level of 0.05, we fail to reject the null hypthesis again since the p-value equals 0.6072.
-Lot 3. At a significance level of 0.05, we can reject the null hypothesis since the p-value equals 0.04168.

## Study Design: MechaCar vs Competition

Another study that could be performed to determine is an analysis on fuel efficiency. Possibly a linear regression analysis on the differences between city and highway fuel efficiency. I predict a null hypothesis highway mpg and none for city driving. for The following metrics can be included:

-City/Highway fuel efficiency
-Vehicle Statistics (type/weight)
-Miles per gallon.
