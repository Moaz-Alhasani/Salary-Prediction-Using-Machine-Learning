# Salary Prediction

Overview
- Predict employee salary using demographic and job-related features.
- Includes data preprocessing, exploratory data analysis (EDA), and regression models (Decision Tree, Random Forest).

Dataset
- Source: Salary_Data_Based_country_and_race.csv (included in repo).
- Features: Age, Gender, Country, Education Level, Job Title, Years of Experience, Race, Salary.

Main Steps
1. Data cleaning: remove nulls, drop unnecessary columns.
2. Feature engineering: group job titles and education levels into categories.
3. Encoding: label-encode categorical features.
4. Scaling: standardize continuous features (Age, Years of Experience, Salary).
5. Modeling: train/test split, hyperparameter tuning (GridSearchCV), Decision Tree and Random Forest regressors.
6. Evaluation: R2, MSE, MAE, RMSE and prediction vs actual plots.

How to run
- Create a virtual environment (recommended) and install dependencies:
  pip install -r requirements.txt
- Open and run the notebook:
  jupyter notebook SalaryPrediction.ipynb
- Or run analyses/scripts provided in the repo.

Dependencies
- Python 3.8+
- numpy, pandas, matplotlib, seaborn, scikit-learn, jupyter

Results
- Models are evaluated using R2, MSE, MAE and RMSE on the test set.
- Hyperparameter tuning performed for Decision Tree (GridSearchCV) to improve performance.

File Structure (example)
- SalaryPrediction.ipynb
- Salary_Data_Based_country_and_race.csv
- requirements.txt
- README.md

Contributing
- Feel free to open issues or pull requests. Keep changes focused and include tests or notebook examples when relevant.

License
- Specify a license in LICENSE file (e.g., MIT) or remove this section if not applicable.