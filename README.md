# MechaCar Statistical Analysis Using R

## Objective

AutosRUs has tasked my team to review the new MechaCar as it has been suffering from production troubles. We will analysis the current data to see if we can assist the production team on where the issues occur. 

## Statitical analysis techniques:
  - Linear regressions for mpg
  - PSI review on summary statistics
  - T-tests to see if the manufacturing lots differ from the mean
  
## Linear Regression to Predict MPG

### Linear Regression Results



### Summary of Linear Regression Results



### Analysis Review

**Which variables/coefficients provided gave a different dataset?**

vehicle length and ground-clearence are likely to add non-random variance to the MechCar, whic effects the MPG.

**Is slope on linear model considered to be zero, explain?**

Looking at the regression of the slope, the p-value is 5.35e-11. Meaning that the slope is not 0. 

**Linear model predict mpg of MechaCar prototypes effectively, explain?**

The adjusted R-squared value is .6825, which makes this statistically more so than not able to predict the MPG of the MechaCar.

## Summary Statistics on Suspension Coils

### Total Summary

### Lot Summary


### Analysis Review

**The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?**

Upon review of the Total Summary informaiton the variance is well below the need 100 PSI as dicatated by manufacturing standards. However, when the lots are sorted by their own Lot 3 is 70 PSI off. 

## T-Tests on Suspension Coils

### All Lots T-Tests


### Lot 1


### Lot 2


### Lot 3


### Summary of T-Tests

All Lots analysis you can see that the p-value is 0.06, this is higher than the common significance of 0.05. The mean of the three lots are statisically similar. Especially, when compared to the estimated population mean of 1,500.

Lot 1 - has a mean of 1,500 and a p-value of 1. This lot is matching what is expected from the population. 

Lot 2 - has a mean of 1,500 and a p-value of .60. This lot is statistically similiar to Lot 1

Lot 3- has a mean of 1496 and a p-value of .42. This lot, which has been shown in other statistical reviews, is statistically different than the other two lots. 

## Study Design: MechaCar vs Competition

With total MPG for MechaCar being good, how does this compare to those of its competitors? If that data can be gathered, then a review can be done on MPG by AutosRUs on any competitor. With gas being close to $5 per gallon (June 2022) this will be an important factor for purchasing of a vehicle. 

**Metric**
  - MPG from Competitor and MechaCar (Dependant)
  - Type of Engine (Independant)
  - Type of Drive Train: 4x4 or 2x4 (Independant)
  - Hybrid Capabilities (Independant)
  - List could go on about features that effect the engine
  
  **Hypothesis**
  
  Null: MechaCar's MPG is competitive based on its features and performance
  
  Alternative: MechaCar's MPG is not competitive against its rival car makers based on ites features and performans
  
  **Testing**
  
  - T-tests of car models
  - Linear regressions
  - Visuals, such as box plots and scatter plots to see comparisons
  




