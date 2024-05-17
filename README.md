# Flu Vaccine Prediction

## Project Objective
The objective of this project is to develop predictive models that can estimate the likelihood of individuals receiving their H1N1 and seasonal flu vaccines. By analyzing demographic, socioeconomic, behavioral, and opinion-based data collected from respondents, we seek to create models that accurately predict vaccination probabilities for both the H1N1 and seasonal flu viruses. Insights gained from this analysis can inform future public health efforts and strategies to enhance vaccine uptake rates.

## Dataset Overview
The dataset comprises 36 columns, with 'respondent_id' serving as a unique identifier. The subsequent features provide detailed information about respondents, including age group, education level, race, gender, income, marital status, housing situation, employment status, and various behavioral and opinion-based indicators related to flu vaccination.

## Performance Metrics
We evaluated the performance of different algorithms using various metrics:

### Accuracy:
1. Label Powerset with Logistic Regression achieved an accuracy of 0.678.
2. Label Powerset with SVM achieved an accuracy of 0.675.

### Hamming Loss:
Binary Relevance with Decision Tree resulted in a Hamming Loss of 0.288.

### Jaccard Score:
Binary Relevance with Logistic Regression attained a Jaccard Score of 0.312.

### F1 Score:
Binary Relevance with Logistic Regression achieved an F1 Score of 0.327.

### Precision:
Binary Relevance with Logistic Regression demonstrated a Precision of 0.341.

### Recall:
Binary Relevance with SVM exhibited a Recall of 0.324.

These algorithms were identified as the best performers based on each metric.
