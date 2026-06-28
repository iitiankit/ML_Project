# 🎓 Student Performance Predictor

A Machine Learning web application that predicts a student's **Mathematics Score** based on demographic and academic information. The application is built using **Flask** and deployed on **AWS Elastic Beanstalk**, providing a simple and interactive web interface for real-time predictions.

---

## 🚀 Features

- Predicts Mathematics Score
- Interactive Web Interface
- Flask Backend
- Machine Learning Model Integration
- Data Preprocessing Pipeline
- Logging and Exception Handling
- AWS Elastic Beanstalk Deployment

---

# 📊 Dataset

The model is trained on the **Students Performance Dataset**, which contains demographic and academic information.

### Input Features

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Reading Score
- Writing Score

### Output

- Predicted Mathematics Score

---

# 📂 Project Structure

```text
Student-Performance-Predictor/
│
├── notebook/
├── src/
│   ├── components/
│   ├── pipeline/
│   ├── exception.py
│   ├── logger.py
│   ├── utils.py
│   └── __init__.py
│
├── templates/
├── application.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

# ⚙️ Project Workflow

```text
Dataset
   │
   ▼
Data Preprocessing
   │
   ▼
Model Training
   │
   ▼
Save Model (.pkl)
   │
   ▼
Flask Web Application
   │
   ▼
User Input
   │
   ▼
Prediction
```

---

# 🛠️ Tech Stack

### Programming Language

- Python

### Backend

- Flask

### Machine Learning

- Scikit-Learn
- CatBoost
- XGBoost

### Data Processing

- Pandas
- NumPy

### Deployment

- AWS Elastic Beanstalk

### Version Control

- Git
- GitHub

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Student-Performance-Predictor.git

cd Student-Performance-Predictor
```

Create virtual environment

```bash
python -m venv venv
```

Activate virtual environment

Windows

```bash
venv\Scripts\activate
```

Linux

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python application.py
```

Open

```
http://127.0.0.1:5000
```

---

# 📈 Prediction Process

1. User enters student details.
2. Flask receives the input.
3. Data is preprocessed using the saved pipeline.
4. The trained machine learning model predicts the Mathematics Score.
5. The predicted score is displayed on the web page.

---

# ☁️ Deployment

The application is deployed on **AWS Elastic Beanstalk**, enabling scalable and reliable hosting for the Flask web application.

---

# 📌 Future Enhancements

- FastAPI Migration
- Docker Support
- CI/CD Pipeline
- Model Monitoring
- REST API Integration
- Authentication System

---

# 👨‍💻 Author

**Ankit Kumar**

B.Tech
Indian Institute of Technology (ISM), Dhanbad


---

⭐ If you found this project useful, consider giving it a Star on GitHub.
