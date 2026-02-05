# 🏥 Health Insurance Premium Prediction System( Regression)

## 📋 Project Overview
A production-ready machine learning system that accurately predicts health insurance premiums using an innovative age-based segmentation strategy. Features dual specialized models with exceptional accuracy and a professional Streamlit web interface.

https://img.shields.io/badge/App-Streamlit-FF4B4B?style=for-the-badge
https://img.shields.io/badge/ML-XGBoost%252BRidge-FF6B00?style=for-the-badge
https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge

## 🚀 Live Application

<img src="images/health_insurance_cost_predictor_layout.png" alt="health_insurance_cost_predictor_layout" width="400">
🔗 Try the live app: Streamlit Cloud Deployment ([Add your link here](https://health-insurance-cost-prediction-pro.streamlit.app/))

## 📊 Model Performance

1️⃣ Young Group (≤25 years)

- Model: Ridge Regression
- R² Score: 0.9887
- RMSE: 292.78
- Best Features: Insurance Plan, Genetic Risk

2️⃣ Adult Group (>25 years)

- Model: XGBoost Regressor
- R² Score: 0.9935
- RMSE: 1717.70
- Best Features: Insurance Plan, Age, Medical Risk



## 📈 Feature Importance

1️⃣ Young Group Feature Impact
<img src="images/Healthcare_premium_prediction_young_with_gr.png" alt="Healthcare_premium_prediction_young_with_gr" width="400">
Insurance plan and genetic risk are most influential for young individuals

2️⃣ Adult Group Feature Impact
<img src="images/Healthcare_premium_prediction_rest_with_gr.png" alt="Healthcare_premium_prediction_young_with_gr" width="400">
Insurance plan, age, and medical risk drive premiums for adults


## 📊 Error Analysis

1️⃣ Young Group Error Distribution
<img src="images/Healthcare_premium_prediction_young_with_gr_diff.png" alt="Healthcare_premium_prediction_young_with_gr_diff" width="400">
95% predictions within ±15% error margin

2️⃣  Adult Group Error Distribution
<img src="images/Healthcare_premium_prediction_rest_with_gr_diff.png" alt="Healthcare_premium_prediction_young_with_gr_diff" width="400">
90% predictions within ±20% error margin

## ⚙️ Installation

1. Clone & Install: 

```bash
git clone https://github.com/yourusername/ml-project-premium-prediction.git
cd ml-project-premium-prediction
pip install -r requirements.txt
```
2. **Run the app:**:   
```bash
streamlit run main.py
```

## 🎮 Key Features

- 12 Input Parameters: Age, income, medical history, lifestyle factors
- Dual-Model System: Specialized models for different age groups
- Medical Risk Scoring: Intelligent disease weight calculation
- Real-time Predictions: Instant premium estimates in ₹

## 📁 Project Structure

health-insurance-predictor/
├── main.py                 # Streamlit app
├── prediction_helper.py    # ML prediction engine
├── artifacts/              # Trained models
├── images/                 # sample pictures
└── requirements.txt        # Dependencies

👨‍💻 Author

Yoseph Negash

📧 yosephn22@gmail.com

📅 2026
