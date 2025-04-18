# CareSense 🩺
##*Your AI-powered symptom check-in tool.*

CareSense is an AI-powered triage assistant that helps users assess symptom urgency and receive personalized care recommendations. It uses natural language input and optionally extracts symptoms from patient report images using OCR.


## 🔍 Problem
Many individuals are uncertain about when to seek care, leading to either delayed medical attention or overuse of emergency services. This is especially true for underserved populations without immediate access to health professionals.


## 💡 Solution
CareSense provides an intelligent triage system that:
- Classifies the urgency of symptoms (Low, Medium, High)
- Recommends appropriate care actions and specialties
- Logs user symptom history for pattern recognition and better support
- Uses real symptom descriptions extracted from medical report images via OCR 

## ⚙️ Features
- Natural language symptom classification
- Enriched outputs: care type, suggested specialty, and urgency level
- Built with Python, scikit-learn, and Streamlit
- OCR image

## 🧪 Setup Instructions

### Install Python Dependencies

```bash
pip install -r requirements.txt
```

### Train the Model

```bash
python ocr_extract.py         # Extract symptoms from patient report images
python train_model.py         # Train and save model using extracted data
```

### Launch the Web App

```bash
streamlit run app.py
```
---

## ❇️ Example Output

![Example Output Screenshot](./assets/screenshots/results.png)

## 🛠️ Tech Stack

- Python 3.9+
- scikit-learn
- Streamlit
- Pandas
- Tesseract OCR
- PIL / pytesseract

---

## 📚 Credits
CU Denver – AurariaHack 2025

---
