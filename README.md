# AI-Powered Intrusion Detection System

An AI-powered Intrusion Detection System (IDS) developed to detect and classify network attacks using Machine Learning, Deep Learning, Transformer architectures, and Explainable AI (SHAP). The project evaluates multiple models on benchmark intrusion detection datasets to identify malicious network traffic with high accuracy and interpretability.

---

## Project Overview

Traditional signature-based intrusion detection systems struggle to detect evolving cyber threats. This project leverages Artificial Intelligence techniques to automatically classify network traffic into multiple attack categories and distinguish malicious activity from benign traffic.

The project compares the performance of classical Machine Learning models with Deep Learning and Transformer-based approaches while using Explainable AI (SHAP) to improve model transparency.

---

## Datasets

- **CIC-IDS Collection (Primary Dataset)**
- **UNSW-NB15 (Reference Dataset)**

---

## Models Implemented

- Decision Tree
- Random Forest
- XGBoost
- Recurrent Neural Network (RNN)
- Long Short-Term Memory (LSTM)
- Transformer
- SHAP (Explainable AI)

---

## Data Preprocessing

- Data Cleaning
- Duplicate Removal
- Missing Value Handling
- Feature Scaling
- Label Encoding
- Dataset Balancing
- Train-Test Split

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

---

## Results

| Model | Accuracy | ROC-AUC |
|--------|----------|----------|
| Decision Tree | 96.88% | 0.9649 |
| Random Forest | 97.46% | 0.9972 |
| XGBoost | 97.15% | 0.9978 |
| RNN | 93.94% | 0.9930 |
| LSTM | - | 0.9922 |
| Transformer | 90.59% | 0.9850 |

Random Forest and XGBoost achieved the best overall performance, while SHAP analysis provided feature-level explanations for model predictions.

---

## Explainable AI

SHAP (SHapley Additive Explanations) was used to:

- Interpret model predictions
- Identify important network traffic features
- Improve transparency of intrusion detection decisions

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- XGBoost
- SHAP
- Matplotlib
- Seaborn
- Google Colab

---

## Repository Structure

```
AI-Powered-Intrusion-Detection-System/
│
├── README.md
├── requirements.txt
├── AI_Powered_Intrusion_Detection_System.ipynb
│
├── images/
│   ├── workflow.png
│   ├── comparison_graph.png
│   └── shap_summary.png
│
└── results/
    └── comparison_table.csv
```

---

## Future Improvements

- Real-time network traffic monitoring
- Federated Learning for distributed IDS
- Lightweight IDS for IoT environments
- Deployment using Flask/FastAPI
- Integration with Security Information and Event Management (SIEM) systems

---

## Author

Shreya Talod
