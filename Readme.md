# 📊 Learning Statistics for Data Science & Data Analysis

Hi there! 👋  
This repository is part of my learning journey into **Statistics for Data Science and Data Analysis**, focusing on both theory and practical Python coding.

---

## 🎯 Goal

To build a strong foundation in statistics with hands-on Python examples, such as:

- Finding outliers
- Analyzing distributions
- Summarizing data
- Hypothesis testing
- Correlation and regression
- And much more!

---

## 🧠 What You'll Find Here

- 📁 `src/find_Outlier`: Techniques to detect outliers (IQR, Z-Score, Boxplots)
- 📁 `src/stats_part1`: Mean, median, mode, range, variance, etc.
- 📁 `visualizations/`: Histograms, box plots, scatter plots using Seaborn and Matplotlib
- 📁 `notebooks/data`: Interactive Jupyter Notebooks for step-by-step learning and have csv files

---

## 🔧 Tools Used

- Python 3.10+
- Conda (Anaconda or Miniconda)
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `jupyter`,`statistics`

---

## ⚙️ Setting Up the Environment

To get started, you can create a new conda environment with all the required packages:

```bash
# Step 1: Clone the repo
git https://github.com/yashagarwal16/Stats_for_DataScience.git
cd Stats_for_DataScience

# Step 2: Create a conda environment
conda create -n stats_env python=3.10

# Step 3: Activate the environment
conda activate stats_env

# Step 4: Install required libraries
conda install pandas numpy matplotlib seaborn scipy jupyter statistics

# Step 5: Start Jupyter Notebook
jupyter notebook
