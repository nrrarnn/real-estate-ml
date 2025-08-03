# 🏡 Real Estate Price Prediction with Machine Learning

This is a simple machine learning project that uses a regression model to predict house prices based on input features such as number of bedrooms, bathrooms, year built, and more. The model is deployed as a Flask API.

---

## 🚀 Features

- Train and test a machine learning model (Linear Regression, LARS, Gradient Boosting)
- Predict house price based on input features
- Flask API for serving predictions

---
```bash
📦 real-estate-ml/
├── app.py                # Flask API
├── model.pkl             # Trained ML model
├── notebook.ipynb        # Notebook for EDA and training
├── requirements.txt      # Libraries needed
└── README.md             # You're reading it
```

---

## ⚙️ How to Use

1. **Install dependencies**:
```bash
pip install -r requirements.txt
```

2. **Run the API**:
```bash
python app.py
```

3. **Make a prediction**:
Send a POST request to http://localhost:5000/predict with JSON body:

```bash
{
  "features": [1200, 3, 2, 2010, 2.5, 1, 7]
}
```

Response:
```bash
{
  "prediction": 375385.0126
}
```

**🧠 Tech Stack**
- Python 🐍
- Pandas, NumPy
- Scikit-Learn
- Flask
- Joblib
- Google Colab / Jupyter Notebook
