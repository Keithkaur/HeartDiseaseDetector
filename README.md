# ❤️ Heart Disease Detector

An **end-to-end Machine Learning project** designed to predict chronic heart disease using an **ensemble-based framework** that integrates multiple traditional ML models for high accuracy and reliability.

---

## 🚀 Project Overview

The **Heart Disease Detector** leverages ensemble learning to provide accurate, consistent, and early detection of potential heart diseases.  
It combines the strengths of various models — **SVC, KNN, Random Forest, Decision Tree, and AdaBoost** — and uses a **majority voting mechanism** for final predictions.

**Key Highlights:**
- Developed a custom ensemble ML framework.
- Achieved **99.58% accuracy** on benchmark heart disease datasets.
- Integrated preprocessing, model inference, and visualization in a unified pipeline.
- Designed to support real-time prediction through a user-friendly interface.

---

## 🧠 Workflow

1. **User Input:** Data entered manually or uploaded via medical report.  
2. **Frontend:** Converts input into JSON and sends to backend API.  
3. **Backend:**  
   - Converts JSON to DataFrame  
   - Applies one-hot encoding & standard scaling  
   - Passes data to ensemble model  
4. **Model Prediction:**  
   - Ensemble model aggregates predictions via majority voting  
   - F1-score and individual model accuracies handle tie-breaking  
5. **Output:** Predicted result is sent back and displayed on the interface.

---

## 🧩 Machine Learning Models Used

- **Support Vector Classifier (SVC)**
- **K-Nearest Neighbors (KNN)**
- **Random Forest**
- **Decision Tree**
- **AdaBoost**

---

## 🧪 Technologies and Tools

| Category | Tools Used |
|-----------|------------|
| **Languages** | Python, JavaScript |
| **Libraries (ML)** | scikit-learn, pandas, numpy |
| **Visualization** | matplotlib, seaborn |
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Flask / Node.js (Express) |
| **Version Control** | Git, GitHub |

---

## 📊 Results

| Metric | Score |
|--------|-------|
| **Accuracy** | 99.58% |
| **Precision** | 98.9% |
| **Recall** | 99.4% |
| **F1-Score** | 99.1% |

---
## 📁 Project Structure

Heart-Disease-Detector/
│
├── backend/
│ ├── app.py
│ ├── model/
│ │ ├── ensemble_model.pkl
│ │ ├── ada_boost.pkl
│ │ ├── decision_tree.pkl
│ │ ├── knn.pkl
│ │ ├── rf.pkl
│ │ ├── svc.pkl
│ └── utils/
│ └── preprocess.py
│
├── frontend/
│ ├── index.html
│ ├── script.js
│ └── style.css
│
├── data/
│ └── heart.csv
│
├── requirements.txt
└── README.md

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Keithkaur/Heart-Disease-Detector.git
   cd Heart-Disease-Detector
   ```

   
