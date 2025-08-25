# Scikit Playground 🧪

An interactive machine learning playground built with **Vue.js** (frontend), **FastAPI** (backend), and **scikit-learn** (ML engine).  
It allows users to generate datasets, train simple models, and visualize results dynamically.

---

## 🚀 Features
- Generate datasets with `scikit-learn` (`make_classification`, `make_regression`, `make_blobs`, etc.)
- Adjust parameters like:
  - `n_samples` (max 5000)
  - `n_features` (max 20)
  - `n_classes` (max 5)
- Choose ML models:
  - Linear Regression
  - Logistic Regression
  - Decision Tree (depth ≤ 10)
  - KNN (neighbors ≤ 20)
- Live interactive plots (decision boundaries, regression fits) with **Plotly**
- Lightweight and optimized for deployment (Render)

---

## 🏗 Tech Stack
- **Frontend:** Vue.js + TailwindCSS + Plotly.js
- **Backend:** FastAPI + scikit-learn
- **Communication:** REST API
- **Deployment:** Render

---

## 📂 Project Structure (planned)
```
ml-playground/
│── frontend/ # Vue.js app
│── backend/ # FastAPI app
│ ├── main.py # API entry
│ ├── models/ # sklearn model handlers
│ └── datasets/ # dataset generation functions
│── README.md
│── requirements.txt
```
