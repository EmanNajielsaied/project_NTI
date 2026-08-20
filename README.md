#  PowerGuard – AI-Based Energy Theft Detection

## Project Overview

PowerGuard is an AI-based system designed to detect electricity theft using smart meter data and machine learning techniques.

The system analyzes electricity consumption patterns and identifies abnormal behavior that may indicate energy theft.

The project combines Machine Learning, Deep Learning, and an Expert System to improve the accuracy and reliability of energy theft detection.

---

##  Project Objectives

- Detect abnormal electricity consumption patterns.
- Identify possible electricity theft cases.
- Use Machine Learning and Deep Learning for prediction.
- Provide an easy-to-use interface using Streamlit.
- Compare different detection approaches.
- Help reduce electricity losses caused by energy theft.

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Streamlit
- Matplotlib
- Seaborn
- Jupyter Notebook

---

 Models Used

The project uses multiple approaches for energy theft detection:

# 1. Random Forest

A Random Forest model is used to classify electricity consumption patterns and detect suspicious cases.

### 2. LSTM

An LSTM deep learning model is used to analyze time-series electricity consumption data.

### 3. Expert System

An expert-based approach is used to apply predefined rules and detect suspicious consumption behavior.

---

##  Project Structure

```text
project_NTI/
│
├── PowerGuard/
│
├── powerapp.py
├── powerguard_expert_v1_20260419_1007.py
│
├── powerguard_LSTM_v1_20260419_1007.keras
├── powerguard_RF_v1_20260419_1007.pkl
│
├── smart_meter_data.csv
├── train_data_lstm.csv
├── test_data_lstm.csv
├── merged_data_lstm.csv
├── powerguard_results_v1_20260419_1007.csv
│
├── Preprocessing_Training_Of__Energy__Theft_Detection.ipynb
│
├── Project_Proposal_PowerGuard_AI_Based_Energy_Theft_Detection.pdf
└── README.md
