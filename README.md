# 🎓 Student Performance Analysis

> **Exploring the factors that influence student academic performance using Python, Data Analysis & Machine Learning.**

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python\&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas\&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy\&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4c72b0)](https://seaborn.pydata.org/)
[![Scikit--learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-F7931E?logo=scikit-learn\&logoColor=white)](https://scikit-learn.org/)

---

## 📌 About the Project

**Student Performance Analysis** is a data analysis and machine learning project focused on understanding the factors associated with students' academic performance.

The project analyzes variables such as:

* 📚 Study hours
* 📝 Previous academic score
* 🎯 Attendance
* 😴 Sleep hours
* 👨‍👩‍👧 Parental education
* 🌐 Internet access
* ⚽ Extracurricular activities
* 💼 Part-time employment
* 👤 Gender
* 📊 Final examination score

The project follows a practical **Data Science workflow**, starting from raw data and progressing through cleaning, exploration, visualization, feature engineering, and machine learning preparation.

---

## 🎯 Project Objective

The main objective is to answer questions such as:

> **"Which factors are associated with better student academic performance?"**

The analysis also prepares the dataset for machine learning tasks such as:

* Predicting `final_exam_score`
* Classifying students using `pass_fail`

---

## 📊 Dataset

The dataset contains **608 student records** with **13 original features**.

### Main Variables

| Feature                 | Description                   |
| ----------------------- | ----------------------------- |
| `student_id`            | Unique student identifier     |
| `gender`                | Student gender                |
| `age`                   | Student age                   |
| `study_hours_per_day`   | Average daily study hours     |
| `attendance_percentage` | Attendance percentage         |
| `previous_score`        | Previous academic score       |
| `sleep_hours`           | Average daily sleep           |
| `extra_curricular`      | Extracurricular participation |
| `parental_education`    | Parental education level      |
| `internet_access`       | Internet availability         |
| `part_time_job`         | Part-time job status          |
| `final_exam_score`      | Final examination score       |
| `pass_fail`             | Final academic result         |

---

## 🛠️ Tech Stack

```text
🐍 Python
│
├── NumPy          → Numerical Operations
├── Pandas         → Data Manipulation
├── Matplotlib     → Data Visualization
├── Seaborn        → Statistical Visualization
└── Scikit-learn   → Machine Learning
```

---

## 🔍 Project Workflow

```text
📂 Raw Dataset
      │
      ▼
🧹 Data Cleaning
      │
      ▼
🔎 Data Exploration
      │
      ▼
📊 Exploratory Data Analysis
      │
      ▼
📈 Data Visualization
      │
      ▼
🔗 Correlation Analysis
      │
      ▼
⚙️ Feature Engineering
      │
      ▼
🔢 Categorical Encoding
      │
      ▼
🤖 Machine Learning Preparation
      │
      ▼
📌 Prediction & Analysis
```

---

## 📈 Exploratory Data Analysis

The project uses Python visualization libraries to investigate relationships between student characteristics and academic performance.

### Visualizations Include

* 📊 Distribution plots
* 📦 Box plots
* 📈 Scatter plots
* 📉 Line plots
* 📋 Bar charts
* 🥧 Pie charts
* 🔥 Correlation heatmaps
* 🔗 Pair plots

### Example Questions Explored

* Does more study time relate to higher exam scores?
* How does attendance relate to academic performance?
* Does previous academic performance relate to final scores?
* Is sleep associated with student performance?
* Does parental education show a relationship with scores?
* How do extracurricular activities compare with academic performance?
* Do students with internet access perform differently?
* How does having a part-time job relate to academic results?

---

## 🧹 Data Preprocessing

The project performs several preprocessing operations:

* Missing-value checking
* Duplicate checking
* Data-type inspection
* Outlier identification
* Outlier treatment
* Data filtering
* Feature transformation
* Categorical encoding

Categorical variables are converted into numerical features using:

```python
pd.get_dummies()
```

---

## 🤖 Machine Learning

The project introduces machine learning using **Scikit-learn**.

### Regression Target

```text
final_exam_score
```

The regression workflow includes:

```text
Features
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
```

### Classification Target

```text
pass_fail
```

This target can be used to develop classification models for predicting whether a student is likely to pass or fail.

---

## 📁 Project Structure

```text
Student-Performance-Analysis/
│
├── DataSet/
│   ├── student_performance_dataset.csv
│   └── updated_data.csv
│
├── NoteBook/
│   └── project_based_learning.ipynb
│
├── README.md
└── requirements.txt
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Devam-Rajput-1006/Student-Performance-Analysis.git
```

### 2. Open the Project

```bash
cd Student-Performance-Analysis
```

### 3. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```text
NoteBook/project_based_learning.ipynb
```

---

## 💡 Key Skills Demonstrated

Through this project, I practiced:

* 🐍 Python programming
* 🔢 NumPy
* 🐼 Pandas
* 📊 Data cleaning
* 🔍 Exploratory Data Analysis
* 📈 Matplotlib
* 🎨 Seaborn
* 🔗 Correlation analysis
* ⚙️ Feature engineering
* 🔤 Categorical encoding
* 🤖 Scikit-learn
* 📚 Regression
* 🎯 Classification concepts
* 📊 Train/Test splitting
* 🧠 Machine learning fundamentals

---

## 📌 Project Status

**Status: 🟢 Completed — Data Analysis & ML Preparation**

The project currently focuses on the complete data-analysis workflow and preparation of the dataset for machine learning.

---

## 👨‍💻 Author

### Devam Rajput

**B.Tech CSE | Data Science & Machine Learning Enthusiast**

🔗 **GitHub:**
https://github.com/Devam-Rajput-1006

---

⭐ **If you find this project useful, consider giving the repository a star!**
