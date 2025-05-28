# Health Insurance Cost Predictor 🩺💰

A Streamlit-based web application that predicts personalized health insurance costs based on demographic, lifestyle, and medical history information.

## 🔍 Features
- Interactive UI using **Streamlit**
- Dual-model approach (`≤25` vs `>25` age groups)
- Normalized medical risk scoring
- Preprocessing with `StandardScaler` and `OneHotEncoder`
- Sub-second prediction latency for 500+ users

## 🛠️ Tech Stack
- Python
- Pandas
- Matplotlib
- Seaborn
- Streamlit
- Scikit-learn
- XGBoost
- Joblib

## 🚀 How to Run Locally
```bash
# Clone the repository
git clone https://github.com/yourusername/health-insurance-cost-predictor.git
cd health-insurance-cost-predictor

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app/streamlit_app.py
```
## Analysis in EDA
Explore eda.ipynb files for better understanding of how model works 
