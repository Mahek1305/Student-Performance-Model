# 🎓 Student Performance Prediction Dashboard

A **Machine Learning–powered web application** built using **Streamlit** that predicts a student’s **Performance Index** based on academic and lifestyle factors.
The project also provides **interactive visual analytics** to help understand how different factors influence performance.

---

## 📌 Project Overview

This application allows users to:

* Enter student-related details (study hours, sleep, scores, etc.)
* Predict academic performance using a **trained ML regression model**
* Visualize relationships between features and performance
* Explore how changing inputs affects predictions

The system is designed for **educational analysis**, **student self-assessment**, and **ML learning demonstrations**.

---

## 🚀 Features

* 🎯 **Real-time Performance Prediction**
* 📊 **Interactive Visualizations**

  * Correlation Heatmap
  * Feature vs Performance Scatter Plots
  * Performance Distribution
  * Input Impact Analysis
* 🧠 **Pre-trained Machine Learning Model**
* ⚡ **User-friendly Streamlit UI**
* 📈 **Dynamic Feature Sensitivity Analysis**

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Web Framework:** Streamlit
* **Machine Learning:** Scikit-learn
* **Data Handling:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Model Persistence:** Joblib

---

## 📂 Project Structure

```
├── app.py                          # Streamlit application
├── train.ipynb                     # Model training notebook
├── student_performance_model.joblib# Saved ML model
├── Student_Performance.csv         # Dataset
├── README.md                       # Project documentation
```

---

## 🧠 Input Features Used

| Feature                    | Description              |
| -------------------------- | ------------------------ |
| Hours Studied              | Daily study hours        |
| Previous Scores            | Academic history (0–100) |
| Extracurricular Activities | Participation (Yes/No)   |
| Sleep Hours                | Average daily sleep      |
| Sample Question Papers     | Practice count           |

---

## 🎯 Output

* **Predicted Performance Index** (continuous value)
* Visual comparison of prediction with historical data

---

## 📊 Visualizations Included

* 🔥 **Correlation Heatmap** – Shows relationships among features
* 📈 **Regression Plots** – Feature vs performance trends
* 📊 **Distribution Plot** – Performance index spread
* ⚡ **What-if Analysis** – Effect of changing study hours

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/student-performance-predictor.git
cd student-performance-predictor
```

### 2️⃣ Install Dependencies

```bash
pip install streamlit pandas numpy matplotlib seaborn scikit-learn joblib
```

### 3️⃣ Run the Application

```bash
streamlit run app.py
```

---

## 📌 Dataset

* Source: Student academic performance dataset
* Categorical values are preprocessed (Yes → 1, No → 0)
* Cleaned and used for regression modeling

---

## 🧪 Model Training

* Model trained using **Supervised Regression**
* Stored using `joblib` for fast inference
* Training process available in `train.ipynb`

---

## 💡 Use Cases

* Academic performance analysis
* Student self-evaluation
* ML regression demonstration
* Educational dashboards
* Portfolio / Major Project submission

---

## 📸 Application Preview

> Interactive dashboard with sidebar inputs and real-time graphs.

---

## 📜 License

This project is intended for **educational and learning purposes**.

---

## 🙌 Author

**Mahek**
*AI & Data Science Student*


Just tell me 👍
