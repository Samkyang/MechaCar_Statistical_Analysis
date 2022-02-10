# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![Screen Shot 2022-02-06 at 11 29 32 PM](https://user-images.githubusercontent.com/92561003/152743909-e288e83a-a747-4c39-bafc-bbf3f95f6e90.png)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
looking at the Pr(>|t|) column we want to find which will indicate a non-random amount of variance to the mpg. Vehicle length and ground clearance are two variables 

Is the slope of the linear model considered to be zero? Why or why not?
The p-value is 5.35e-11 which smaller than the 0.05% significance level so it is no zero.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
the linear model does predict the mpg because the R-squared number is 0.7149 so 71.49% of the predictions can be made with these models.

## Summary Statistics on Suspension Coils

We first look at all of the suspension coils manufactured and can see the following stats:


![Total_summary](https://user-images.githubusercontent.com/92561003/153340332-b573345a-4aa7-486f-81d3-a687fe145b2e.png)

Then we break it down and group the coils by the manufacturing lot and see:


![lot_summary](https://user-images.githubusercontent.com/92561003/153340346-c30bed54-29d7-46a3-a2e2-f753f57e9dcd.png)

The company provides regulations that the PSI variance cannot exceed 100psi. As a whole the coils would pass, but in manufacturing things are looked at on a lot level. With this in mind only lot1 and lot2 pass, lot3 does not pass.

