# 📊 Data Analysis and Transformation Project

## 📝 Task
I was tasked with preparing and transforming raw data from the provided `store_income_data_task.csv` file. The objective was to clean the dataset, handle missing data, engineer features, and apply transformations to make it ready for deeper analysis and potential machine learning applications. Additionally, I was asked to uncover meaningful insights and summarise key trends and patterns.

---

## 📋 Plan
To tackle the task systematically, I established the following plan:

1. **Understand the Dataset**:
   - Import the dataset and perform initial exploration to identify structure, anomalies, and key issues such as missing values.

2. **Handle Missing Data**:
   - Identify columns with missing values.
   - Classify the nature of missing data and apply appropriate strategies to address them.

3. **Data Transformation**:
   - Engineer new features to enhance the dataset's predictive power.
   - Aggregate data into meaningful metrics for clearer analysis.
   - Normalise or standardise data to address skewness and ensure comparability.

4. **Encode Categorical Data**:
   - Transform categorical variables into numeric formats using One-Hot and Label Encoding.

5. **Visualisation**:
   - Visualise key variables to understand distributions and transformations.
   - Compare before-and-after states of the data to highlight improvements.

---

## 🚀 Actions Taken

1. **Dataset Exploration**:
   - Imported the dataset and used descriptive statistics to assess structure and content.
   - Identified missing values in key columns such as `store_email`, `department`, and `country`.

2. **Data Cleaning and Handling Missing Values**:
   - Addressed missing values by:
     - Imputing defaults for certain columns.
     - Removing or flagging records with critical missing data.

3. **Feature Engineering**:
   - Created new columns derived from existing data to enhance analysis capabilities.
   - Aggregated multiple records to summarise trends at higher levels (e.g., by department or country).

4. **Data Transformation**:
   - Applied log transformations to normalise skewed data.
   - Scaled numerical columns using standardisation techniques for better comparability.

5. **Categorical Encoding**:
   - Converted categorical variables into numerical formats using One-Hot and Label Encoding, making them machine-learning ready.

6. **Data Visualisation**:
   - Created histograms to explore distributions of key variables before and after transformations.
   - Visualised trends and patterns to validate data quality and uncover insights.

---

## 🔍 Findings and Outcomes

1. **Insights into Missing Data**:
   - Missing values were primarily due to incomplete records in the `store_email` and `department` fields.
   - Addressed by imputing or removing incomplete entries.

2. **Feature Engineering Results**:
   - Newly engineered features provided better predictive value and allowed for more granular trend analysis.

3. **Improved Data Quality**:
   - Normalisation and standardisation reduced skewness, improving the dataset's usability for advanced analysis.

4. **Visualisation Outcomes**:
   - Clear trends and patterns were identified in key metrics.
   - Visual comparisons demonstrated the effectiveness of transformations and cleaning efforts.

---

## 🔧 Skills Demonstrated

- 📥 **Data Import and Handling**: Efficiently loaded and organised raw datasets for analysis.
- 🔍 **Exploratory Data Analysis (EDA)**: Gained insights into the dataset's structure and potential issues.
- 🔧 **Data Preprocessing & Transformation**: Applied advanced cleaning, transformation, and scaling techniques.
- 🚀 **Feature Engineering**: Created new metrics and features to enhance analysis capabilities.
- 📊 **Data Visualisation**: Developed clear and informative visualisations to highlight key trends.
- 🖋️ **Communication & Documentation**: Clearly documented processes, decisions, and findings.

---

For the complete analysis, including code and visual outputs, visit the [Jupyter Notebook](data_preprocessing.ipynb) in this repository.
