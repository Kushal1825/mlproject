## End to End Machine Learning Project
# 🎓 Student Performance Prediction System

An **end-to-end Machine Learning project** that predicts **students' math scores** based on multiple academic and demographic factors such as gender, race/ethnicity, parental education, lunch type, test preparation course, and other performance metrics.

---

## 📘 Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Tech Stack](#tech-stack)
4. [Project Structure](#project-structure)
5. [Workflow](#workflow)
6. [Model Pipeline](#model-pipeline)
7. [How to Run](#how-to-run)
8. [Future Improvements](#future-improvements)
9. [Author](#author)

---

## 🧠 Project Overview

The goal of this project is to build a **Machine Learning system** that can **predict the math score** of students by analyzing their personal and academic features.  

This system can help educators and institutions identify students who might need additional support based on early data insights.

---

## 📊 Dataset Description

The dataset used for this project is named **`stud.csv`**, which contains the following columns:

| Feature | Description |
|----------|-------------|
| `gender` | Student's gender |
| `race_ethnicity` | Ethnic group of the student |
| `parental_level_of_education` | Education level of the student's parents |
| `lunch` | Type of lunch the student receives (standard/free) |
| `test_preparation_course` | Whether the student completed the test preparation course |
| `math_score` | Target variable — score achieved in math |
| `reading_score` | Reading score |
| `writing_score` | Writing score |

---

## ⚙️ Tech Stack

- **Programming Language:** Python 3.x  
- **Machine Learning:** Scikit-learn, CatBoost  
- **Data Manipulation:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Web Framework:** Flask  
- **Environment Management:** Virtualenv  
- **Version Control:** Git, GitHub  

---


## 🏗️ Project Structure
```
📂 Student_Performance_System
│
├── 📁 artifact/ # Stores trained models and other artifacts
├── 📁 logs/ # Log files for debugging
├── 📁 notebook/
│ ├── 1. EDA STUDENT PERFORMANCE.ipynb
│ ├── 2. MODEL TRAINING.ipynb
│
├── 📁 src/
│ ├── 📁 components/ # Core ML components
│ │ ├── data_ingestion.py
│ │ ├── data_transformation.py
│ │ ├── model_trainer.py
│ │
│ ├── 📁 pipeline/ # Training and prediction pipelines
│ │ ├── train_pipeline.py
│ │ ├── predict_pipeline.py
│ │
│ ├── exception.py # Custom exception handling
│ ├── logger.py # Logging utility
│ ├── utils.py # Helper functions
│
├── 📁 templates/ # Frontend HTML templates
│ ├── home.html
│ ├── index.html
│
├── 📁 venv/ # Virtual environment
│
├── app.py # Flask web app entry point
├── requirements.txt # Python dependencies
├── setup.py # Setup script for packaging
├── README.md # Project documentation
└── .gitignore # Files to ignore in version control

```

---

## 🔄 Workflow

1. **Data Ingestion:**  
   Load and split the dataset into training and testing sets.

2. **Data Transformation:**  
   Perform encoding, scaling, and handling of categorical/numerical features.

3. **Model Training:**  
   Train multiple models (e.g., Linear Regression, CatBoost, etc.) and evaluate them.

4. **Evaluation:**  
   Measure performance using metrics such as R² Score, RMSE, and MAE.

5. **Prediction Pipeline:**  
   Build a prediction system to take new inputs and predict math scores.

6. **Web Application:**  
   A Flask-based web app where users can input student details and get real-time predictions.

---

## 🧩 Model Pipeline

The model pipeline connects multiple steps:
- **Data Ingestion → Data Transformation → Model Training → Prediction**

Each component is modularized under the `src/components/` and `src/pipeline/` directories, ensuring scalability and maintainability.

---

## 🚀 How to Run

### 1️⃣ Clone the Repository
### 2️⃣ Create a Virtual Environment
### 3️⃣ Install Dependencies
### 4️⃣ Run the Flask Application


## 🧭 Future Improvements

Integrate deep learning models for performance comparison
Add feature importance visualization
Deploy on cloud platforms like AWS or Render
Implement API endpoint for external integration

## 👨‍💻 Author
Kushal K K
