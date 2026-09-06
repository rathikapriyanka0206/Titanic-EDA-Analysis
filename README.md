# Titanic-EDA-Analysis
# Titanic EDA Analysis

Exploratory Data Analysis (EDA) on the Titanic dataset, completed as **Task 5** of the Data Analyst Internship (Elevate Labs).

## 📌 Objective
Extract insights from the Titanic dataset using visual and statistical exploration, and identify patterns, trends, and relationships between variables that influenced passenger survival.

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook (VS Code)

## 📂 Files in this Repository
| File | Description |
|------|-------------|
| `Titanic_Data.ipynb` | Jupyter Notebook with all code, charts, and observations |
| `titanic_data.csv` | Dataset used for the analysis |
| `Task5_EDA_Report.pdf` | Final PDF report with visuals and findings |
| `Task5_EDA_Report.docx` | Word version of the report |

## 🔍 Steps Performed
1. Loaded and explored the dataset using `.info()`, `.describe()`, and `.value_counts()`
2. Identified missing values (Age column had 177 missing entries)
3. Visualized data using:
   - Histogram (Age Distribution)
   - Boxplot (Age vs Survived)
   - Scatterplot (Age vs Fare, colored by Survival)
   - Correlation Heatmap
   - Pairplot (Survived, Pclass, Age, Fare)
   - Countplot (Survival Count by Sex)
4. Wrote observations for each visual
5. Summarized overall findings

## 📊 Key Findings
- About **38%** of passengers survived overall. females had a much higher survival rate than males.
- **Passenger class (Pclass)** mattered — 1st class passengers survived more than 3rd class.
- **Fare** correlated with survival — higher fare passengers survived more, tying back to class.
- **Age** alone did not show a strong pattern, though very young children had slightly better survival odds.
- Age has 177 missing values that would need handling in further analysis.

## 🎯 Outcome
Gained hands-on skill in finding patterns, trends, and anomalies in real-world data using univariate, bivariate, and multivariate visual analysis techniques.
