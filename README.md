# 🚢 Titanic Survival Analysis: A Data-Driven Investigation

This project analyzes passenger survival on the Titanic using a data-driven approach through interactive visualizations. It explores whether survival was influenced by specific measurable factors or a combination of social and situational conditions.

---

## 📌 Overview

The project follows a structured analytical approach:

* Individual factor analysis (Gender, Class, Age, Family Size)
* Comparative analysis across categories
* Multi-variable visualization through dashboard
* Exploration of patterns influencing survival

The study reveals that survival was not random, but strongly influenced by multiple interacting factors.

---

## 🎯 Objectives

* Analyze survival patterns using visualization techniques
* Identify key factors affecting survival
* Understand how different variables interact
* Present insights using an interactive Tableau dashboard

---

## 📊 Dataset

* Titanic passenger dataset (historical data from 1912)
* Structured tabular dataset

### 🔹 Key Features

* PassengerId
* Pclass
* Sex
* Age
* SibSp
* Parch
* Fare
* Survived

### 🔹 Target Variable

* **Survived (0 = No, 1 = Yes)**

---

## ⚙️ Data Preprocessing

* Handled missing values (especially Age)
* Cleaned dataset for analysis
* Verified data types
* Created new derived features for better insights

---

## 🔧 Feature Engineering

New variables were created to enhance analysis:

* **Age Group**

  * Child (0–12)
  * Teen (13–19)
  * Adult (20–59)
  * Senior (60+)

* **Family Size**

  * SibSp + Parch

* **Family Category**

  * Alone
  * Small Family
  * Large Family

These features improved interpretability and visualization clarity.

---

## 📈 Exploratory Analysis

### Observations

* Survival distribution is uneven across groups
* Strong variation based on gender and class
* Age and family size show meaningful patterns

### Key Patterns

* Females had significantly higher survival rates
* First-class passengers had better survival chances
* Survival decreases with age
* Moderate family size improves survival probability

---

## 📊 Visualization Approach

The project uses multiple visualization techniques:

* **Bar Charts** → Category comparison (Gender, Class, Family)
* **Line Chart** → Trend analysis (Age Groups)
* **Dashboard** → Combined multi-variable insights

---

## 🧪 Analytical Breakdown

### 1. Gender Analysis

* Female survival (~74%) vs male (~19%)
  → Strong gender-based survival difference

---

### 2. Passenger Class Analysis

* 1st class (~63%) highest
* 3rd class (~24%) lowest
  → Socioeconomic status influenced survival

---

### 3. Age Group Analysis

* Children highest survival (~57%)
* Decline in survival with increasing age
  → Younger passengers were prioritized

---

### 4. Family Size Analysis

* Small families (~58%) highest survival
* Large families lowest (~16%)
  → Moderate group size improved chances

---

## 📊 Dashboard

An interactive Tableau dashboard integrates all visualizations:

### Filters:

* Gender
* Passenger Class
* Age Group
* Family Category

This enables dynamic exploration of survival patterns.

---

## 🧠 Key Findings

* Gender had the strongest impact on survival
* Higher class increased survival probability
* Younger passengers had better chances
* Small families performed better than large groups

---

## 🧾 Conclusion

Passenger survival was influenced by:

* Social hierarchy (class)
* Gender-based prioritization
* Age-based evacuation patterns
* Family structure



---

## 📁 Project Structure

```
Titanic-Survival-Analysis/
│── dataset.csv
│── Tableau_Workbook.twbx
│── Project_Report.pdf
│── Presentation.pptx
│── README.md
```

---





Interactive Data Visualization (IDV)
