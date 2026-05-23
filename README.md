# 🧠 DecodeLabs Internship Projects

Welcome to my internship project repository at **DecodeLabs**!  
This repository contains 4 AI/ML projects built using Python during my internship.

---

## 📁 Projects Overview

### Project 1 — Rule-Based AI Chatbot
A conversational chatbot built from scratch using Python dictionaries and string matching logic.

**What it does:**
- Responds to user messages using a knowledge base of 7 intents
- Sanitizes user input (lowercase, strip whitespace, remove punctuation)
- Uses O(1) dictionary lookup for fast response retrieval
- Handles unknown inputs gracefully with a fallback message
- Runs as an interactive loop until user types `exit`

**Tech used:** Core Python (no libraries)

---

### Project 2 — Data Classification Using AI (KNN)
A machine learning classification model trained on the famous Iris flower dataset.

**What it does:**
- Loads and explores the Iris dataset using Pandas
- Applies feature scaling using StandardScaler for accurate distance calculations
- Trains a K-Nearest Neighbors (KNN) classifier
- Evaluates model performance using Accuracy Score, F1 Score, and Classification Report
- Visualizes results with a Confusion Matrix heatmap and Decision Boundary plot
- Predicts the species of a new unseen flower sample

**Tech used:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn

---

### Project 3 — Tech Stack Career Recommender
An AI-powered career recommendation system using NLP and cosine similarity.

**What it does:**
- Maintains a dataset of 8+ tech job roles with associated skill sets
- Converts skills into TF-IDF vectors using Scikit-learn
- Accepts 3 user skills as input and computes cosine similarity scores
- Recommends the Top 3 most matching career paths with similarity percentages
- Handles cold start problem (when no skills match any role)
- Packaged as a reusable `recommend_career()` function

**Tech used:** Pandas, NumPy, Scikit-learn (TF-IDF, Cosine Similarity)

---

### Project 4 — OCR Text Recognition System
An Optical Character Recognition (OCR) pipeline using computer vision techniques.

**What it does:**
- Generates a synthetic test image with custom text using OpenCV
- Applies image pre-processing: Grayscale → Gaussian Blur → Adaptive Thresholding
- Extracts text from images using Tesseract OCR engine via PyTesseract
- Displays confidence scores for each recognized word
- Shows a 3-panel visual: Original → Pre-processed → OCR Output

**Tech used:** OpenCV, PyTesseract, Pillow, NumPy, Matplotlib

---

## 🛠️ Technologies Used

| Category | Tools |
|---|---|
| Language | Python 3 |
| ML / AI | Scikit-learn, KNN, TF-IDF, Cosine Similarity |
| Computer Vision | OpenCV, PyTesseract, Pillow |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Environment | Google Colab |

---

## 👤 Author

**Bahadar Akmal**  
AI Engineering Intern — DecodeLabs  
GitHub: [@bahadurakmal1620-prog](https://github.com/bahadurakmal1620-prog)

---

*Built with dedication during my internship at DecodeLabs 🚀*
