# ECON 50: Using Big Data to Solve Economic and Social Problems - Harvard University

This repository contains lab assignments and attempted solutions for **Econ 50 / SUP 135** taught by **Professor Raj Chetty** at Harvard University. In this course, I used big data to analyze key social and economic challenges, such as equality of opportunity, education, health outcomes, climate change, and criminal justice. The assignments leverage both modern data science and econometrics techniques, allowing me to address these issues from a interdisciplinary quantitative perspective.

## Course Overview

**Course Title**: Using Big Data to Solve Economic and Social Problems  
**Instructor**: Professor Raj Chetty, Harvard University  
**Institution**: Harvard University

This course introduced me to frontier social science research and how big data can address some of today’s most pressing social and economic problems. I applied quantitative methods like regression, causal inference, and machine learning to real-world datasets, working to generate actionable insights for policy-making and research.

## Assignments

### **Lab 1: Introductory Statistical Concepts** 
- Context: This lab introduces foundational statistical concepts used in data science. The focus is on understanding basic data structures and conducting preliminary data analysis.
- Dataset: An extract from the 1966 and 1979 National Longitudinal Survey (NLS).
- Approach: Students explore income and demographic data to compute histograms, means, quantiles, and other basic statistical measures.
- Techniques Used: Data visualization, summary statistics, quantile analysis, binning, and random assignment simulations.

### **Lab 2: Measuring Upward Mobility Using the National Longitudinal Survey**
- Context: Analyzing intergenerational mobility in the U.S., the lab investigates how children's income ranks compare to those of their parents across different demographic groups.
- Dataset: The 1997 cohort of the National Longitudinal Survey of Youth (NLSY97).
- Approach: Predict the upward mobility of children by evaluating the rank-rank relationship between parents' and children's incomes, and compare these predictions with population-level data from Chetty et al. (2014).
- Techniques Used: Rank-rank regression, binned scatter plots, percentile ranking, and visualization of mobility statistics.

### **Lab 3: Predicting Social Mobility Using Cross Validation and Random Forests**
- Context: Predicting upward mobility using decision trees and random forests, focusing on absolute mobility at the 25th percentile in different U.S. counties.
- Dataset: Opportunity Atlas data, containing community characteristics for counties with at least 10,000 residents.
- Approach: Implement cross-validation to optimize decision tree depth and random forest performance using both selected and full predictor sets.
- Techniques Used: Cross-validation, random forests, decision tree optimization, RMSE evaluation, and variable importance plots.

### **Lab 4: The Tennessee STAR Experiment**
- Context: Measuring the causal impact of class size on student achievement, this lab examines how smaller class sizes affect academic outcomes in kindergarten.
- Dataset: Data from the Tennessee Student-Teacher Achievement Ratio (STAR) experiment, involving over 11,600 students.
- Approach: Apply regression discontinuity design (RDD) to evaluate causal effects and test for balance in teacher and student characteristics.
- Techniques Used: Regression discontinuity design (RDD), balancing covariates, multivariable regression with school fixed effects, binned scatter plots.

### **Lab 5: Evaluating Education Policy Using Regression Discontinuity Design**
- Context: This lab evaluates the effectiveness of an academic probation policy on educational outcomes, such as on-time graduation rates, by analyzing student-level data from a Canadian university.
- Dataset: Data from a Canadian university's probation policy, containing variables on student performance and graduation outcomes.
- Approach: Use regression discontinuity to estimate the effect of probation on student outcomes, focusing on students near the GPA cutoff.
- Techniques Used: Linear regression, interaction terms, data visualization with scatter plots, RDD implementation.

### **Lab 6: Predicting Social Mobility Using Trees and Regression**
- Context: The goal of this lab is to compare the performance of decision trees and multivariable regression models for predicting social mobility, with a focus on training and testing dataset splits.
- Dataset: National-level data on social mobility, containing predictors related to community characteristics and economic outcomes.
- Approach: Train decision trees and regression models to predict upward mobility, then compare performance on test and training datasets.
- Techniques Used: Decision tree learning, multivariable regression, RMSE calculation, in-sample and out-of-sample performance evaluation.

### **Lab 7: Predicting Social Mobility Using Random Forests and Cross-Validation**
- Context: Building on Lab 6, this lab introduces random forests to improve predictive accuracy while controlling for overfitting through cross-validation.
- Dataset: The Opportunity Atlas dataset, containing predictors related to community characteristics and economic mobility for U.S. counties.
- Approach: Implement random forests with multiple tree depths, cross-validation, and full predictor sets to identify optimal model parameters.
- Techniques Used: Cross-validation, random forests, decision tree learning, RMSE comparison, variable importance plots.

### **Lab 8: Bias in Algorithms**
- Context: This lab addresses the issue of bias in algorithms, particularly in healthcare prediction models, and how model choices affect racial and demographic biases.
- Dataset: Health data from Obermeyer et al. (2019), containing patient demographics, health outcomes, and costs.
- Approach: Train random forest models to predict patient costs and health outcomes, both with and without race as a predictor. Examine the impact on model performance and racial disparities.
- Techniques Used: Random forests, model comparison with and without sensitive variables, variable importance, bias detection.

### **Lab 9: The Long-Run Causal Effects of HOLC “Redlining”**
- Context: This lab investigates the long-term impact of the Home Owners’ Loan Corporation (HOLC) redlining maps on homeownership rates, using both differences in differences (DiD) and regression discontinuity (RDD) approaches.
- Dataset: A historical dataset from the HOLC redlining program, including data on city demographics, housing, and homeownership rates from 1910 to 2010.
- Approach: Apply DiD and RDD to assess the causal effect of HOLC maps on long-term homeownership trends, accounting for pre-treatment characteristics and parallel trends.
- Techniques Used: Differences in differences (DiD), regression discontinuity (RDD), binned scatter plots, robustness checks.

## Technologies Used
- **Programming Languages**: R, Python

## Contact Information

For any questions or comments regarding this repository, please feel free to contact [Shreya Chaturvedi]
