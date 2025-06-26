# 🎓 Academic Marks Prediction Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)

This project predicts a student’s academic marks using their full education history from 1st to 12th grade. It uses supervised machine learning models to identify which factors most influence performance — such as attendance and study habits.

---

## 📁 Dataset Overview

The dataset was manually created and includes the following features:

| Feature           | Description                                       |
|-------------------|---------------------------------------------------|
| `Academic Year`   | Academic session year (e.g., 2012–2013)           |
| `Grade`           | School grade (1 to 12)                            |
| `Average Mark`    | Target: average mark/percentage for that year     |
| `type`            | Type of education board (CBSE/State)              |
| `Extra Curricular`| Participation in activities (Yes/No)              |
| `Study Hours`     | Estimated daily study hours                       |
| `Attendance`      | Attendance percentage                             |

➡️ After correlation analysis, only selected features were used to train the model (`Attendance`, `Study Hours`, etc.).

---

## 📊 Exploratory Data Analysis

- Correlation heatmaps to find relationships
- Visualizations: box plots, bar charts
- Feature selection based on importance



---

## 🤖 Models Used

- **Linear Regression**


### 🔍 Evaluation Metrics

| Metric     | Value         |
|------------|---------------|
| MSE        | 70.73         |
| R² Score   | 0.27 (Linear) |

---

➡️ **Conclusion: The model isn't performing well yet, which is normal for small datasets (12 rows) and limited features**
