# Beta Bank Model

## Overview
In the dynamic retail banking landscape, customer retention is critical for sustained growth and profitability. Beta Bank has identified a troubling trend of customer attrition, which is negatively impacting its financial performance. To address this challenge, the bank has initiated a project to develop a predictive model capable of anticipating customer churn.

## Description
The objective of this project is to leverage historical customer behavior and termination data to predict the likelihood of customer attrition. By accurately identifying at-risk customers, Beta Bank aims to implement proactive retention strategies to preserve its customer base and optimize operational efficiency.

The primary evaluation metric for this predictive model is the F1 score, with a minimum threshold of 0.59 required for project approval. The F1 score, balancing precision and recall, ensures reliable churn identification.

Additionally, the model's performance will be assessed using the AUC-ROC (Area Under the Receiver Operating Characteristic curve) metric. A high AUC-ROC value indicates the model's ability to distinguish between churn and non-churn instances across various decision thresholds.

## Objectives
- Develop a predictive model to anticipate customer churn using historical data.
- Achieve a minimum F1 score of 0.59 to validate the effectiveness of the model.
- Evaluate model performance using the AUC-ROC metric to ensure robustness in identifying churn.

## Conclusion

Through extensive experimentation, the Random Forest Model trained on upsampled data with balanced classes emerged as the top performer, consistently delivering high accuracy, recall, precision, F1 score, and AUC-ROC during testing.

The final model achieved impressive results on unseen data, demonstrating an accuracy of 84.2%, with a recall of 57.5% and a precision of 62.5%. The balanced F1 score of 59.9% and AUC-ROC score of 83.3% underscored the model's effectiveness in identifying at-risk customers.

This predictive tool equips Beta Bank with actionable insights to proactively manage customer retention, foster enduring customer relationships, and enhance competitiveness. Future work may focus on optimizing and integrating the model into Beta Bank's operational workflows to maximize its impact on reducing customer churn and driving business growth.

## Libraries
This project utilizes the following libraries:
- Pandas
- NumPy
- Scikit-learn