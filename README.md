🧠 Autism Prediction Model

A full-stack Machine Learning web application that predicts the likelihood of Autism Spectrum Disorder (ASD) based on user input.
This project integrates a Python-based ML model, a Flask API backend, and an interactive frontend UI, tested using Bruno and powered by a Kaggle dataset.

🚀 Overview

This project explores the application of AI in healthcare, particularly in assisting with autism screening and early detection.
The system enables users to answer a few simple screening questions, after which the model predicts the probability of autism using trained data.

🧩 Features

✅ Data-Driven Prediction: Trained on the Kaggle Autism Screening dataset
✅ Machine Learning Pipeline: Preprocessing, feature selection, and model evaluation
✅ Flask REST API: Handles backend logic and ML inference
✅ Frontend Web Interface: User-friendly input form for real-time predictions
✅ Bruno Testing: Used to test and verify API endpoints
✅ Deployment Ready: Lightweight, portable Flask app with web integration

⚙️ Tech Stack

Frontend:

HTML, CSS, JavaScript

Responsive design for desktop & mobile

Backend / API:

Flask (Python)

Bruno (API testing tool)

scikit-learn, pandas, numpy, joblib

Machine Learning:

Decision Tree, Random Forest and XGB classifier(Got best model as Random Forest)

Trained on Kaggle Autism Screening Dataset

🧠 Model Workflow

Data Preprocessing: Cleaned and normalized Kaggle data

Feature Engineering: Selected key predictors for ASD screening

Model Training: Trained using supervised ML algorithms

Model Evaluation: Measured using Accuracy, Precision, Recall, F1-score

Integration: Deployed via Flask API

Frontend Interaction: User submits form → Flask API → Model → Predicted Result displayed

🖥️ How to Run
🔧 Clone the Repository
git clone https://github.com/yourusername/autism-prediction-model.git
cd autism-prediction-model

🧱 Install Dependencies
pip install -r requirements.txt

🧠 Run the Flask App
python app.py


The app will start on http://127.0.0.1:5000/

🌐 Access the Frontend

Open your browser and visit the above URL to interact with the prediction interface.

🧪 API Testing with Bruno

You can test API endpoints easily using Bruno.
Example:

POST /predict

Input: JSON with user features

Output: Predicted autism likelihood (e.g., “High Risk” / “Low Risk”)

📊 Results

| Metric | Score |
|:--|:--|
| Accuracy | 0.82 |
| Precision | 0.84 |
| Recall | 0.82 |
| F1-Score | 0.83 |

**Interpretation:**
- The model achieves **82% accuracy** on test data.
- It maintains a **high precision (84%)**, meaning few false positives.
- With a **recall of 82%**, it identifies most true cases.
- The **F1-score (83%)** indicates balanced performance.

🌱 Future Improvements

Deploy on cloud (AWS / Render / Railway)

Add database integration for user data

Improve UI/UX and accessibility

Experiment with deep learning models

👩‍💻 Author

👋 Jyotsna Koova
🎓 B.Tech in Information Technology | 💼 3+ years in IT Industry
🤖 AI/ML Specialist | 🐍 Python Expert

📫 Connect with me: www.linkedin.com/in/jyotsna-koova-1376937a
 | jyotsnapnr@gmail.com
