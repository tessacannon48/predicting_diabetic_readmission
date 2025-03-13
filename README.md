# About the Project

This project applies machine learning to predict hospital readmission using the UC Irvine Diabetes dataset. The dataset, collected from 130 U.S. hospitals between 1999 and 2008, consists of 101,766 patient encounters with 50 features (11 numeric and 39 categorical). The project involves detailed dataset exploration, custom data transformations, nested cross-validation, and model interpretation. Three models are compared—SVC, Logistic Regression with L1 (Lasso), and Random Forest—with an alternative pipeline featuring SelectKBest for feature selection.

# Repository Structure

root/
├── README.md         # This file
├── predicting_diabetic_readmission.ipynb    # Jupyter Notebook containing all code for data processing, modeling, evaluation, and visualization.
├── requirements.txt    # Python package dependencies.

# Getting Started

The requirements.txt file needs to be installed to run the notebook: 

######
    !pip install requirements.txt
    
# Data Source

Download the dataset from the UC Irvine Machine Learning Repository: https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008

# Notes
- Dataset Subset: Only 50% of the dataset is used to reduce computational load.
- This notebook was completed as part of an assignment for a course at University College London. All of the code is my original work.

# Contact

Author: Tessa Cannon - tessacannon48@gmail.com

For any questions or feedback, feel free to reach out or open an issue in the repository.
For questions or further information, please contact [your-email@example.com].
