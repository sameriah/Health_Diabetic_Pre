# Health_Diabetic_Pre
**Description: **

The growing burden of undiagnosed or late-diagnosed diabetes poses a critical challenge in preventive healthcare. Using medical records from a dataset of Pima Indian women aged 21+, the goal is to build a model that can accurately predict whether an individual has diabetes or not, based on diagnostic features like blood glucose, BMI, and insulin levels.

**Approach:**
Loaded the dataset and performed data cleaning, missing values, dropping zero variance columns, and reformatting the data for better readability and analysis; Ensuring the date column was in the correct date format, and converting any text columns with only two unique values into binary type.

Explored Variable Distributions: Used histograms and boxplots to understand spread and detect outliers.

Analyzed Data Types: Created frequency plots to compare counts of integer vs float variables.

Checked Class Imbalance: Plotted target variable (Outcome) to observe diabetic vs non-diabetic distribution

Visualized Feature Relationships: Created scatter plots between key variables (e.g., Age vs Glucose).

Performed Correlation Analysis: Built a heatmap to examine relationships and multicollinearity.

Decided Validation Strategy: Used stratified sampling or cross-validation to ensure model generalization.

Trained Multiple Models: Compared KNN, logistic regression, and other classifiers for performance.

Evaluated Performance: Analyzed accuracy, sensitivity, specificity, and AUC scores.

Created Tableau Dashboard: Built charts like pie plots, scatter plots, histograms, and bubble charts.

