# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The linear regression model shows that the 

* vehicle_weight 0.0776 p-value
* spoiler_angle 0.3069 p-value
* AWD 0.1852 p-value
variables show non random effect on the mpg values. Higher p-value shows no-random amount of variance. Compare withe the Vehicle Length with p-value of 2.60 x 10-12(= 0.00000000000206) and the variable Ground Clearance with p-value of 5.21 x 10-8 (= 0.0000000521). Such small p-values show random amount of varience.

* Is the slope of the linear model considered to be zero? Why or why not?
It is not considered to be at zero, because the p-value of this linear reqression is 5.35 x10 -11(= 0.0000000000535), which is much smaller then the assumed statistical significance level of P <0.05.

* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
With the Multiple R-squared at 0.7149 (71%) it shows that this model would not predict mpg of MechaCar prototypes effectively.  

![](images/delivarable1.PNG)
 
## Summary Statistics on Suspension Coils
* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

![](images/delivarable2totalsummary.PNG)
![](images/delivarable2lotsummary.PNG)

## T-Tests on Suspension Coils
* Summarize your interpretation and findings for the t-test results
![](images/delivarable3.PNG)


## Study Design: MechaCar vs Competition
* What metric or metrics are you going to test?
* What is the null hypothesis or alternative hypothesis?
* What statistical test would you use to test the hypothesis? And why?
* What data is needed to run the statistical test?
