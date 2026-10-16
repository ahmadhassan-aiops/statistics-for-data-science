<div align="center">

# 📊 Statistics for Data Science

**The statistics every data scientist actually uses, from mean and standard deviation to hypothesis tests and regression, taught with intuition, worked problems and Python code.**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-Stats-8CAAE6?logo=scipy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![Level](https://img.shields.io/badge/Level-Beginner%20→%20Intermediate-0EA5A4)

</div>

---

## 🎯 Why this course

Statistics is the difference between *running* a model and *understanding* it. Each lesson explains the idea first, works through it by hand where it helps, and then does it in Python with **NumPy, Pandas, SciPy and Seaborn** on real data (Iris, IPL cricket deliveries, student placements).

---

## 📚 Module 1: Descriptive statistics

| # | Lesson | What you'll learn |
|---|---|---|
| 1 | [Descriptive vs. inferential statistics](1.%20Descriptive%20statistics/1.%20Descriptive%20vs.%20Inferential%20Statistics.ipynb) | The two branches of statistics and the types of data you'll meet |
| 2 | [Measures of central tendency](1.%20Descriptive%20statistics/2.%20MEASUREMENT%20OF%20CENTRAL%20TENDENCY.ipynb) | Mean, median and mode on the Iris dataset, and why outliers break the mean |
| 3 | [Measures of spread](1.%20Descriptive%20statistics/3.%20MEASURE%20OF%20SPREAD.ipynb) | Range, percentiles, quartiles, IQR, box plots, MAD, variance and standard deviation |

## 📚 Module 2: Inferential statistics

| # | Lesson | What you'll learn |
|---|---|---|
| 1 | [PDF & CDF](2.%20Inferential%20statistics/1.%20PDF%20AND%20CDF.ipynb) | Probability density and cumulative distribution functions, plotted three ways |
| 2 | [PDF & CDF: theory](2.%20Inferential%20statistics/2.%20Theorarical%20understanding%20of%20pdf%20and%20cdf.ipynb) | The intuition behind PDFs and CDFs in plain language |
| 3 | [Normal distribution & CLT](2.%20Inferential%20statistics/3.Normal%20Distribution.ipynb) | Bell curve, empirical rule, z-scores, z-tables and a hands-on Central Limit Theorem proof on IPL data |
| 4 | [Confidence intervals](2.%20Inferential%20statistics/4.%20Confidence%20Interval.ipynb) | Calculating, visualising and interpreting a confidence interval for the mean |
| 5 | [Hypothesis testing](2.%20Inferential%20statistics/5.%20Hypothesis%20testing%20foundation.ipynb) | Null vs. alternative, test statistics, p-values, Type I & II errors and a reusable template |
| 6 | [t-tests](2.%20Inferential%20statistics/6.%20Significance%20tests%20%28t-tests%29.ipynb) | One-sample, two-sample and paired t-tests with SciPy |
| 7 | [Chi-square & ANOVA](2.%20Inferential%20statistics/7.%20Chi%20square%20and%20Anova%20test.ipynb) | Testing categorical independence and comparing group means, step by step |

📝 [Handwritten notes: advanced inferential statistics](2.%20Inferential%20statistics/Advanced%20stats%20%28inferential%29%20notes.pdf) (sample vs. population, covariance and more)

## 📚 Module 3: Correlation & regression

| # | Lesson | What you'll learn |
|---|---|---|
| 1 | [Linear regression](3.%20Correlation%20and%20regression/Linear%20regression.ipynb) | Simple, multiple and polynomial regression: OLS maths and code built from scratch, compared with scikit-learn |

📝 Handwritten notes: [Correlation](3.%20Correlation%20and%20regression/Correlation%20%28Relation%20between%20two%20variables%29.pdf) · [Regression analysis](3.%20Correlation%20and%20regression/Regression%20Analysis.pdf)

---

## 🚀 Getting started

```bash
git clone https://github.com/ahmadhassan-aiops/statistics-for-data-science.git
cd statistics-for-data-science
pip install numpy pandas scipy matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

Run each notebook from inside its module folder. Datasets are included and loaded with relative paths. Module 2 reads its data from `1. Descriptive statistics/`.

---

## 🗂️ Datasets

| File | Used in |
|---|---|
| `iris.csv` | Central tendency, spread, PDF & CDF |
| `deliveries.csv` (IPL ball-by-ball) | Normal distribution & Central Limit Theorem |
| `placement.csv` | Linear regression |

---

## 🧭 Part of a complete Data Science path

**Python basics → NumPy → Pandas → Matplotlib → Seaborn → Statistics → Machine Learning**

- 🐍 [Python for Data Science](https://github.com/ahmadhassan-aiops/python-for-data-science)
- 🔢 [NumPy](https://github.com/ahmadhassan-aiops/Numpy)
- 🐼 [Pandas](https://github.com/ahmadhassan-aiops/Pandas)
- 📈 [Matplotlib](https://github.com/ahmadhassan-aiops/matplotlib)
- 🎨 [Seaborn](https://github.com/ahmadhassan-aiops/seaborn)
- 📊 **Statistics** ← you are here

---

## 👨‍🏫 About the author

**Ahmad Hassan** | AI/ML Engineer & Instructor with 5+ years of experience
1,500+ hours of live teaching, 100+ students mentored from medicine, business and engineering into data roles.

[![Portfolio](https://img.shields.io/badge/Portfolio-ahmadhassan--aiops.github.io-0EA5A4)](https://ahmadhassan-aiops.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ahmad%20Hassan-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmad-hassan-79a44b1a3)
[![GitHub](https://img.shields.io/badge/GitHub-ahmadhassan--aiops-181717?logo=github&logoColor=white)](https://github.com/ahmadhassan-aiops)

⭐ If these notebooks help you learn, please star the repo. It helps other students find it!
