![Banner Image](./img/APPLIED_STATISTICS.png)
---
---
![GitHub last commit](https://img.shields.io/github/last-commit/damienfarrell/applied-statistics)
![GitHub contributors](https://img.shields.io/github/contributors/damienfarrell/applied-statistics)
![GitHub commit activity](https://img.shields.io/github/commit-activity/w/damienfarrell/applied-statistics)

# Repository Overview

This repository contains a set of statistical tasks and project written in Python for the [ATU HDip in Data Analytics - Applied Statistics Module](https://github.com/ianmcloughlin/2425_applied_statistics.git). These tasks demonstrate foundational statistical methods and concepts through Python-based calculations and visualisations.

- **`tasks.ipynb`**: Jupyter Notebook containing the statistical tasks.
- **`project.ipynb`**: Jupyter Notebook containing the project analysis using the PlantGrowth dataset.

## Tasks Overview

### **Task 1: Permutations and Combinations**

This task involves calculating probabilities related to a modified version of the classic "Lady Tasting Tea" experiment. It demonstrates the use of combinatorics to determine the likelihood of specific outcomes.

### **Task 2: numpy's Normal Distribution**

In this task, we assess the properties of `numpy.random.normal()` to verify whether it generates values that follow a normal distribution. Statistical and visual methods are used for validation.

### **Task 3: t-Test Calculation**

Here, we manually compute a t-statistic and compare the results with those obtained using `scipy.stats`. This task highlights the underlying mechanics of the t-test.

### **Task 4: ANOVA and Type II Error**

This task estimates the probability of committing a Type II error in an ANOVA test under controlled experimental conditions. It demonstrates the relationship between statistical power, effect size, and sample size.

## Project

### **Analysis of the PlantGrowth Dataset**

The final project, implemented in `project.ipynb`, involves statistical analysis of the [PlantGrowth dataset](https://vincentarelbundock.github.io/Rdatasets/csv/datasets/PlantGrowth.csv).

## How to Use

1. Clone the repository:
   ```bash
   git clone <https://github.com/damienfarrell/applied-statistics.git>
   cd <applied-statistics>
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebooks:
   ```bash
   jupyter notebook
   ```

4. Explore the `tasks.ipynb` and `project.ipynb` files.

## Acknowledgments

The PlantGrowth dataset is sourced from the [R Datasets repository](https://vincentarelbundock.github.io/Rdatasets/).
