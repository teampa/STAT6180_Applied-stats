# STAT6180_Applied-stats
# Traffic Congestion and Chocolate Cake Quality Analysis - Applied statistics assignment

## Description
This repository contains two major projects conducted as part of applied statistics unit at Macquarie University.

### Traffic Congestion Analysis
The first project focuses on analyzing traffic congestion in a U.S. metropolitan area using the `traffic.csv` dataset. It involves exploring variables like Speed Performance Index (SPI), Public Transportation Accessibility, Road Capacity Index, Weather Severity Index, Fuel Price, and Average Wind Speed. 

#### Key Findings:
- **Correlation Analysis**:
  - Weather: A strong positive correlation with SPI (r = 0.667), suggesting that worsening weather conditions correlate with increased traffic congestion.
  - Transport: A moderate negative correlation with SPI (r = -0.473), indicating that improved transport facilities might lead to decreased SPI.

- **Regression Model**:
  - The model indicates that with every one index value increase in weather, SPI increases between 3.35 and 5.14 units on average, holding other predictors constant.

- **F-Test for Overall Regression**:
  - Statistical Conclusion: The test rejects the null hypothesis at a 5% significance level, indicating a significant linear relationship between SPI and at least one predictor.
  - Model Validation: The analysis suggests a linear relationship between predictors and SPI. However, deviations in the residuals indicate potential skewness or outliers, affecting the model's predictions.

- **Model Effectiveness**:
  - Full Model (M1): R² = 74%, Adjusted R² = 71.74%.
  - Final Model (M3): After removing wind and fuel predictors, R² = 72%, Adjusted R² = 71.14%. The final model retains nearly the same explanatory power with fewer predictors, indicating the robustness of significant predictors.

### Chocolate Cake Quality Analysis
The second project investigates the impact of recipe and baking temperature on the breaking angle of chocolate cakes using the `cake.csv` dataset. 

#### Key Findings:
- **Experimental Design Analysis**:
  - Conclusion: The design is balanced, as every combination of 'Recipe' and 'Temp' has an equal number of observations.

- **Preliminary Graph Analysis**:
  - The interaction plots suggest non-parallel lines, indicating a potential interaction effect, which necessitates further analysis.

- **Full Interaction Model**:
  - Analysis reveals no significant interaction between Recipe and Temperature on the breaking angle, as indicated by a p-value greater than 0.05 for the interaction term.

- **Effect of Recipe and Temperature**:
  - Recipe Effect: The p-value (0.0140636) suggests a statistically significant effect of the recipe on the breaking angle.
  - Temperature Effect: The p-value (0.000196) indicates a statistically significant effect of baking temperature on the breaking angle.
  - Conclusion: Both recipe and baking temperature independently have a significant impact on the breaking angle of the cake.

## Data Source
- `traffic.csv`: Data on traffic congestion in a U.S. metropolitan area.
- `cake.csv`: Data on chocolate cake breaking angles based on different recipes and temperatures.

## Technologies
- R Language
- R Libraries: `ggplot2`

## Installation and Usage
(Instructions on setting up R and running the analysis script for each study.)

## License
This project is for academic purposes and is not licensed for commercial use.

## Contact
For inquiries or collaborations, contact:
- Parinya Sodsai
- Email: parinya.ssai@gmail.com
- LinkedIn: https://www.linkedin.com/in/parinya-sodsai-70b66b18b/
- GitHub: https://github.com/teampa
