# Techniques to handle missing values and ensure data quality
After understanding how EDA helps assess dataset completeness, the next step is addressing missing values to ensure reliable insights. In financial risk analytics, incomplete or inconsistent data can skew predictions and lead to incorrect risk assessments. When handling missing data, it is critical to first analyze the reason for missingness—whether it is random, systematic, or indicative of underlying biases. While GenAI models can assist in detecting patterns and suggesting imputation strategies, statistical techniques (e.g., mean, median, or regression-based imputation) remain the industry standard due to their transparency and reproducibility. Blindly applying GenAI-generated imputation without understanding data context can introduce significant bias.

## What are the common causes of missing data?
1️⃣ **Random errors** (e.g., a system glitch fails to record a payment).

2️⃣ **Skewed data collection** (e.g., high-income customers are less likely to disclose salary details).

3️⃣ **Customer behavior** (e.g., financially distressed individuals may avoid reporting debt).

Understanding the cause helps determine the best approach for handling missing values.

## How to handle missing values:
1️⃣ Deleting missing data – If only a small percentage of data is missing, removing incomplete entries may be the best approach. However, this can reduce the sample size.

2️⃣ Imputation (replacing missing values) – Mean, median, or mode imputation fills gaps with typical values.
Forward or backward filling uses existing data trends to estimate missing entries.

3️⃣ AI-Assisted Imputation – 

» GenAI models can help detect patterns and suggest imputation strategies and statistical techniques (e.g., mean, median, or regression-based imputation).

» AI tools can also suggest synthetic data where needed, provided data privacy is maintained.

Beyond missing values, check for<br>
  duplicates,<br>
  inconsistent formatting, and<br>
  logical errors (e.g., high credit scores with multiple missed payments). By maintaining data integrity, you ensure that predictive models generate fair and accurate delinquency assessments.
