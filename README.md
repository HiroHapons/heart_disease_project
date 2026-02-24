# Clinical Analysis: Heart Disease Indicators
Research and data exploration of cardiovascular health markers using Python.

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on a clinical dataset of 303 patients to identify correlations between physiological markers—such as Age, Maximum Heart Rate, and Cholesterol, and the presence of Heart Disease (AHD). 

## Technical Stack
- Language: Python 3.x
- Libraries: Pandas, Seaborn, Matplotlib
- Environment: Jupyter Notebook / VS Code

## Domain Context
As a student pursuing a dual degree in Computer Science and Biology, I approached this dataset as a clinical study rather than a standard data exercise. Understanding the biological basis of cardiovascular stress (such as the relationship between age and cardiac output) allows for more informed feature selection and a more nuanced interpretation of the statistical results.

## Key Medical Insights
- Age vs. Heart Rate: A statistically significant negative correlation (-0.39) was observed between Age and Maximum Heart Rate.
- Diagnostic Trends: Patients diagnosed with Heart Disease (AHD = Yes) consistently demonstrated lower Maximum Heart Rates compared to healthy patients within the same age brackets.
- Feature Interconnectivity: Correlation mapping indicates that Thalamic stress and Chest Pain types are high-value variables for future predictive modeling.

## Project Structure
- Data/: Contains the clinical dataset (heart_disease_clinical.csv).
- Notebook/: Contains the exploratory analysis and visualization scripts.
- README.md: Project documentation and findings.

## How to Run
1. Clone the repository: git clone [Your-Link-Here]
2. Install necessary dependencies: pip install pandas seaborn matplotlib
3. Execute the notebook: Notebook/analysis.ipynb
