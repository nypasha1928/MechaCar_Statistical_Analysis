# MechaCar_Statistical_Analysis

# Multiple Linear Regression to Predict MPG

#### This simple had a dependent variable of (mpg) and five other independent variables (vehicle_length,vehicle_weight,spoiler_angle,ground_clearance,AWD). Since there was no feature selection in this model we will see that some variables are less relevant to include in the model.

For the overall model, we see that we have a R-squared of .7149 which mean that this model with our given dataset, our five independent varibles can explain about 70% of what determines (mpg). Which in general, is a satisfactory model to use. This model can be improved by simply including more effective varibles to explain our dependent varible (mpg) through data collection.

No, our model does not have a slope of zero since the relationship between our Y and our intercept does not equal zero. Our alternative hypothesis says that our intercept does not equal zero which is true.

### Independent Variable Analysis:

    1. vehicle_length
         P-value of about 0 shows that it is statistically significant in this model.
    2. vehicle_weight  
         P-value of .0776 shows that it is statistically significant to include in this model only at the .1 alpha level.
    3. spoiler_angle  
         P-value of .3069 shows that it is not statistically significant at any alpha level. Therefore not worth to include in this model.
    4. ground_clearance
         P-value of .3069 shows that it is not statistically significant at any alpha level. Therefore not worth to include in this model.
    5. AWD   
         P-value of .1852 shows that it is not statistically significant at any alpha level.
### SUMMARY STATISTICS

![image](https://github.com/nypasha1928/MechaCar_Statistical_Analysis/blob/main/images/SUMMARY%20STATISTICS.png)
         
### T-Tests on Suspension Coils
#### In this section, I tested a general population mean of 1500 against the different Manufacturing Lots in the data set. Now, population means can never be known but just for this case there is one in place to gather some insight on pounds per square inch per Lot. Let see if the lot are statistically significant/ different from the predetermined population mean of 1500.

### Lot1 vs PopMean

![image](https://github.com/nypasha1928/MechaCar_Statistical_Analysis/blob/main/images/Lot1%20vs%20PopMean.png)

#### From this test and with a p-value of 1 , this is not statitically signifcant since we do not have enough evidence to reject the null hypothesis, thus these two numbers are statistically similar.

### Lot2 vs PopMean

![image](https://github.com/nypasha1928/MechaCar_Statistical_Analysis/blob/main/images/Lot2%20vs%20PopMean.png)

#### From this test and with a p-value of 0.6072, this is not statitically signifcant since we do not have enough evidence to reject the null hypothesis, thus these two numbers are statistically similar.

### Lot3 vs PopMean

![image](https://github.com/nypasha1928/MechaCar_Statistical_Analysis/blob/main/images/Lot3%20vs%20PopMean.png)

#### From this test and with a p-value of 0.04168, this is not statitically signifcant since we do not have enough evidence to reject the null hypothesis, thus these two numbers are statistically similar.


## Study Design: MechaCar vs Competition

#### I would perform a ANOVA test since I want to use the means of a continuous numerical variable across a number of groups. I would test between the different categorical cars(SUV, sports car, Pickups) and use a single dependent varibale of (MPG) across these groups and compare it against the competition to try and convince a consumer that there is a statistical difference between MechaCar and Non-MechaCars products. I would just need the data on all the SUVs, sports car and pickups models mpg for my picked competition and MechaCars. We want to reject our null hypothesis that there is not a difference between the two groups (MechaCars and Competition) and accept our alternative that there is a difference between the two groups. With ANOVA the tests are done individually so some car types my or may not be statistically significant.

