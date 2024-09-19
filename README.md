# TP2: Predicting Ozone Concentration Using Multiple Linear Regression  
*Master 1 in Modelisation Statistique Project*  
Université Franche-Comté, Besançon (2022–2023)  

## **Project Overview**  
This project involved predicting ozone concentration using **multiple linear regression models** based on meteorological data. The dataset included variables such as temperature, cloud cover, wind speed, and ozone concentration from the previous day. The project aimed to answer key statistical questions related to model adequacy, confidence interval estimation, and bias detection.

### **Key Questions Solved**:
1. **Model Comparison**: Compared a simple model (M1) using temperature at noon (T12) as a predictor with a more complex model (M2) that included variables like wind speed (Vx), cloud cover at noon (Ne12), and the previous day’s maximum ozone level.
2. **Model Adequacy**: Assessed whether both the simple and multiple models provided a good fit and if the predictor variables significantly explained the ozone concentration.
3. **Confidence Intervals**: Calculated confidence intervals for each regression coefficient and visualized these using **confidence ellipses**.
4. **Unbiasedness of Estimators**: Conducted simulations by drawing 10,000 random samples from the dataset to verify that the estimators for the coefficients were unbiased.
5. **Bootstrap Confidence Intervals**: Applied bootstrap methods to estimate confidence intervals, particularly when sample size is small, and the normality assumption might not hold.

## **Project Files**:
- `TP2NEW2.Rmd`: R Markdown file containing the full analysis and code.
- `index.html`: Rendered HTML report showing the results of the analysis.
- `data/`: I can not share the data, but the name is ozono, maybe you can find it in internet. 

## **R Packages Used**:
- `lm()`: For fitting linear regression models.
- `ellipse`: For visualizing confidence ellipses.
- `bootstrap`: For applying bootstrap methods to estimate confidence intervals.
