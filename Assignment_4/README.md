# Assignment 4

## Hypothesis Testing and Chi-Square Test 


## Overview

This repository contains the Jupyter Notebook `Assignment_4.ipynb`, which includes Python code for conducting two statistical analyses:

1. **Hypothesis Testing for Weekly Operating Costs**
2. **Chi-Square Test for Customer Satisfaction**

The notebook provides a detailed analysis of each task using the given problem statements and data.

## Files

1. **`Assignment_4.ipynb`**: Jupyter Notebook containing the Python code and results for both the hypothesis testing and chi-square test.
2. **`chisquare_test.docx`**: Documentation for the Chi-Square Test analysis, including background, data, and objectives.
3. **`hypothesis_testing.docx`**: Documentation for the Hypothesis Testing analysis, including background, data, and objectives.

## Hypothesis Testing Analysis

### Objective

To investigate if the weekly operating costs reported by restaurant owners are significantly higher than the costs predicted by the given model.

### Problem Statement

Bombay Hospitality Ltd. operates a franchise model with a cost equation \( W = \$1,000 + \$5X \), where \( X \) represents the number of units produced in a week. Recent feedback suggests the observed weekly operating costs are higher than the model predicts.

### Methodology

1. **Hypothesis Statements**:
   - **Null Hypothesis (H₀)**: The weekly operating cost according to the model is accurate. (H₀: µ = µ₀)
   - **Alternative Hypothesis (H₁)**: The weekly operating cost is higher than what the model suggests. (H₁: µ > µ₀)

2. **Test Statistic Calculation**:
   - Sample Mean Weekly Cost : 3050
   - Theoretical Mean Weekly Cost  = 4000 
   - Standard Deviation = 125
   - Sample Size : 25



3. **Critical Value Determination**:
   - The critical value is obtained from the t-distribution with \( n-1 \) degrees of freedom at a 5% significance level.

4. **Decision Making**:
   - Compare the calculated test statistic with the critical value to decide whether to reject the null hypothesis.

5. **Conclusion**:
   - The conclusion is drawn based on whether the test statistic exceeds the critical value, indicating if the observed costs significantly differ from the model's prediction.

## Chi-Square Test Analysis

### Objective

To determine if there is a significant association between the type of smart home device purchased and customer satisfaction levels.

### Problem Statement

Mizzare Corporation has collected data on customer satisfaction for two types of devices: Smart Thermostats and Smart Lights. The goal is to assess if there's a significant association between the device type and satisfaction level.

### Methodology

1. **Hypothesis Statements**:
   - **Null Hypothesis (H₀)**: There is no significant association between the type of smart home device purchased and the customer satisfaction level.
   - **Alternative Hypothesis (H₁)**: There is a significant association between the type of smart home device purchased and the customer satisfaction level.

2. **Chi-Square Statistic Calculation**:
   - A contingency table is used to calculate the Chi-Square statistic.
   - The p-value from the Chi-Square test indicates the probability of observing the data under the null hypothesis.

3. **Critical Value Determination**:
   - The critical value is obtained from the Chi-Square distribution with the appropriate degrees of freedom at a 5% significance level.

4. **Decision Making**:
   - Compare the p-value with the significance level (alpha) to decide whether to reject the null hypothesis.

5. **Conclusion**:
   - The conclusion is drawn based on whether the p-value indicates a significant association between device type and customer satisfaction.

## Running the Analysis

1. **Ensure you have the required libraries**:
   - `numpy`
   - `scipy`
   - `pandas`

2. **Execute the Jupyter Notebook**:
   - Open `Assignment_4.ipynb` in Jupyter Notebook or any compatible environment to view and run the analysis.

3. **Review the Documentation**:
   - Refer to `chisquare_test.docx` and `hypothesis_testing.docx` for detailed explanations, problem statements, and data related to each analysis.

