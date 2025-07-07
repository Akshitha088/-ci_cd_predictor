#Intelligent CI/CD Pipeline Failure Predictor
This project is a part of the Techsophy coding interview round. The goal is to build a machine learning-based system that analyzes CI/CD pipeline data to predict which builds are likely to fail and provide preventive recommendations.
## Problem Statement
Build a system that:
- Analyzes historical CI/CD build data
- Predicts whether a build will fail or succeed
- Suggests possible actions to prevent failure
## Features
- Simulated CI/CD pipeline data 
- Feature engineering 
- ML model using **Random Forest Classifier**
- Smart recommendation engine for risky builds
- 
## Technologies Used
- Python
- NumPy, Pandas
- scikit-learn (RandomForestClassifier)
## Model Performance
- Accuracy: ~65%
- Strong prediction for successful builds
- Can be improved for failure detection using class weighting or more data
## Sample Output
Sample 2:
unit_t_coverage: 51.77
t_failure_ratio: 0.75
Predicted Failure: No ❌

Suggested Fixes:
Increase unit test coverage
Investigate failing tests

