

---

# Student Exam Score Prediction: Exploratory Data Analysis

## 📌 Project Overview

This repository contains a comprehensive exploratory data analysis (EDA) of a dataset featuring 20,000 student records. The goal of this project is to identify and visualize the primary factors—such as study habits, physical well-being, and academic environment—that contribute to a student's final exam performance.

## 📊 Dataset Description

The analysis is based on the `Exam_Score_Prediction.csv` dataset. Key features analyzed include:

* **Demographics:** Age, Gender.
* **Academic Habits:** Study Hours, Class Attendance, Study Method (e.g., coaching, self-study, online videos).
* **Environment & Resources:** Internet Access, Facility Rating, Exam Difficulty.
* **Health & Well-being:** Sleep Hours, Sleep Quality.
* **Target Variable:** Exam Score.

## 🛠️ Data Processing & Cleaning

* **Library Integration:** Utilized `pandas` for data manipulation, `numpy` for numerical operations, and `matplotlib`/`seaborn` for data visualization.
* **Handling Missing Values:** Verified that the dataset contains no null values across all 13 columns.
* **Standardization:** Standardized column names by capitalizing the first letter for a consistent coding format.
* **Filtering:** Performed specific filtering (such as removing "Other" gender categories) to ensure focused and accurate statistical comparisons.

## 📈 Key Findings & Visualizations

The analysis revealed several critical insights into student success:

* **The Power of Study Hours:** Confirmed a strong positive correlation ( 0.71) between daily study hours and higher exam scores.
* **The Sleep Factor:** Visualized the significant impact of sleep quality. Students with "Good" sleep quality consistently achieved higher average scores compared to those with "Poor" sleep.
* **Difficulty Distribution:** A **Pie Chart** analysis showed that nearly half (**49.5%**) of the exams were of "Moderate" difficulty, followed by "Easy" (**30.9%**) and "Hard" (**19.6%**).
* **Performance Trends:** Used **Line Plots** to map the direct relationship between increased effort (study hours) and academic outcomes (exam scores).

## 🚀 How to Use

1. **Clone the Repository:**
```bash
git clone https://github.com/your-username/student-exam-analysis.git

```


2. **Install Dependencies:**
```bash
pip install pandas numpy matplotlib seaborn

```


3. **Run the Notebook:** Open `ExamScorePrediction.ipynb` in Jupyter Notebook or VS Code to view the full step-by-step analysis and generated plots.

## 📁 Repository Structure

* `ExamScorePrediction.ipynb`: The main Python notebook containing the full analysis code and visualizations.
* `Exam_Score_Prediction.csv`: The raw dataset used for the project.
* `README.md`: Project documentation.

---

* **Visual Appeal:** In your GitHub README, you can include the actual image of your Pie Chart or Line Plot by using the syntax `![Exam Difficulty Distribution](path/to/your/image.png)`.
* **Cleanliness:** Before you commit your final version, remember to **Restart & Run All** in your notebook so that all outputs (charts and tables) are visible directly on the GitHub page.
