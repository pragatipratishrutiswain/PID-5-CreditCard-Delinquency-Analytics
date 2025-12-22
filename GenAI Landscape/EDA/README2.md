# Techniques to handle missing values and ensure data quality

In the next step I would address the missing values to ensure reliable insights. 

In financial risk analytics, incomplete or inconsistent data can skew predictions and lead to incorrect risk assessments. 

When handling missing data, I would first analyze the reason for missingness—whether it is 

1️⃣ random, or <br>
2️⃣ systematic, or <br>
3️⃣ indicative of underlying biases

While GenAI models can assist in detecting patterns and suggesting imputation strategies, statistical techniques (e.g., mean, median, or regression-based imputation) remain the industry standard due to their transparency and reproducibility. Blindly applying GenAI-generated imputation without understanding data context can introduce significant bias.

## 💡 What are the common causes of missing data?

Missing data can occur due to:

1️⃣ Random errors (e.g., a system glitch fails to record a payment).<br>
2️⃣ Skewed data collection (e.g., high-income customers are less likely to disclose salary details).<br>
3️⃣ Customer behavior (e.g., financially distressed individuals may avoid reporting debt).<br>
4️⃣ Understanding the cause helps determine the best approach for handling missing values.<br>

## 💡 How to handle missing values:

### 👉 Deleting missing data
If only a small percentage of data is missing, removing incomplete entries may be the best approach. However, this can reduce the sample size.

### 👉 Imputation (replacing missing values)
➡️ Mean, median, or mode imputation fills gaps with typical values.<br>
➡️ Forward or backward filling uses existing data trends to estimate missing entries.

### 👉 AI-Assisted Imputation
➡️ GenAI models can help detect patterns and suggest imputation strategies and statistical techniques (e.g., mean, median, or regression-based imputation).<br>
➡️ AI tools can also suggest synthetic data where needed, provided data privacy is maintained.<br>
➡️ Beyond missing values, I check for duplicates, inconsistent formatting, and logical errors (e.g., high credit scores with multiple missed payments).<br>
➡️ By maintaining data integrity, I ensure that predictive models generate fair and accurate delinquency assessments.
