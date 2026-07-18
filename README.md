# 🎯 Score Predictor

A machine learning web application that predicts a student's exam score based on demographic and academic information. The project demonstrates an end-to-end ML workflow, including data preprocessing, model training, API development, containerization, CI/CD, and cloud deployment.

## 💡 Key Skills Demonstrated

- Machine Learning Pipeline Development
- Feature Engineering
- Scikit-learn Pipelines
- Docker Containerization
- GitHub Actions CI/CD
- AWS EC2 Deployment
- Model Serialization (Pickle)
- Python Backend Development

---

## 🚀 Features

- Predicts student performance using a trained machine learning model
- Interactive web interface
- Data preprocessing with Scikit-learn Pipelines
- Model serialization using Pickle
- Dockerized for easy deployment
- Automated CI/CD using GitHub Actions
- Deployed on AWS EC2

---

## 🛠️ Tech Stack

### Machine Learning
- Python
- Scikit-learn
- Pandas
- NumPy

### Backend
- Uvicorn
- Jinja2

### DevOps
- Docker
- GitHub Actions
- AWS EC2

---

## 📂 Project Structure

```
score-predictor/
│
├── app/
│   ├── templates/
│   ├── static/
│   ├── main.py
│   ├── predict.py
│   └── utils.py
│
├── artifacts/
│   ├── model.pkl
│   └── preprocessor.pkl
│
├── notebook/
│
├── .github/
│   └── workflows/
│       └── deploy.yml
│
├── Dockerfile
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/<your-username>/score-predictor.git
```

Move into the project directory

```bash
cd score-predictor
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate the virtual environment

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

Start the FastAPI server

```bash
uvicorn app.main:app --reload
```

Open your browser

```
http://127.0.0.1:8000
```

Interactive API documentation

```
http://127.0.0.1:8000/docs
```

---

## 📊 Model Pipeline

The project follows a complete machine learning workflow:

1. Data Collection
2. Data Preprocessing
3. Feature Engineering
4. Model Training
5. Model Evaluation
6. Model Serialization
7. API Integration
8. Deployment

---

## 📌 Input Features

The prediction model uses the following features:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

---

## 🐳 Docker

Build the Docker image

```bash
docker build -t score-predictor .
```

Run the container

```bash
docker run -p 8000:8000 score-predictor
```

---

## ☁️ Deployment

The application is deployed using:

- AWS EC2
- Docker
- GitHub Actions (CI/CD)

Every push to the main branch automatically triggers the deployment workflow.

---

## 📈 Future Improvements

- User authentication
- Model monitoring
- Multiple model comparison
- Explainable AI (SHAP/LIME)
- Model versioning
- Database integration
- Batch prediction endpoint

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Abhigya Narain**

GitHub: https://github.com/Abhigya27
