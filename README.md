# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Objective:
The goal of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to discover patterns, trends, and relationships among features, especially in relation to passenger survival.

## 🛠️ Tools Used:
- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

## 📂 Dataset:
- **Name**: Titanic Dataset
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data) *(or local upload in Colab)*
- **Features include**: Age, Sex, Pclass, Fare, Survived, Embarked, etc.

## 🔍 Steps Performed:

1. **Data Loading**
   - Read dataset using `pd.read_csv()`

2. **Initial Exploration**
   - Used `.info()` and `.describe()` to understand data types and statistical summaries.
   - Checked distributions using `.value_counts()` for categorical columns like `Survived`, `Pclass`, etc.

3. **Data Visualization**
   - Plotted histograms for Age and Fare distribution.
   - Used boxplots to detect outliers and understand distribution based on survival.
   - Created scatter plots and pairplots to identify relationships between variables.
   - Generated heatmaps to understand correlations between numerical features.

4. **Observations**
   - Added short insights under each plot using Markdown cells in Colab.

5. **Summary of Findings**
   - Survival was higher among women, younger passengers, and higher classes (Pclass 1).
   - Age and Fare had outliers but also showed survival-related patterns.
   - Strong correlation between Fare and Pclass.

## ✅ Outcome:
This project helped develop hands-on experience with EDA using Pandas, Seaborn, and Matplotlib. It also improved my ability to analyze real-world datasets, extract meaningful insights, and prepare for machine learning.

---

