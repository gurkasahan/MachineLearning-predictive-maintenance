# Predictive Maintenance using Machine Learning
![Python](https://img.shields.io/badge/python-3.11-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24.2-orange.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-0.87.0-blueviolet.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3.3-brightgreen.svg)
![Joblib](https://img.shields.io/badge/Joblib-1.1.1-yellow.svg)

This project was developed by **Gurk Asahan** as part of a personal initiative to demonstrate predictive maintenance using a machine learning pipeline. A Random Forest classifier was trained on synthetic equipment sensor data to predict failure likelihood.

## 🔍 Project Highlights
- End-to-end ML pipeline: data loading, preprocessing, training, and evaluation
- Real-time prediction interface with **Streamlit**
- Feature importance analysis
- Deployed model using `joblib` for fast inference

## 🚀 Run Locally
To run the web app locally:
```bash
pip install -r requirements.txt
streamlit run app.py
```

## 🗂️ Files
- `app.py` – Streamlit frontend
- `Machine_Predictive_Maintenance_Classification.ipynb` – Notebook for training and EDA
- `model.joblib` – Trained ML model
- `predictive_maintenance.csv` – Dataset
- `requirements.txt` – Dependencies

## 📄 License
This project is licensed under the Apache 2.0 License.

---

**Author**: Gurk Asahan
