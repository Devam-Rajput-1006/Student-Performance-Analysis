# Student Performance Analysis

A Python-based data analysis and machine learning project that explores the factors affecting student academic performance using study habits, attendance, previous scores, sleep, extracurricular activities, parental education, internet access, and other student-related attributes.

## Project Overview

The objective of this project is to analyze student performance data, identify meaningful patterns and relationships, and prepare the dataset for machine learning.

The project covers the complete data analysis workflow from data loading and cleaning to exploratory data analysis, visualization, feature engineering, categorical encoding, and initial machine learning preparation.

## Dataset

The dataset contains **608 student records** and **13 columns**.

### Features

| Column                  | Description                                 |
| ----------------------- | ------------------------------------------- |
| `student_id`            | Unique identifier of the student            |
| `gender`                | Student gender                              |
| `age`                   | Student age                                 |
| `study_hours_per_day`   | Average daily study hours                   |
| `attendance_percentage` | Student attendance percentage               |
| `previous_score`        | Previous academic score                     |
| `sleep_hours`           | Average daily sleep hours                   |
| `extra_curricular`      | Participation in extracurricular activities |
| `parental_education`    | Parent's highest education level            |
| `internet_access`       | Availability of internet access             |
| `part_time_job`         | Whether the student has a part-time job     |
| `final_exam_score`      | Final examination score                     |
| `pass_fail`             | Final result: Pass or Fail                  |

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Feature Engineering
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Correlation Analysis
   ↓
Categorical Encoding
   ↓
Feature & Target Selection
   ↓
Train/Test Split
   ↓
Machine Learning Preparation
```

## 1. NumPy

NumPy is used for numerical operations and array-based analysis.

Topics covered include:

* NumPy arrays
* Boolean indexing
* `np.where()`
* `np.sort()`
* Array slicing
* `np.vstack()`
* `np.corrcoef()`

## 2. Pandas

Pandas is used for data loading, cleaning, transformation, and analysis.

The project covers:

* Loading CSV data
* `.head()`
* `.tail()`
* `.info()`
* `.describe()`
* `.shape`
* Missing-value analysis
* Missing-value handling
* Duplicate checking
* Outlier handling
* Filtering
* `groupby()`
* Sorting
* Feature transformation
* Categorical encoding

## 3. Data Cleaning

The dataset is examined for:

* Missing values
* Duplicate records
* Invalid or extreme values
* Data types
* Outliers

For example, unusually high values in `study_hours_per_day` are treated as outliers and handled using the median.

## 4. Exploratory Data Analysis

The project investigates relationships between student characteristics and academic performance.

Examples include:

* Study hours vs final exam score
* Attendance vs final exam score
* Previous score vs final exam score
* Sleep hours vs performance
* Parental education vs performance
* Extracurricular activities vs performance
* Gender vs average score
* Part-time jobs and student performance
* Internet access and student performance

## 5. Matplotlib Visualizations

The project includes several visualization techniques:

* Histogram
* Line plot
* Scatter plot
* Bar chart
* Pie chart
* Multiple subplots

These visualizations are used to understand distributions, trends, and relationships in the dataset.

## 6. Seaborn Visualizations

Seaborn is used for more advanced statistical visualization.

The project includes:

* `histplot()`
* `boxplot()`
* `countplot()`
* `scatterplot()`
* `heatmap()`
* `pairplot()`
* `barplot()`

A correlation heatmap is also used to analyze relationships between numerical variables.

## 7. Feature Engineering

The categorical variables are converted into numerical values using one-hot encoding.

Categorical columns include:

```text
gender
extra_curricular
parental_education
internet_access
part_time_job
```

The project uses:

```python
pd.get_dummies()
```

with `drop_first=True` to avoid unnecessary duplicate dummy variables.

## 8. Machine Learning

The project introduces supervised machine learning using Scikit-learn.

### Regression

The initial regression target is:

```text
final_exam_score
```

The data is separated into:

```text
X = Features
y = final_exam_score
```

The dataset is then divided into training and testing sets using:

```python
train_test_split(
    X,
    y,
    test_size=0.2,
    random_state=42
)
```

### Classification

The dataset also contains:

```text
pass_fail
```

which can be used as a classification target.

The planned classification models include:

* Logistic Regression
* Decision Tree Classifier
* K-Nearest Neighbors (KNN)

The models can be evaluated using classification accuracy and confusion matrices.

## Project Structure

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

## Installation

Clone the repository:

```bash
git clone https://github.com/Devam-Rajput-1006/Student-Performance-Analysis.git
```

Move into the project directory:

```bash
cd Student-Performance-Analysis
```

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
NoteBook/project_based_learning.ipynb
```

## Key Learning Outcomes

Through this project, I practiced:

* Data loading and inspection
* Data cleaning
* Missing-value handling
* Outlier detection
* Data filtering
* Grouping and aggregation
* NumPy numerical operations
* Pandas data manipulation
* Matplotlib visualization
* Seaborn visualization
* Correlation analysis
* Categorical encoding
* Feature and target selection
* Train/test splitting
* Introduction to regression
* Introduction to classification
* Machine learning model preparation

## Conclusion

This project demonstrates the practical application of Python data science tools to analyze student performance data.

The analysis helps explore how factors such as study time, attendance, previous academic performance, sleep, extracurricular activities, and other student characteristics relate to final academic outcomes.

It also provides a foundation for developing machine learning models that can predict student scores and classify students based on their academic results.

## Author

**Devam Rajput**

B.Tech CSE Student

GitHub:
https://github.com/Devam-Rajput-1006
