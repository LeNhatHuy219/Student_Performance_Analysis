# Student Performance Analysis Project 

**Course:** Data Analysis and Visualization  
**University:** Ton Duc Thang University  
**Instructor:** PhD. Tran Thi Thanh Diu  

---

##  Team Members
| Student Name | Student ID |
|--------------|------------|
| **Le Nhat Huy** | 523H0138 |
| **Nguyen Thai Khanh Nam** | 523H0159 |

---

##  Project Overview
This project aims to analyze the factors affecting high school students' academic performance in **Math, Reading, and Writing**. By applying Data Science techniques, we investigate how demographic backgrounds (Gender, Race, Parental Education) and preparation (Test Prep Course) influence exam scores.

**Dataset Source:** [Students Performance in Exams (Kaggle)](https://www.kaggle.com/spscientist/students-performance-in-exams)

** Version :** Python 3.9.18
---

##  Repository Structure
* `523H0138_523H0159.ipynb`: The main **Jupyter Notebook** containing all Python code, visualization, and analysis.
* `523H0138_523H0159.docx`: The detailed **Final Report** explaining methodology and conclusions.
* `StudentsPerformance.csv`: The dataset used for this project.
* `README.md`: Project documentation.

---

##  Tech Stack & Libraries
The project is implemented using **Python** with the following libraries:
* **Pandas & NumPy:** Data manipulation and cleaning.
* **Matplotlib & Seaborn:** Data visualization (Histograms, Boxplots, Heatmaps).
* **SciPy:** Statistical hypothesis testing (Shapiro-Wilk, T-test, ANOVA).
* **Statsmodels / Scikit-learn:** Multiple Linear Regression modeling.

---

##  Key Analysis Steps
1.  **Exploratory Data Analysis (EDA):** Data cleaning, outlier detection, and distribution visualization.
2.  **Probability Distribution Analysis:** verifying Normality using Shapiro-Wilk test and Q-Q Plots.
3.  **Hypothesis Testing:**
    * *T-test:* Analyzing gender differences in scores.
    * *ANOVA:* Analyzing the impact of Parental Education levels.
4.  **Correlation Analysis:** Pearson & Spearman correlation to find relationships between subjects.
5.  **Predictive Modeling:** Building a Multiple Linear Regression model to predict Math scores ($R^2 \approx 0.84$).

---

##  How to Run
1.  Clone this repository:
    ```bash
    git clone [https://github.com/LeNhatHuy219/Student_Performance_Analysis.git](https://github.com/LeNhatHuy219/Student_Performance_Analysis.git)
    ```
2.  Install required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn scipy statsmodels
    ```
3.  Open the notebook `523H0138_523H0159.ipynb` in Jupyter Notebook or Google Colab.
4.  Run all cells to see the analysis and charts.

---

##  Conclusion
* **Gender:** Males score higher in Math, while Females score higher in Reading/Writing.
* **Preparation:** Completing the test preparation course significantly improves scores.
* **Parental Education:** Higher parental education levels are linked to better student performance.
* **Prediction:** Math scores can be accurately predicted using Reading/Writing scores and Gender.

---
*Project submitted for Midterm & Final Project - 2025*
