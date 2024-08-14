
# VicCrashAnalytics - Blackspot Analysis

## Executive Summary

VicCrashAnalytics partnered with the Victorian government's Department of Transport (DOT) to address the issue of blackspots, or accident-prone areas, in Victoria, Australia. The project aims to identify factors contributing to these blackspots, analyze the data, and develop strategies to mitigate risks and improve road safety.

The project involves a detailed exploration of data provided by DOT, including univariate, bivariate, and multivariate analyses. A Logistic Regression Model is used to classify areas as either blackspots or non-blackspots. The insights gained are intended to inform effective campaigns, intervention strategies, and policy reforms.

## Business Understanding

**Needs**: Identify and address factors contributing to blackspots in Australia to improve road safety.

**Value**: Enhance road safety, potentially saving lives and reducing accidents through predictive analysis and targeted interventions.

**Stakeholders**: DOT, VicCrashAnalytics Team, government representatives, general public, data providers, legislators, and policymakers.

**Solution**: Utilize logistic regression to predict blackspots and implement education campaigns, infrastructure improvements, and traffic management strategies.

**Change**: Implement safety measures, enhance road designs, and raise awareness through targeted campaigns.

**Context**: Ensure that policy reforms and campaigns comply with DOT regulations and effectively target the relevant audience.

## Data Analysis

### Data Understanding

- **Dataset**: Contains 5326 observations and 36 variables, including categorical and numerical data.
- **Target Variable**: `Blackspot` (binary classification).

### Data Cleansing and Preparation

- **Categorical Variables**: Converted to numerical labels using Label Encoding.
- **Missing Values**: Handled by replacing with median values for skewed variables.
- **Data Integrity**: Ensured through thorough cleansing and preparation.

### Exploratory Data Analysis (EDA)

- **Univariate Analysis**: Visualized distributions of key variables (e.g., age, car ownership).
- **Bivariate Analysis**: Analyzed relationships between variables and blackspots.
- **Multivariate Analysis**: Used heatmaps and correlation filters to select significant features.

## Machine Learning Model

### Model: Logistic Regression

- **Feature Selection**: High-correlation features identified and used.
- **Performance Metrics**:
  - Accuracy: 92%
  - Precision: 93%
  - Recall: 98%
  - F1 Score: 98%
  - AUC: 0.86

### Pros and Cons

**Pros**:
- Easy implementation and interpretation
- Provides insights into predictor significance
- Good accuracy for binary classification

**Cons**:
- Assumes linear relationships
- Limited to binary classification
- Linear boundaries may not handle complex data well

## Recommendations

1. **Engineering Improvements**: Optimize traffic signal timings, enhance road signs and lighting, and consider converting intersections to roundabouts.
2. **Public Campaigns**: Promote carpooling, public transport use, and traffic rule adherence.
3. **Enhanced Safety Measures**: Increase police presence and install intelligent traffic management systems in blackspot areas.
4. **Data Quality**: Improve data quality and relevance for better model performance.

