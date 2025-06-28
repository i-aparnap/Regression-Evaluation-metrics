# Regression-Evaluation-metrics
California Housing Regression Models – README
📌 Purpose of the Assignment
This project involves using the California Housing dataset from Scikit-Learn to build and evaluate various regression models that predict the median house price based on features like income, house age, population, and location.

The goal is to:

Load and preprocess the dataset

Explore the data (EDA)

Implement and compare multiple regression algorithms

Evaluate model performance using standard metrics

Tune hyperparameters using cross-validation

Select the best model with proper justification

📂 Files Included
File Name	Description
main.ipynb or model_script.py	Main code file with all steps implemented
README.md	This file — summary and instructions
requirements.txt (optional)	Python packages used (scikit-learn, pandas, etc.)

🛠️ Models Implemented
Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Support Vector Regressor (SVR)

Each model is:

Trained using the California housing data

Evaluated using R² Score, MSE, MAE

Tuned using GridSearchCV or RandomizedSearchCV

Compared based on performance

⚙️ How to Run the Code
🐍 Requirements
Make sure you have the following Python libraries installed:

scikit-learn
pandas
matplotlib
seaborn
numpy
If needed, install them with:
pip install -r requirements.txt
▶️ Running in Jupyter Notebook
Open Anaconda Navigator or run:

jupyter notebook
Navigate to the project folder and open main.ipynb

Run each cell in order

✅ Final Conclusion
After comparing all models, Gradient Boosting Regressor was selected as the best model, achieving the highest R² score (~0.67). It showed better generalization and handled non-linear relationships effectively.

🙋 Author & Acknowledgements
Developed by: APARNA P

Dataset Source: [sklearn.datasets.fetch_california_housing()]
