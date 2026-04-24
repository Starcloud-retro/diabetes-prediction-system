# AI-Based Diabetes Prediction System 🏥

A machine learning project that predicts diabetes risk using patient health data with an interactive web interface.

## 📋 Project Overview

This system analyzes patient health indicators to predict the likelihood of diabetes using a Random Forest classifier.

## 🎯 Features

- **Predictive Model**: Random Forest classifier with 75-85% accuracy
- **Interactive Interface**: User-friendly Streamlit web app
- **Real-time Predictions**: Instant diabetes risk assessment
- **Visual Analytics**: Confusion matrix and ROC curve
- **Risk Analysis**: Identification of key health risk factors

## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- pip package installer

### Installation

1. **Clone this repository**
```bash
   git clone https://github.com/YOUR_USERNAME/diabetes-prediction-system.git
   cd diabetes-prediction-system
```

2. **Install dependencies**
```bash
   pip install -r requirements.txt
```

3. **Train the model**
```bash
   python diabetes_model.py
```

4. **Run the web app**
```bash
   streamlit run app.py
```

## 📁 Project Structure
diabetes_mini_project/
├── 2015.csv                    # Original dataset
├── diabetes_model.py           # Model training script
├── app.py                      # Streamlit web application
├── requirements.txt            # Python dependencies
├── diabetes_model.pkl          # Trained model (generated)
├── scaler.pkl                  # Feature scaler (generated)
├── confusion_matrix.png        # Visualization (generated)
└── roc_curve.png              # Visualization (generated)

## 🔧 Model Details

- **Algorithm**: Random Forest Classifier (100 trees)
- **Features**: 21 health indicators from CDC BRFSS dataset
- **Accuracy**: ~75-77%
- **ROC-AUC**: ~82-84%

## ⚠️ Disclaimer

This tool is for educational and screening purposes only. NOT a substitute for professional medical diagnosis.

## 📄 License

Educational purposes only.

---

**Author**: Zaheer Abbas
**Course**: Artificial Intelligence - Minor Project
