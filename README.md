🕵️‍♂️ DeepFake Detection Web App

📌 Project Overview

This project is a DeepFake Detection Web Application built using Flask (Backend), React.js (Frontend), and a PyTorch-based deep learning model. The application allows users to upload a video, which is then analyzed to determine whether it is REAL or FAKE using deep learning techniques. The model is trained to detect manipulated facial features in videos.

🏗️ Project Structure

DeepFake-Detection
│── model/
│   ├── df_model.pt  # Pre-trained deep learning model
│
│── static/
│   ├── react/
│       ├── css/  # Contains stylesheets for frontend
│       ├── js/   # Minified JavaScript files for React frontend
│
│── templates/
│   ├── index.html  # Frontend UI for video upload and results
│
│── upload/  # Stores uploaded videos temporarily
│
│── requirements.txt  # List of dependencies
│── server.py  # Flask backend and model inference logic
│── README.md  # Documentation (this file)


🛠️ Tech Stack

1.Backend (Flask) 🐍
Flask
PyTorch
OpenCV
NumPy

2.Face Recognition (dlib-based)

3.Frontend (React.js) ⚛️
HTML
CSS
JavaScript

4.Deep Learning Model 🤖
ResNeXt-50: Used as a feature extractor
LSTM: Processes video frame sequences
Softmax Classifier: Predicts REAL or FAKE

📸 How It Works

1️⃣ Upload a video file
2️⃣ The model processes the video and detects manipulated faces
3️⃣ The system returns either FAKE or REAL with a confidence score
4️⃣ The video file is deleted after processing for security

🧑‍💻 Contributors

GEDELA ROHIT CHANDRA - https://github.com/rohitxolo
RAVANAM HARSHA VARDHAN

🌟 Future Improvements

🚀 Improve model accuracy with more datasets
📈 Optimize frontend UI/UX for better user experience
🎯 Deploy to a cloud platform for global access
