## 💡 What is exploratory data analysis?
Exploratory data analysis (EDA) is the first step in understanding a dataset before applying any predictive models or making business decisions.<br>
EDA helps analysts uncover patterns, trends, inconsistencies, and missing values to ensure data quality and reliability.<br>

In the context of financial services, EDA plays a crucial role in risk assessment, allowing teams to identify key factors contributing to credit card delinquency and build stronger prediction models. 

### Here is why EDA matters in predicting delinquency:

🚀 Ensures data integrity – Identifies missing values, duplicates, and inconsistencies before analysis.<br>
🚀 Highlights patterns and anomalies – Helps detect trends in customer behavior, such as spending patterns before delinquency.<br>
🚀 Prevents biased models – Reduces the risk of unfair treatment by ensuring diverse data representation.<br>
🚀 Supports better decision-making – Provides Geldium’s Collections and Risk teams with clear insights for proactive customer engagement.<br>
🚀 Without a thorough EDA process, predictive models can be built on flawed data, leading to inaccurate insights, poor risk management, and potentially unfair decision-making.

## 💡 Key steps in conducting EDA
EDA consists of four main steps, which can be enhanced with GenAI tools:

### 1️⃣ Understanding the dataset
Before jumping into analysis, I need to ask myself:

𝟏. What are the key variables (e.g., payment history, income levels, credit utilization)?<br>
𝟐. Are there categorical or numerical data points?<br>
𝟑. Are there missing or inconsistent values?<br>

#### Using GenAI: 
I can use AI-powered summarization tools to quickly scan a dataset and generate an overview. Open AI Tools can help interpret column headers, suggest relevant features, and summarize key statistics.

💡 Example prompt: "Analyze this dataset and provide a summary of key columns, including common patterns and missing values."

### 2️⃣ Identifying missing values and outliers<br>
Incomplete data can lead to poor predictions. Missing values in credit risk datasets may result from human error, system failures, or unreported financial activity.

Here are some common techniques for handling missing data:

Statistical imputation (industry standard): Replace missing values using well-established techniques such as mean, median, or regression-based imputation. (We've provided a resource with further information on imputation below.)<br>
Understanding missingness patterns: Before filling in missing values, determine whether the data is missing completely at random (MCAR), missing at random (MAR), or missing not at random (MNAR) to avoid introducing bias. <br>
Removing irrelevant data: If a feature has excessive missing values and cannot be meaningfully imputed without introducing bias, it may be best to exclude it—but only after assessing its impact on model accuracy and fairness.

#### Using GenAI (for exploration, not direct imputation):

AI-powered tools can automate missing value detection and summarize data gaps, helping analysts assess which variables require attention.<br>
GenAI can suggest potential imputation strategies based on statistical best practices, but final decisions should be validated with domain expertise.<br>
Synthetic data generation may be an option when real data is unavailable, but it should be validated against real-world distributions to prevent bias.<br>

💡 Example prompt: "Identify missing values in this dataset and recommend the best imputation strategy based on industry best practices."

### 3️⃣ Understanding relationships between variables
EDA also involves examining how different features interact. For example:

Do customers with high credit utilization rates have a higher risk of delinquency?<br>
Is there a correlation between income levels and late payments?<br>

#### Using GenAI:
AI models can automate correlation analysis, helping identify key risk indicators.<br>
Instead of manually coding formulas, GenAI can summarize variable relationships in natural language.

💡 Example prompt: "Analyze the correlation between customer income and delinquency risk, summarizing key findings in simple terms."

### 4️⃣ Detecting patterns and risk factors
The final step in EDA is to identify patterns that could impact delinquency prediction. These might include:

Customers who miss one payment often miss multiple.<br>
Younger customers or those with recently opened accounts may have different risk profiles.<br>

#### Using GenAI:
AI models can highlight trends in the data, making it easier to understand how different features contribute to delinquency.<br>
AI-assisted insights can be refined by asking follow-up questions, ensuring that the analysis remains relevant to Geldium’s objectives.<br>

💡 Example prompt: "Analyze trends in late payments and identify the top 3 risk factors associated with delinquency."
