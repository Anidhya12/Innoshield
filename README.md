# Innoshield
This project implements a cybersecurity threat detection system using anomaly detection techniques, specifically leveraging the Isolation Forest model. The system is designed to detect anomalies in network traffic data, integrate with a Security Information and Event Management (SIEM) system, and provide visualizations and alerts through a web application

Data preprocessing is performed to load and prepare the UNSW-NB15 dataset for analysis. An anomaly detection component is implemented using the Isolation Forest model, enabling the prediction of anomalies in the data. The system integrates with a Security Information and Event Management (SIEM) system by implementing alert-sending functionality for detected threats. Additionally, firewall and syslog integration is established to block anomalous IP addresses and send syslog messages for ongoing monitoring. A Flask dashboard is created to provide a user-friendly web application for displaying alerts and monitoring activities. To enhance the interpretability of the model, visualizations are added to illustrate anomaly scores and attack categories, along with SHAP values that help in understanding feature contributions to the model's predictions.

Requirements: 
Python 3.x, pandas, numpy, requests, matplotlib. seaborn, scikit-learn, shap, Flask, pyngrok
