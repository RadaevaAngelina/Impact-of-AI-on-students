# Impact of Generative AI on Students: Exploratory Data Analysis

Exploratory analysis of how generative AI usage relates to student academic
performance, exam anxiety and skill retention. University project (HSE University,
Faculty of Computer Science), built with Python, pandas, matplotlib and seaborn.

## Dataset
Kaggle dataset **"AI Impact on Students"** (`ai_student_impact_dataset.csv`):
50,000 students, 16 features, no missing values.

| Type | Features |
|---|---|
| Numeric | `Pre_Semester_GPA`, `Post_Semester_GPA`, `Weekly_GenAI_Hours`, `Traditional_Study_Hours`, `Skill_Retention_Score`, `Tool_Diversity`, `Perceived_AI_Dependency`, `Anxiety_Level_During_Exams` |
| Categorical | `Major_Category`, `Year_of_Study`, `Primary_Use_Case`, `Prompt_Engineering_Skill`, `Institutional_Policy`, `Burnout_Risk_Level` |
| Boolean | `Paid_Subscription` |

## What was done
1. Data quality checks (missing values, dtypes, categorical consistency)
2. Descriptive statistics (min, max, mean, median, std)
3. Visualizations: histogram, box plot, scatter plot, pie, stacked and grouped
   bars, line plots
4. Feature engineering:
   - `GPA_Change = Post_Semester_GPA - Pre_Semester_GPA`
   - `AI_Study_Ratio = Weekly_GenAI_Hours / (Weekly_GenAI_Hours + Traditional_Study_Hours) * 100`
5. Two hypothesis checks with grouped comparisons

