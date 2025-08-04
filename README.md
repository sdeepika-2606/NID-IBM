# NID-IBM
# 🛡️ Network Intrusion Detection System (NIDS) using Machine Learning

This project is a **Network Intrusion Detection System (NIDS)** built using machine learning to analyze network traffic data and identify cyber-attacks such as:

- DoS (Denial of Service)
- Probe
- R2L (Remote to Local)
- U2R (User to Root)

The system classifies network behavior as either **normal** or **attack**, using a trained machine learning model. It helps provide an early warning system against potential threats in communication networks.

---

## 🗃️ Dataset

Kaggle: [Network Intrusion Detection Dataset](https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection)

Each row represents a network connection with 41 features, and a label (attack or normal).

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- MinMaxScaler, LabelEncoder, OrdinalEncoder
- Jupyter Notebook / Google Colab

---

## 📊 Machine Learning Workflow

1. **Data Preprocessing**
   - Encoding categorical columns using `OrdinalEncoder`
   - Label encoding of the target class using `LabelEncoder`
   - Normalization using `MinMaxScaler`

2. **Model Training**
   - Random Forest Classifier
   - Train/test split
   - Evaluation using accuracy, precision, recall

3. **Streamlit Deployment (Optional)**
   - Built a UI to allow CSV upload and real-time prediction

---

## 🚀 How to Run

1. Clone or download this repository
2. Open the notebook (`nids ibm.ipynb`) in Google Colab or Jupyter Notebook
4. Upload the dataset (`train.csv` and `test.csv`)
5. Run all cells to:
   - Preprocess the data
   - Train the ML model
   - Test predictions

---

## 🔐 Future Scope

- Real-time traffic capture using Scapy
- Deploy as web app using IBM Cloud Code Engine
- Log predictions to dashboard / database
- Auto-alerts for attack classification

---


