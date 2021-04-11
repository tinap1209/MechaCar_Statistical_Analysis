# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
- Deliverable 1 Task to be done: Using multiple linear regression, we were asked to use the miltiple linear regression function, passing all six variables MechaCar mpg dataset.
- we are also to determine the p-value and the r-squared modle for the value for the linear regression model.

### Questions to be addressed
#### 1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
#### 2. Is the slope of the linear model considered to be zero? Why or why not?
#### 3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- According to the results, vehicle length, ground clearance and Intercept have provided a non-random amount of variance to the mpg values in the dataset. It is observed that the vehicle length and ground clearance have a significant impact on the mpg. Here the expected mean value is statistically significant, which means there are other variables and factors  that contribute to the variation in mpg that have not been included in this model. These variables may or may  not be  within this dataset and may still need to be collected or observed.

- The spoiler angle, AWD and vehicle weight contributes a random amount of variance to this linear model.

- The p-value of this linear model is 5.35e-11, which is much smaller than the assumed significance level of 0.05%. Hence, it can be understood that there is sufficient evidence to reject our null hypothesis, which means that the slope  of this linear model is not zero.

- From  this linear  model, the r-squared value is 0.7149 which means that roughly 71% of all mpg predictions will be correct when using this model. So it can be inferred that this linear model predicts mpg of MechaCar prototypes  effectively.

- Refer to the below output on of the console. 
- <img width="700" alt="d1" src="https://user-images.githubusercontent.com/76264061/114311354-0e7e4080-9b0c-11eb-9a8d-b65bbc902aa2.png"> and 
- <img width="700" alt="d1 1" src="https://user-images.githubusercontent.com/76264061/114311308-de36a200-9b0b-11eb-9c95-b44a0c581b36.png">  

## Summary Statistics on Suspension Coils
For Deliverable 2 we had to statistically calculate the mean, median and variance and were also asked to summarise the same based on manufactiring lot in the suspension coil datasets.  

- Below are the tables that shows the Summary Coil depecting the mean, median and variance and the Manufacturing lot summary. From the Summary coil table you can infer that    the mean and the median values are close, by which the interpretation is that the data is normally distributed.
 <img width="700" alt="d2 1" src="https://user-images.githubusercontent.com/76264061/114313040-80f21f00-9b12-11eb-9a10-bebe6ac90385.png">
 <img width="700" alt="d2" src="https://user-images.githubusercontent.com/76264061/114313053-8cdde100-9b12-11eb-8eee-eff39440aeda.png">
- the Summary coil table indicates a large standard deviation. A large standard deviation indicates that the data points are far from the mean, and a small standard deviation   indicates that they are clustered closely around the mean.
- If the significance level of 0.05 percent, the p-value (0.06028) is above our significance level. The data is considered to have normal distribution. 

## T-Tests on Suspension Coils
 
For Deliverable 3 , one-sample t-test has been used to assert if there is a statistical difference between the means of a sample dataset The mean of the  hypothesized, potential population dataset is given as 1,500 pounds per inch. We also have to three more RScripts in  MechaCarChallenge.RScript using the t.test() function and its subset() argument to determine if the PSI for each manufacturing lot is statistically different from the population mean of 1,500 pounds per square inch. 

<img width="700" alt="d3" src="https://user-images.githubusercontent.com/76264061/114314025-b4cf4380-9b16-11eb-935e-8f7c86ed4acc.png">

- Assuming the significance level of 0.05 percent, the p-value (0.06028) is above our significance level. The data is considered to have normal distribution.Therefore, we do not have sufficient evidence to reject the null hypothesis, and we would state that the two means are statistically similar.

- Population mean for Manufacturing Lot 1 

<img width="262" alt="d3p1" src="https://user-images.githubusercontent.com/76264061/114314805-d7af2700-9b19-11eb-89bb-07d23973695d.png">

- Population mean for Manufacturing Lot 2 

<img width="315" alt="d3p2" src="https://user-images.githubusercontent.com/76264061/114314813-e39ae900-9b19-11eb-804b-0b9e045341ae.png">

- Population mean  for Manufacturing Lot 3

<img width="281" alt="d3p3" src="https://user-images.githubusercontent.com/76264061/114314832-f31a3200-9b19-11eb-93fa-d41566c107a4.png">

## Study Design: MechaCar vs Competition
The comparison data that would appeal to a consumer are the fuel efficiency, horse power, overall build,  cost of ownership, color options, reliability, inbuilt features etc. By tackling these data wisely, MechaCar can outperforms the competition.

**Milage and Fuel efficiency**

Fuel efficiency is a measure of how far a vehicle can travel per unit of fuel. We can use ANOVA tests for this purpose which is used to compare the means of a continuous numerical variable across a number of  groups. For conducting this test, mpg data of all the concerned manufacturers are required. 

*H0: All cars offer the same mileage and fuel efficiency.*
*H1: All cars do not offer same mileage and fuel efficiency.*

**Cost**

 The long-term cost of owning a car is considerably more than the actual price we pay for it. Ownership cost includes depreciation, fuel, maintenance, repairs, and insurance. The largest of these costs is depreciation - the loss in value over time. The question here is that the cost of MechaCars is less than or equal to that of other manufacturers. To compare the cost of various manufacturers we need to perform ANOVA test in which we need to have mainly cost and fuel efficiency data of all the concerned manufacturers.

*H0: Cost of all car from all the manufacturers are the same.*
*H1: The cost of all cars from all manufactureres are not the same.* 

**Color**

 Color options also play an important role for customers in car selection. The question here is that which color or colors are most opted by the customers of MechaCars. To perform the comparison of color options between various colors we need to do the statisticle analysis using the Chi-Squared Test which is mainly used for categorical variables. The chi-squared test is used to compare the distribution of frequencies across two groups.

*H0: There is no significant difference between the preference of the colors of the cars.*
*H1: There is a significant difference between the preference of the colors of the  cars.*

