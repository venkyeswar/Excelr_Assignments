# Assignment 2

## Confidence Interval Assignment

## Overview
This assignment focuses on constructing 99% confidence intervals for the mean number of characters printed before a print-head fails. Two different methods are used: one utilizing the sample standard deviation and the other utilizing the known population standard deviation. The solutions are implemented in Python, and the detailed explanations and results are provided in accompanying documents.

## Files Included
1. **Basic_stats_2.docx**: This document contains the theoretical explanation and the step-by-step process for constructing the 99% confidence intervals using both methods.
2. **Basic_stats_2.ipynb**: This Python script contains the code used to calculate the confidence intervals. It includes data loading, necessary imports, and calculations for both methods.
3. **Confidence_interval.docx**: This document provides an additional explanation of confidence intervals, complementing the main assignment.

## Instructions
1. **Review the Documents**:
   - **Basic_stats_2.docx**: Understand the objectives, methods, and conclusions for constructing the confidence intervals. This document explains the theoretical background and the results obtained.
   - **Confidence_interval.docx**: Review this for a deeper understanding of Assignment problem statement.

2. **Run the Python Script**:
   - **Basic_stats_2.py**: Execute this script to reproduce the calculations and results presented in the documents. Ensure all required libraries (`pandas`, `numpy`, `scipy`) are installed.

## Summary of Methods and Results

### Task 1: Using Sample Standard Deviation
- **Objective**: Construct a 99% confidence interval for the mean number of characters printed before the print-head fails using the sample standard deviation.
- **Method**: T-distribution is used since the population standard deviation is unknown and the sample size is relatively small.
- **Data**: `[1.13, 1.55, 1.43, 0.92, 1.25, 1.36, 1.32, 0.85, 1.07, 1.48, 1.20, 1.33, 1.18, 1.22, 1.29]`
- **Results**:
  - Sample Mean: 1.239
  - Standard Deviation: 0.193
  - Margin of Error: 0.148
  - Confidence Interval: `[1.09, 1.387]`

### Task 2: Using Known Population Standard Deviation
- **Objective**: Construct a 99% confidence interval for the mean number of characters printed before the print-head fails using the population standard deviation.
- **Method**: Z-distribution is used since the population standard deviation is known.
- **Data**: `[1.13, 1.55, 1.43, 0.92, 1.25, 1.36, 1.32, 0.85, 1.07, 1.48, 1.20, 1.33, 1.18, 1.22, 1.29]`
- **Results**:
  - Sample Mean: 1.239
  - Population Standard Deviation: 0.2
  - Margin of Error: 0.133
  - Confidence Interval: `[1.106, 1.372]`

### Conclusion
- The confidence intervals obtained using the T-distribution and Z-distribution are very similar, with the T-distribution interval being slightly wider due to using the sample standard deviation. Both methods indicate that 99% of the print-heads are expected to print between approximately 1.1 and 1.3 million characters before failure.

## Execution Steps
1. **Run the Script**:
   ```bash
   run Basic_stats_2.ipynb 
   # run in jupyter notebook

