# Cab-Review-Analysis
An end-to-end NLP pipeline that classifies cab/ride-sharing reviews into **topics** and **sentiments** using **BERT**. This project includes data generation, preprocessing, model training, and inference components, making it a full-stack solution for textual review analysis in the ride-sharing domain.

---

## 🚀 Features

- 🔍 **Topic Classification** – Identify key aspects like pricing, safety, driver behavior, punctuality, etc.
- 🙂 **Sentiment Analysis** – Detect sentiment (positive, negative, neutral) within each review.
- 🤖 **BERT-based Models** – Leverages the power of pretrained transformer models for high performance.
- 🛠️ **Modular Pipeline** – Includes stages for data generation, cleaning, training, and evaluation.
- 📈 **Inference Support** – Make predictions on new reviews with ease.

---

## 🧠 Model Architecture

- Base model: `bert-base-uncased` (can be swapped with any HuggingFace transformer)
- Fine-tuned on a labeled dataset of ride-sharing reviews
- Dual-head output for topic and sentiment prediction (optional multi-task setup)

---
