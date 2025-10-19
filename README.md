# Student Exam Performance Prediction 🎓📊

This project is a Machine Learning application that predicts a student's **math score** based on various input parameters such as gender, parental education, lunch type, reading score, and writing score.

The model is trained using multiple regression algorithms, evaluated, and the best-performing model is saved for deployment. A prediction pipeline is also included for real-time inference.


## 🚀 Features

- Data ingestion and preprocessing
- Model training using multiple regression algorithms
- Hyperparameter tuning with GridSearchCV
- Model evaluation using R2 Score
- Save & Load models using Pickle
- Prediction pipeline for real-time inference

## 🧠 Model Training Workflow

1. **Data Ingestion**
2. **Data Transformation (Preprocessing & Scaling)**
3. **Model Training**
4. **Model Evaluation**
5. **Best Model Selection & Saving (`model.pkl`)**

## 📂 Project Structure
MLPROJECT/
│
├── .ebextensions/
├── artifacts/
├── catboost_info/
├── logs/
├── mlproject.egg-info/
├── notebook/
├── src/
│   ├── components/
│   ├── data_ingestion.py
│   ├── data_transformation.py
│   ├── model_trainer.py
│   ├── pipeline/
│   ├── predict_pipeline.py
│   ├── exception.py
│   ├── logger.py
│   ├── utils.py
├── templates/
│   ├── home.html
│   ├── index.html
├── venv/
├── .gitignore
├── application.py
├── README.md
├── requirements.txt
├── setup.py


## 🛠 Installation & Setup

```bash
# 1️⃣ Clone the repository
git clone <your-repo-url>
cd mlproject

# 2️⃣ Create & activate virtual environment
python -m venv venv
venv\Scripts\activate          # Windows
# source venv/bin/activate     # Mac/Linux

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣  Run the web app
python app.py



