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
- <img width="960" alt="d1" src="https://user-images.githubusercontent.com/76264061/114311354-0e7e4080-9b0c-11eb-9a8d-b65bbc902aa2.png"> and 
- <img width="960" alt="d1 1" src="https://user-images.githubusercontent.com/76264061/114311308-de36a200-9b0b-11eb-9c95-b44a0c581b36.png">  
