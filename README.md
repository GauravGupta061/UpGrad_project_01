# UpGrad_project_01

                                              **Predictive Maintenance using Anomaly Detection**

**Project Overview**

This project focuses on building a machine learning model to predict machine breakdowns (anomalies) based on sensor data collected from machines. By detecting anomalies early, organizations can schedule maintenance in advance, preventing costly breakdowns and reducing downtime. The project explores various models including Random Forest, XGBoost, and ensemble methods to detect these anomalies effectively.

**Project Summary**

Problem Statement: The aim of this project is to develop a predictive maintenance system to identify machine breakdowns (anomalies) early using sensor data. By leveraging data-driven insights, we aim to improve maintenance schedules and reduce operational downtime.

**Final Model:**

The final model uses a Stacking Classifier, combining XGBoost and Random Forest, to achieve balanced performance across all metrics.
Key performance metrics include:
Accuracy: 99.5% Precision for anomalies: 0.50 Recall for anomalies: 0.50 F1-score for anomalies: 0.50 This performance ensures that the model can effectively detect machine anomalies with a reasonable balance between precision and recall.

**Key Techniques Used:**
SMOTE: To address the class imbalance issue, where very few instances of anomalies were present in the dataset.

RandomizedSearchCV: For hyperparameter tuning of Random Forest and XGBoost models.

Ensemble Methods: Using Voting and Stacking Classifiers to combine the strengths of different models.

Cross-Validation: Ensured model robustness and reduced the risk of overfitting.

**Dependencies**

Here is a list of Python libraries required to run the project.
pandas==1.2.3 
numpy==1.19.5
scikit-learn==0.24.1
xgboost==1.3.3
matplotlib==3.3.4
imbalanced-learn==0.8.0

**Future Work**

Feature Engineering: Additional feature extraction from the sensor data could improve the model's performance.

Model Tuning: Further hyperparameter tuning for XGBoost and Random Forest can lead to even better results.

Deployment: The model can be deployed using Flask or FastAPI for real-time anomaly detection in a production environment.

**Contact:**

If you have any questions or issues with the project, feel free to contact me:
Name: Gaurav Gupta
Email: guptagaurav061@gmail.com 
Github: https://github.com/GauravGupta061/UpGrad_project_01
