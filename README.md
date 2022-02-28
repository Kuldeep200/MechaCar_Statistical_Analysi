# MechaCar_Statistical_Analysi
Overview of Project: Explain the purpose of this analysis.
AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. In this challenge, we'll do the following:

Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
Run t-tests to determine if the manufacturing lots are statistically different from the mean population
Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.



Linear Regression to Predict MPG
The screenshot below shows the results of producing a linear regression model to predict MPG from the MechaCar_mpg dataset using the variables of vehicle length, vehicle weight, spoiler angle, ground clearance, and AWD. Of these variables, vehicle length and ground clearance provided a non-random amount of variance to the mpg values in the dataset, as shown by their low p-values.  This model predicts the mpg of MechaCar protoypes effectively because the Adjusted R-squared reflects that ~68.25% of the variation within mpg is explained by the coefficients.

Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/93456209/155903483-57423aeb-813d-44c9-b563-6ee9b1f50f2a.png)


Summary statistics of the mean, median, variance, and standard deviation of the PSI are shown below for the suspension coils overall and for the manufacturing lots. The design specifications for the MechaCar suspension coils presure the variance of the suspension coils must not exceed 100 pounds per square inch (PSI). Based on the variance of the suspension coils in the total summary, the suspension coils overall meet the MechaCar design specifications. However, the lot summary shows that while manufacturing Lots 1 and 2 meet the design specifications and have variances under 100 PSI, Lot 3 does not meet the design specifications as its variance is much over the 100 PSI limit.

Total Summary


![image](https://user-images.githubusercontent.com/93456209/155903888-18ef3152-733a-42ea-8d65-b3b17bd0ceab.png)

![image](https://user-images.githubusercontent.com/93456209/155908888-bcb819f8-00f0-4b71-b9c0-924152109588.png)

T-Tests on Suspension Coils


  T-tests were run on the suspension coil data to determine if all manufacturing lots, and each lot individually, are statistically different from the population mean of 1,500 pounds per square inch (PSI). The results of the t-tests across all lots and each individual lot are below.
  
  ![image](https://user-images.githubusercontent.com/93456209/155909102-023bb42b-c335-4ff4-a94f-b088788bd8a8.png)

Three Smaple Coil tests results

![image](https://user-images.githubusercontent.com/93456209/155909315-eeaa626b-a0d6-4c97-8070-e27aa8ec2870.png)
![image](https://user-images.githubusercontent.com/93456209/155909396-75a26700-39a5-4c3d-80bb-c07ed998769a.png)

 ## Study Design: MechaCar vs Competition.
 
 Mostly people would like to consider cost, city or highway fuel efficiency and horse power when they purchase a car.
 
## hypothesis


Null hypothesis would be all variables from city or highway fuel efficiency and horse power does not have impact on the cost of car. Alternate hypothesis: all or some of the variable have impact on the cost of car.



What data is needed to run the statistical test?


We need fuel efficiency both from city and highway, horse power and the cost of a car. 


 


