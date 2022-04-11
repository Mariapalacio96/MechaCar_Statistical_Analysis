# MechaCar Statistical Analysis
## Linear Regression to predict MPG
Analysing the Pr(>|t|) column in the summary table below, it shows that the variables with no random variance are vehicle_weight, spoiler_angle and AWD.The variables with the most random variance are ground_clearence and vehicle_length.

The slope of the linear model in not considered zero because the p-values is less than 0.05 wich shows that the independent variable had a significant effect on the dependent variables.

By using the R-squared value wich is 0.7149 or 71%, we can infer that this linear model can predict mpg of MechaCar prototypes effectively.

<img width="505" alt="MechaCar_lm_2" src="https://user-images.githubusercontent.com/95391094/162837775-3385cb2a-2787-48d3-b284-aa7ea22eba9e.png">

## Summary Statistics on Suspension Coils
The current manufacturing data meets this design specifications for all manufacturing lots in total. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch and the total variance for the three lots is 62.29.

After analizing the three lots one by one, we found out that lot 1 and lot 2 meet the disign specifications with a variance of 0.98 and 7.47 respectively. In the other hand, lot 3 does not met the design specification since its variance exceds by far the design specification with 170 in variance.

<img width="327" alt="total_summary" src="https://user-images.githubusercontent.com/95391094/162838320-68489232-02e2-4b44-970e-c99d24ff4051.png">

<img width="488" alt="lot_summary" src="https://user-images.githubusercontent.com/95391094/162838374-497184fd-bdd0-4a3b-b55a-a77bfb40f2a9.png">

## T-Tests on Suspension Coils
A T-Test was run to find out if the PSI values are or are not different from the population mean. After performing this test we found ot theta the p-value for lot 1 and lot 3 are higher than 0.05 wich means that they are not different to the mean population. But, lot 2 p-value is less than 0.05 wich means that it is less than the population mean.

<img width="438" alt="PSI_LOTS" src="https://user-images.githubusercontent.com/95391094/162841039-b4a23f5c-b57b-4949-a89a-50533138fbb0.png">

### Lot 1
<img width="479" alt="PSI_Lot1" src="https://user-images.githubusercontent.com/95391094/162841084-a90ad527-e579-4511-b4ec-c7c9f54c50f5.png">

### Lot 2
<img width="486" alt="PSI_Lot2" src="https://user-images.githubusercontent.com/95391094/162841112-aec757a6-98ce-45b2-bfcf-ec1e70d9d7c3.png">

### Lot 3
<img width="488" alt="PSI_Lot3" src="https://user-images.githubusercontent.com/95391094/162841164-64d30257-81df-4ea8-b61e-0fcb48ad3819.png">

## Study Design: MechaCar vs Competition
The metrics that we would like to consider when comparing our prototype from the competitor vehicle are:
- Fuel efficency
- Cost
- Horsepower

Our null hypothesis is that the mean of the metrics that we are considering is not different from the competitors vehicle. While our alternative hypothesis is that there is actually a difference between the means.

I would perform T-Test to collect evidence to try to reject or not reject our hypothesis. To do this we would need to collect data from samples to be able to perform the test.



