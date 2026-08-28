🎯 The practice contains an exploratory data analysis (EDA) and statistical breakdown of survey data examining digital banking adoption and user satisfaction among Generation Z. The project processes raw survey data collected directly from 385 respondents, cleaning multi-item Likert-scale responses into core analytical constructs and summarizing key consumer behavior trends.

📊 The dataset comprises primary survey responses collected from 385 Gen Z digital banking users, evaluated across 31 features categorized into demographic indicators and multi-item Likert constructs

Key Methodology & Code Pipeline
Data Ingestion & Cleaning: Loaded raw Excel survey metrics via pandas, handled column headers using regular expressions (re) to standardize survey codes, and verified null values.

Construct Aggregation: Computed mean composite scores for the primary analytical dimensions (Trust, Security, Convenience, Efficiency, and Satisfaction) across individual Likert items.

Descriptive Statistics: Extracted central tendencies (means and standard deviations) to compare how construct perceptions rank relative to one another based on the 385 survey responses.

🛠️ Technologies
Python
Pandas
NumPy
Jupyter Notebook
