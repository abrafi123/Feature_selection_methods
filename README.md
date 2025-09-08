# Feature Selection Techniques

This repository contains different feature selection techniques implemented in Jupyter Notebooks. Feature selection is an important step in machine learning pipelines that helps to:

- Improve model performance  
- Reduce overfitting  
- Make models more interpretable  

## Notebooks

1. Feature_importance.ipynb  
   - Implements Feature Importance using tree-based models (e.g., Random Forest, XGBoost)  
   - Ranks features based on their contribution to the predictive model  
   - Helps identify which variables have the most impact on the target variable  

2. chi_square.ipynb  
   - Demonstrates the Chi-Square Test for feature selection  
   - Works for categorical input features and categorical target variables  
   - Useful for identifying the dependency between variables  

3. correlation_matrix_with_heatmap.ipynb  
   - Creates a Correlation Matrix for numerical features  
   - Visualizes correlation using a heatmap  
   - Helps detect multicollinearity and redundant features  

4. f_classif.ipynb  
   - Applies ANOVA F-test (f_classif) for feature selection  
   - Useful for numerical features with categorical target variables  
   - Selects features based on statistical significance  

## Requirements

- Python 3.x  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib / Seaborn  

## How to Use

1. Clone the repository:  
   ` git clone https://github.com/your-username/your-repo-name.git
2. Open Jupyter Notebook:
 jupyter notebook
3. Run the .ipynb files step by step to understand each method.
