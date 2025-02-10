# GenZ Dating App Data Analysis

## Project Overview
This project analyzes data from a GenZ dating app to understand user behavior, preferences, and trends. The dataset undergoes cleaning, exploratory data analysis (EDA), and feature engineering to prepare it for future machine learning applications.

## Tasks & Methodology

### Task 1: Data Quality Assessment
- Checked for duplicate entries (none found).
- Identified and handled missing values in `Primary_App`, `Secondary_Apps`, and `Challenges`.
- Standardized categorical values (e.g., consistent gender and location formatting).

### Task 2: Dataset Documentation
- Created a **data dictionary** defining each column.
- Documented all preprocessing steps to ensure reproducibility.

### Task 3: Relationship Analysis
- **Correlation Analysis**: Heatmap of numerical features.
- **Pivot Tables & Groupby Aggregations**: Summarized data based on gender, age, and location.
- **Stacked Bar Charts**: Visualized app preferences by gender.
- **Urban vs. Rural Trends**: Compared dating app usage patterns.

### Task 4: Detecting Bias
- Identified potential demographic overrepresentation.
- Analyzed whether gender bias affects dating app preferences.

### Task 5: Feature Engineering
- Encoded categorical variables using one-hot encoding.
- Normalized numerical variables for modeling.
- Created a new feature, `Multiple_Apps`, to indicate multi-app users.

## Results & Insights
- The **18-22 age group** is the most active on dating apps.
- **Metro users** dominate app usage, with fewer users from rural areas.
- Different gender groups show varying **app preferences**.
- Users frequently engage with **multiple dating apps**.

## Next Steps
- Further bias detection and mitigation strategies.
- Build predictive models for user engagement.
- Expand analysis to include user satisfaction trends.

## Repository Structure
- `GenZ_DatingApp_Data_Cleaned.csv` - Processed dataset.
- `Assignment.ipynb` - Jupyter Notebook containing all analysis steps.
- `version_1.csv` - First cleaned version of the dataset.
- `README.md` - Project summary and documentation.

## Contribution & Feedback
Feel free to contribute by improving data analysis techniques or suggesting new insights. Open a pull request or start a discussion!

# ML-EDA
