Students Performance EDA

This project performs **Exploratory Data Analysis (EDA)** on the **Students Performance dataset** using Python. The analysis explores patterns in student scores across different categories like gender, parental education, lunch type, and test preparation course.  

The goal is to understand the data, visualize key trends, and derive insights for better interpretation.

🧾 Dataset Overview

- Contains scores of students in Math, Reading, and Writing.  
- Includes categorical variables: `gender`, `race/ethnicity`, `parental level of education`, `lunch`, `test preparation course`.

📊 Analysis Performed

1. Data Cleaning & Inspection
   - Checked for missing values and duplicates.
   - Explored unique categories for categorical variables.

2. Feature Engineering
   - Created `total score` and `average score` columns.

3. Exploratory Data Analysis
   - Histograms and KDE plots for distributions.
   - Violin plots for subject-wise score distribution.
   - Pie charts for categorical variable distribution.
   - Bar charts comparing averages by gender.

4. Key Insights
   - Some students scored full marks in individual subjects.
   - Gender differences and parental education influence scores.
   - Lunch type has visible impact on performance.

🧩 Libraries Used

```bash
numpy
pandas
matplotlib
seaborn
