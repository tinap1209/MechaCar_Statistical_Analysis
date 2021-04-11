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
In Deliverable 2 we had to statistically calculate the mean, median and variance and were also asked to summarise the same based on manufactiring lot in the suspension coil datasets.  

- Below are the tables that shows the Summary Coil depecting the mean, median and variance and the Manufacturing lot summary. From the Summary coil table you can infer that    the mean and the median values are close, by which the interpretation is that the data is normally distributed.
 <img width="700" alt="d2 1" src="https://user-images.githubusercontent.com/76264061/114313040-80f21f00-9b12-11eb-9a10-bebe6ac90385.png">
 <img width="700" alt="d2" src="https://user-images.githubusercontent.com/76264061/114313053-8cdde100-9b12-11eb-8eee-eff39440aeda.png">
- the Summary coil table indicates a large standard deviation. A large standard deviation indicates that the data points are far from the mean, and a small standard deviation   indicates that they are clustered closely around the mean.
- If the significance level of 0.05 percent, the p-value (0.06028) is above our significance level. The data is considered to have normal distribution. 
