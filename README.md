# Data Analysis - Preprocessing and Transformation 🪄

## Overview
In this project, I thoroughly analyzed a given dataframe, employing various techniques to extract insights, transform the data, and draw conclusions. The analysis process included both preprocessing and data transformation steps to ensure data quality and enable deeper insights.

## Analysis and Transformation Highlights:

### Initial Data Exploration:
- **Dataframe Import**: Loaded the dataframe from the provided `store_income_data_task.csv` file.
- **Observations**: Examined the first five records to understand the dataframe's structure and content.
- **Handling Missing Values**: Identified missing values per column to assess data quality.
- **Missing Data Analysis**: Investigated missing data in specific columns (`store_email`, `department`, and `country`) and provided insights into the reasons behind the missingness.
- **Classification of Missing Data**: Categorized missing data based on columns, providing rationale for each classification.

### Data Transformation:
- **Feature Engineering**: Created new features from existing data to enhance the predictive power of the dataset.
- **Data Aggregation**: Combined multiple records into summarized metrics to provide a clearer picture of trends and patterns.
- **Column Transformation**: Applied log transformation to positively skewed columns to reduce skewness and normalize data distribution.
- **Encoding Categorical Variables**: Transformed categorical data into numerical form using encoding techniques like One-Hot Encoding and Label Encoding to make the data suitable for machine learning models.

### Data Normalization and Standardization:
- **Scaling Techniques Decision**: Determined whether normalization or standardization was appropriate for specific columns within the dataset.
- **Data Scaling**: Applied the appropriate scaling method (normalization or standardization) to the selected column ("EG.ELC.ACCS.ZS").
- **Comparison of Original and Scaled Data**: Visualized both the original and scaled data to assess the impact of scaling and gain deeper insights.

### Data Visualization:
- **Visualization of Distributions**: Visualized the distribution of a specific column (`EG.ELC.ACCS.ZS`) from the countries dataset using a histogram to better understand data patterns.
- **Before and After Transformation Analysis**: Compared visualizations before and after data transformation to understand how changes impacted data structure.

Throughout the analysis, the goal was to uncover valuable insights and patterns through effective data transformation, enabling more accurate decision-making and facilitating further exploration.

To view the Jupyter Notebook containing the code and outputs for this project, please refer to `data_analysis.ipynb` in this repository.

For any inquiries or feedback, feel free to reach out.

## 🛠 Skills
- Data Import and Handling
- Exploratory Data Analysis (EDA)
- Data Preprocessing and Transformation Techniques
- Feature Engineering
- Data Visualization
- Communication and Documentation
