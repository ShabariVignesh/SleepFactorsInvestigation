# SleepFactorsInvestigation
This project explores factors influencing sleep quality using machine learning techniques such as Principal Component Analysis (PCA), Support Vector Machines (SVM), and Association Rule Mining. Key variables like stress, BMI, and occupation are analyzed to provide actionable insights for healthcare interventions and lifestyle improvements.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Research Methodology](#research-methodology)
- [Key Findings](#key-findings)
- [Results](#results)
- [Dataset](#dataset)
## Introduction
Sleep quality plays a crucial role in mental, physical, and emotional well-being. This research analyzes sleep patterns using machine learning algorithms to identify influential factors such as occupation, stress level, BMI, and heart rate. The findings provide insights into potential lifestyle and medical interventions to improve sleep health.

This project was presented at HINT 24, Manipal Institute of Technology, and has been accepted for publication by Springer (pending final review).

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn (PCA, SVM)
  - mlxtend (Association Rule Mining)

### Machine Learning Techniques:
- Principal Component Analysis (PCA)
- Support Vector Machines (SVM)
- Histogram-Based Feature Selection
- Recursive Feature Elimination (RFE)
- Random Forest Feature Importance
- Association Rule Mining

## Research Methodology
- **Data Collection**: The dataset used for this study was sourced from Kaggle and includes variables such as sleep duration, BMI, stress level, and physical activity.
- **Preprocessing**: Data cleaning and feature encoding were applied to make the dataset compatible with machine learning algorithms.
- **Machine Learning**:
  - Applied PCA for dimensionality reduction.
  - Used SVM for classification of sleep disorders, achieving an 85% accuracy rate.
  - Association Rule Mining and histogram-based feature selection were used to reveal patterns and critical features.
- **Statistical Analysis**: Chi-squared and Cramér's V tests were conducted to assess the strength and significance of associations between variables.

## Key Findings
- **Precision Improvement**: The application of PCA and feature selection improved data analysis precision by 30%.
- **Influential Factors**: Key factors like sleep duration, occupation, stress levels, and BMI significantly impacted sleep quality and disorders.
- **Actionable Insights**: These findings provide valuable insights for healthcare professionals to develop targeted interventions for improving sleep health.

## Results
The analysis identified the following key findings:
- A positive correlation between sleep duration and quality.
- Stress level and BMI were found to be strong indicators of sleep disorders.
- Occupation had a notable impact on health metrics such as blood pressure and heart rate.

## Dataset
The dataset used in this research is available on Kaggle:
- [Sleep Health and Lifestyle Dataset](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)
