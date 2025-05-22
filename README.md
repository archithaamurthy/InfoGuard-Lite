# InfoGuard-Lite : Real-Time Fake News Detection Engine
A strategic prototype for intelligent misinformation detection, blending interpretability with real-time insights.

---

## Overview
**InfoGuard Lite** is a deployable, explainable AI tool that detects misinformation in news articles and tweets using a lightweight machine learning model trained on real-world fake and true news datasets.

This project represents a **modular proof of concept** aimed at countering digital misinformation, with scalable applications in public diplomacy, policy analysis, and cybersecurity.

---

## Features

- **Text Classification** of news articles and tweets (REAL or FAKE)
- **Confidence Scores** and model certainty visualization
- **Influence Score Analysis** highlighting top contributing words
- **Bar Chart Visuals** for interpretability (color-coded: red~ FAKE, green~ REAL)
- **Streamlit App Interface** with responsive UX
- **Model trained on Kaggle Fake-News Dataset** with 97%+ accuracy

---

## Use Cases

- Foreign policy and public diplomacy: Counter misinformation influencing strategic narratives
- Journalism and media houses: Enhance fact-checking pipelines
- EdTech and civic platforms: Foster digital literacy and awareness

---

## Tech Stack

| Component           | Description                       |
|--------------------|-----------------------------------|
| Python             | Core language                     |
| Scikit-learn       | TF-IDF + Logistic Regression model |
| Streamlit          | Interactive web app               |
| Matplotlib         | Word influence visualizations     |
| Pandas, NumPy      | Data preprocessing                |
