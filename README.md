# 📊 ANOVA Team Performance Analysis

# Overview

This project demonstrates the use of **One-Way ANOVA (Analysis of Variance)** to compare the performance of three different teams based on their scores.

The objective is to determine whether there is a statistically significant difference between the mean scores of the teams.

---

# Problem Statement

Given the performance scores of three teams (Team1, Team2, Team3), we aim to:

* Analyze differences in their mean scores
* Determine statistical significance using ANOVA
* Visualize data distribution

---

# Dataset

* Total observations: 60 (20 per team)
* Features:

  * **Team1** → Scores of Team 1
  * **Team2** → Scores of Team 2
  * **Team3** → Scores of Team 3

---

## 🧠 Concept Used

### 🔸 What is ANOVA?

ANOVA is a statistical method used to compare the means of three or more groups.

### 🔸 Formula

F = Variance Between Groups / Variance Within Groups

---

## 📌 Hypothesis

* **Null Hypothesis (H₀):** All team means are equal
* **Alternative Hypothesis (H₁):** At least one team mean is different

---

## ⚙️ Tools & Libraries

* Python
* Pandas
* NumPy
* SciPy
* Matplotlib
* Seaborn

---

## 🔄 Workflow

1. Generated synthetic dataset for 3 teams
2. Stored dataset in CSV format
3. Converted data from wide format to long format
4. Applied One-Way ANOVA using SciPy
5. Visualized data using boxplot and bar chart
6. Interpreted statistical results

---

## 📊 Visualization

* Boxplot for distribution comparison
* Bar chart for mean comparison

---

## 📈 Results & Interpretation

* Calculated **F-statistic** and **p-value**
* Compared p-value with significance level (α = 0.05)

### ✅ Decision Rule:

* If p-value < 0.05 → Reject H₀
* If p-value ≥ 0.05 → Fail to reject H₀

---

## 🚀 Key Insights

* ANOVA helps identify whether differences between groups are statistically significant
* Visualization supports statistical findings
* Proper data structuring is essential for analysis

---

## 💼 Interview Explanation

> "In this project, I applied One-Way ANOVA to compare the performance of three teams. I used SciPy to calculate the F-statistic and p-value, and visualized the results using boxplots to better understand the distribution and differences between groups."

---

## 🔮 Future Improvements

* Add Tukey HSD post-hoc test
* Use real-world dataset (Kaggle)
* Build interactive dashboard

---

## 📌 Author

Aditya Singh
Aspiring Data Scientist 🚀
