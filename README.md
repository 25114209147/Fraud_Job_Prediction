# 🚨 Fraud Job Prediction 
## Overview
This project aims to detect fraudulent job postings using advanced machine learning algorithms using a dataset from Kaggle. As online job platforms grow, so does the prevalence of scams, making it crucial to identify fake job ads. By analyzing patterns in job listings, our model utilizes techniques like XGBoost and random forests to enhance recruitment integrity.

## Problem Statement
Existing fraud detection methods struggle to keep up with evolving scams, leaving job seekers vulnerable. This project addresses this issue by improving the accuracy of fraud detection through methods such as SMOTE for balancing classes and rigorous model evaluation.

## 🎯 Objectives 
- Develop adaptive machine learning models for recognizing fraud.
- Evaluate various models for effectiveness.
- Deploy the solution on a scalable platform.

## ⚙️ Installation 

### How to Run (Docker) 🐳
```
docker build -t streamlit .
docker run -p 8080:8080 streamlit
```

### How to Run (Local)
```
pip install -r requirements.txt
streamlit run app.py --server.port=8080 --server.address=0.0.0.0
```

Navigate to localhost:8080 (or the specified server.port) to access the website.

##
**You can also access through [this website](https://fraudulent-job-prediction.streamlit.app)**
