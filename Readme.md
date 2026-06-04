# PhishGuard 🛡️

## Overview

PhishGuard is a Machine Learning-based phishing website detection system developed using Python, Flask, HTML, CSS, and JavaScript.

The system analyzes website URLs and predicts whether they are legitimate or phishing websites using a Random Forest classifier trained on a phishing dataset.

---

## Features

- URL Feature Extraction
- Machine Learning Classification
- Random Forest Model
- Flask REST API
- Interactive Web Interface
- Real-Time URL Analysis
- Cybersecurity Dashboard UI

---

## Tech Stack

### Backend
- Python
- Flask
- Scikit-Learn
- Pandas
- NumPy

### Frontend
- HTML
- CSS
- JavaScript

---

## Dataset

The project uses a phishing website dataset containing over 11,000 URLs with 30 phishing-related attributes.

---

## Project Structure

PhishGuard/

├── backend/

│   ├── app.py

│   ├── requirements.txt

│   ├── model/

│   │   ├── train_model.py

│   │   ├── feature_extract.py

│   │   └── phishguard_model.pkl

│   └── frontend/

│       ├── index.html

│       ├── style.css

│       └── script.js

├── dataset/

│   └── phishing_dataset.arff

└── README.md

---

## How to Run

1. Install dependencies

pip install -r requirements.txt

2. Start Flask Server

python app.py

3. Open frontend/index.html

4. Enter a URL and click Analyze URL

---

## Future Enhancements

- DNS Record Analysis
- Domain Age Verification
- SSL Certificate Validation
- Google Index Verification
- Real-Time Threat Intelligence Integration

---

## Author

Subhranshu

BCA Cybersecurity Project

2026
