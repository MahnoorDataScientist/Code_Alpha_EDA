#  Code_Alpha_EDA

##  Project Overview

This repository contains my **Task 2: Exploratory Data Analysis (EDA)** completed as part of the **CodeAlpha Data Analytics Internship**.

The project performs a complete exploratory data analysis on the Titanic dataset using Python. It includes data inspection, missing value analysis, descriptive statistics, hypothesis testing, outlier detection, correlation analysis, and data visualization.

---

##  Repository Structure

```
Code_Alpha_EDA/
│
├── CodeAlphaTask2(EDA).ipynb      # Jupyter Notebook containing the complete EDA
├── task2_eda_output.png           # Generated visualization output
└── README.md                      # Project documentation
```

---

##  Dataset

* **Dataset:** Titanic Dataset
* **Source:** Seaborn Built-in Dataset (`sns.load_dataset("titanic")`)

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

##  Exploratory Data Analysis Includes

###  Dataset Overview

* Dataset shape
* Column names
* Data types
* First five records

###  Missing Value Analysis

* Missing values count
* Missing percentage for each column

###  Descriptive Statistics

* Numerical statistics
* Categorical statistics

###  Hypothesis Testing

* Survival rate by gender
* Survival rate by passenger class

###  Outlier Detection

Using the **Interquartile Range (IQR)** method for:

* Age
* Fare

###  Correlation Analysis

* Correlation matrix
* Heatmap visualization

###  Visualizations

* Survival Count
* Survival Rate by Gender
* Survival Rate by Passenger Class
* Age Distribution
* Fare Distribution
* Correlation Heatmap

---

##  How to Run

1. Clone this repository

```bash
git clone https://github.com/MahnoorDataScientist/Code_Alpha_EDA.git
```

2. Open the project folder.

3. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

4. Open the notebook.

```bash
jupyter notebook
```

5. Run **CodeAlphaTask2(EDA).ipynb**

---

##  Output

The notebook generates:

* Console summary of the dataset
* Statistical analysis
* Hypothesis testing results
* Correlation matrix
* Multiple visualizations
* Saved figure:

```
task2_eda_output.png
```

---

## Learning Outcomes

Through this project, I learned how to:

* Perform Exploratory Data Analysis (EDA)
* Handle missing values
* Generate descriptive statistics
* Detect outliers using the IQR method
* Test simple data hypotheses
* Create meaningful visualizations
* Analyze correlations between variables

---

##  Author

**Mahnoor Ramzan**

GitHub: https://github.com/MahnoorDataScientist

---

###  If you found this project useful, consider giving it a star on GitHub!
