
**🫀 Heart Disease Prediction Using Machine Learning**

This project is a machine learning-powered web application that predicts the presence of heart disease based on various medical attributes. It leverages trained models and a user-friendly interface to assist in preliminary diagnosis.

**🚀 Features**

- Input form for medical data
- Prediction of heart disease risk
- Clean and interactive frontend
- Model built using scikit-learn
- Backend powered by Flask

**🧰 Tech Stack**

- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Python, Flask
- **Machine Learning:** scikit-learn, pandas, numpy
- **Model:** Logistic Regression / Random Forest

**📁 Project Structure**

```
Heart-Disease-Prediction/
├── templates/
│   └── index.html          # Main form interface
├── static/                 # Static assets like CSS
├── model/
│   └── model.pkl           # Trained ML model
├── app.py                  # Flask application
├── heart.csv               # Dataset (if used)
├── requirements.txt        # Dependencies
└── README.md               # Project documentation
```

**⚙️ Installation & Setup**

1. **Clone the repository**

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
```

2. **Create a virtual environment (recommended)**

```bash
python -m venv venv
source venv/bin/activate     # On Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the Flask app**

```bash
python app.py
```

5. **Open in browser**

Visit: `http://127.0.0.1:5000`

**🧪 Sample Inputs**

The model uses the following features:

- Age
- Sex
- ChestPainType
- RestingBP
- Cholesterol
- FastingBS
- RestingECG
- MaxHR
- ExerciseAngina
- Oldpeak
- ST_Slope

**📊 Dataset**

Dataset used: Heart Disease UCI Dataset - https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci

