# Fake News Detection System (ML + API Validation)
📌 Project Overview

This project is an end-to-end Fake News Detection system that combines Machine Learning classification with real-time news verification using a News API.
In addition to text-based prediction, the system improves reliability by penalizing predictions when a news article is not found in trusted news sources, enhancing overall security and accuracy.

🚀 Key Features

Machine Learning–based fake news classification using textual data

External News API integration for real-world article verification

Confidence adjustment by applying negative scoring if news is not found via API

RESTful backend using FastAPI

Dockerized deployment for cross-platform consistency

Interactive Streamlit frontend for real-time analysis

🧠 System Architecture & Logic

User submits a news headline or article via Streamlit

Text is processed and passed to the ML classification model

Simultaneously, the system queries a News API to check article existence

If the article is not present, a negative weight is applied to the prediction

Final result (Fake / Real) is returned with improved reliability

🧩 Tech Stack

Language: Python

Machine Learning: NLP-based ML model

Backend API: FastAPI

Frontend: Streamlit

External API: News API

Containerization: Docker

🐳 Deployment

Backend and ML model containerized using Docker

Enables reproducible, production-ready execution

Compatible across operating systems

🎯 Use Cases

Fake news detection and media verification

AI-powered content moderation

NLP and ML deployment demonstration

Portfolio project for ML / AI / Python roles

🔮 Future Enhancements

Model explainability (SHAP / attention-based NLP)

Multi-source news validation

Confidence score visualization

Cloud deployment with CI/CD
