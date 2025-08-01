# Intelligent-Customer-query-Categorization-Engine

## Overview
Customer support teams in banking often receive thousands of queries daily, ranging from loan issues to account problems. Manually categorizing these queries is time-consuming and can lead to inefficiencies in ticket routing.

This project provides a complete end-to-end solution to automatically categorize customer banking queries using Natural Language Processing (NLP) and Machine Learning. The system is designed to help banks and financial institutions improve operational efficiency, reduce response time, and streamline support processes.

The project goes beyond a simple classifier—it covers everything from raw data processing to production deployment. It includes:

Collecting and cleaning real-world banking query data

Performing feature engineering and building a scalable ML pipeline

Comparing classical NLP models (TF-IDF + Logistic Regression) with BERT

Fine-tuning BERT for 50 epochs to achieve high accuracy

Deploying the model using FastAPI (backend) and Swagger (API testing)

Building a Streamlit frontend dashboard for easy interaction

Adding analytics and visualizations for non-technical stakeholders

Dockerizing the entire solution for seamless deployment with one command

This ensures that both technical and non-technical users can benefit from an intelligent, production-ready query categorization engine.

## 🚀 Features
🔹 Data Engineering – Cleaned and processed raw banking query data

🔹 ML Pipeline – TF-IDF + Logistic Regression baseline model

🔹 BERT Training – Fine-tuned for best performance

🔹 REST API Service – Built with FastAPI, tested with Swagger UI

🔹 Streamlit Dashboard – Simple, user-friendly interface for predictions

🔹 Analytics Tab – Visual insights into ticket distribution and trends

🔹 Dockerized Deployment – Launch backend and frontend with one command

## 🔑 Data Workflow
1️⃣ Collect Data → Raw banking query CSVs
2️⃣ Data Cleaning → Remove duplicates, handle missing data, normalize text
3️⃣ Feature Engineering → Tokenization, TF-IDF vectorization
4️⃣ Train/Test Split → Stratified splitting
5️⃣ Modeling →

### Logistic Regression with TF-IDF

Fine-tuned BERT
6️⃣ Evaluation → Accuracy, F1-score, confusion matrix
7️⃣ Deployment → Selected BERT for serving predictions

⚡ Model Serving
FastAPI Backend serves the trained BERT model

Endpoint → /predict for query classification

Swagger UI available for interactive API testing

## 🎨 Frontend Dashboard
Built with Streamlit

### Prediction Tab:

Enter a banking query → Model predicts issue category with confidence

### Analytics Tab:

Displays ticket category distribution

Shows prediction trends per hour

Visualizes confidence levels for better decision-making

Includes a Gauge Score chart to easily understand prediction confidence in a visual meter format



## 🐳 Dockerized Deployment
Run both backend and frontend together using Docker Compose:

docker-compose up --build
Backend API: http://localhost:8000

Frontend UI: http://localhost:8501

## 🧠 Skills Demonstrated
✅ Data cleaning and preprocessing

✅ Feature engineering for NLP

✅ ML pipeline design and training

✅ Model comparison (TF-IDF vs. BERT)

✅ Docker containerization

✅ API development with FastAPI and Swagger

✅ Interactive frontend with Streamlit

✅ Analytics visualization for non-technical users

✅ Production-ready deployment

## ⚙️ How to Run Locally
1️⃣ Clone the repository:

git clone https://github.com/yourusername/tickets-classifier.git
cd tickets-classifier
2️⃣ Build and run the containers:

docker-compose up --build
3️⃣ Access:

Backend API: http://localhost:8000/docs

Frontend UI: http://localhost:8501

# 📜 License

MIT License © 2025 Warda Iftikhar



