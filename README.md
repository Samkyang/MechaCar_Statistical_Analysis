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

## T-Tests on Suspension Coils

To determin wheter there is a statistical difference between the mean of this dataset and the hypothesized dataset we have to conduct a t-test with a population mean of 1500. 

This is the summary of the t-test for all of the lots manufactured.
![T Test_All](https://user-images.githubusercontent.com/92561003/153348355-b481ff06-d722-4a73-b728-2f4ac46a973e.png)

The p value is 0.06 which is higher than 0.05 which means there is not enough evidence to regject the null hypotheseis.

When we look at the lots individually we see for lot1:

![t test_lot1](https://user-images.githubusercontent.com/92561003/153348358-98e0916a-f518-4c67-b1a5-400cc6602458.png)
lot1 has a pvalue of 1 so we cannot reject the null hypothesis.


![t test_lot2](https://user-images.githubusercontent.com/92561003/153348360-fe639b9c-d5aa-4f51-841e-d7ea36d479ef.png)
lot2 has a pvalue of 0.6072 so we cannot rejeect the null hypothesis.


![t test_lot3](https://user-images.githubusercontent.com/92561003/153348362-cc57f7b5-ba5d-44bc-8cf9-fe53c7c4ca08.png)
lot2 has a pvalue of 0.04168 which is lower than 0.05 so the PSI for lot3 is statisticall different than the population mean.

## Study Design: MechaCar vs Competition









