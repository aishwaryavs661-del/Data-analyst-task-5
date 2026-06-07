# Titanic Dataset - Exploratory Data Analysis (EDA)

This repository contains my submission for **Task 5: Exploratory Data Analysis (EDA)**. The analysis was executed entirely using Python within a Jupyter Notebook environment to uncover trends, patterns, and structural anomalies in the classic Titanic passenger dataset.

## 📋 Objective
The goal of this project is to perform both visual and statistical exploration of the dataset to identify what factors (such as gender, age, and passenger class) most heavily influenced survival probabilities.

## 🛠️ Tools Used
* **Python** (Core Environment)
* **Pandas** (Data Manipulation and Structure Inspection)
* **Matplotlib & Seaborn** (Data Visualization)
* **Google Colab** (Development Workspace)

## 📊 Core Steps Executed
1. **Statistical Exploration:** Checked structural health using `.info()`, summarized numerical data with `.describe()`, and reviewed class balances via `.value_counts()`.
2. **Univariate Analysis:** Plotted histograms with KDE curves to study age distributions and utilized boxplots to isolate extreme ticket price (`Fare`) outliers.
3. **Bivariate & Multivariate Analysis:** Created comparative grouped bar charts to visualize how survival probability drastically shifted across variations of `Sex` and `Pclass`.
4. **Macro Correlation:** Generated a Pearson correlation heatmap matrix to verify the mathematical co-movement across numeric dimensions.

## 🔍 Key Findings & Insights
* **The Gender Factor:** Female passengers achieved significantly higher survival rates across every operational ticket class tier compared to their male counterparts.
* **Socio-Economic Privilege:** Independent of gender, 1st Class ticket status provided severe survival advantages over 2nd and 3rd Class ticket holders.
* **Data Integrity Flags:** The exploratory checks revealed critical data gaps in the `Age` stream and severe right-skewed layout anomalies among luxury ticket `Fare` outlays.

## 📂 Deliverables in this Repository
* **`Untitled1.ipynb`**: The complete Jupyter Notebook containing all raw Python source code, table outputs, and data plots.
* **`Titanic_EDA_Findings_Report.pdf`**: A polished, formal executive findings document summarising the visual observations and statistical summary matrices.

