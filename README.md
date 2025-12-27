# PhishDetect  🛡️  
An intelligent message and URL security analyzer that detects phishing risks using rule-based analysis and explainable machine learning.

PhishDetect is a full-stack security application designed to analyze suspicious messages and URLs (such as those received via email, SMS, or messaging platforms) and assess their phishing risk.

## 🔍 Overview
The system combines **rule-based security heuristics** with **lightweight NLP and machine learning** to produce an explainable risk score.

## 🧠 Flow
┌──────────────────────────────┐
│          User Input          │
│   Paste Message or URL       │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│        Flask Backend         │
│     Receive Input Data       │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│        Preprocessing         │
│  Text Cleaning & Tokenization|
└──────────────┬───────────────┘
               │
     ┌─────────┴─────────┐
     ▼                   ▼
┌─────────────────┐   ┌──────────────────────┐
│ Rule-Based      │   │ ML Model Prediction  │
│ Analysis        │   │                      │
│ • Phishing      │   │ • TF-IDF             │
│   Keywords      │   │   Vectorization      │
│ • Suspicious URL│   │ • Logistic           │
│   Patterns      │   │   Regression         │
│ • Urgency       │   │                      │
│   Triggers      │   └──────────────────────┘
└─────────┬───────┘
          │
          └──────────────┬───────────────┐
                         ▼               ▼
              ┌──────────────────────────────┐
              │       Risk Score Fusion      │
              │ Combine Rule Score & ML Score│
              └──────────────┬───────────────┘
                             │
                             ▼
              ┌──────────────────────────────┐
              │        Final Result          │
              │ • Risk Level: 75%            │
              │   (Suspicious)               │
              │ • "Urgent action needed"     │
              │ • "High-risk URL detected"   │
              └──────────────────────────────┘


---

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python
- Flask

### NLP & Machine Learning
- NLTK
- TF-IDF (scikit-learn)
- Logistic Regression

### Security Logic
- Rule-based heuristics
- URL pattern analysis

## 👩‍💻 Author

- GitHub: https://github.com/pratikshabade09
- LinkedIn: https://www.linkedin.com/in/pratiksha-bade-2992b7306