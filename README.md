# KAIM Week 3 Challenges Task 4
## AlphaCare Insurance Solutions (ACIS) Marketing Analytics Repository

Welcome to the AlphaCare Insurance Solutions (ACIS) Marketing Analytics Repository! This repository contains the code, data, models, and analysis related to our project aimed at optimizing marketing strategies and identifying low-risk targets for potential premium reductions in the South African car insurance market.

## Project Overview

Our primary objective is to leverage historical insurance claim data to perform predictive and risk analytics. By employing statistical modeling, machine learning, and hypothesis testing, we aim to:

- Identify low-risk customer segments for premium optimization.
- Explore geographic and demographic trends.
- Optimize marketing strategies by understanding feature impacts on customer behavior.

This repository is divided into four key branches, each representing a distinct task. Below is an outline of the different branches, tasks, methodologies, and tools used.

## Branch Overview

### 4. `task-4` - Statistical Modeling & Machine Learning

**Objective**: Build predictive models to forecast total claims and optimize premium values using features such as car characteristics, owner details, and location.

**Key Tasks**:
- **Data Preparation**: Handle missing values, encode categorical variables, and split data into training and test sets.
- **Modeling**: Implement models including Linear Regression, Random Forests, and Gradient Boosting Machines (GBMs).
- **Evaluation**: Compare models using metrics such as accuracy, precision, recall, and F1-score.
- **Feature Importance**: Analyze the most influential features using SHAP or LIME for interpretability.

## Project Structure Overview

```bash

|   .dvcignore
|   .gitignore
|   dvc.lock
|   dvc.yaml
|   files.txt
|   folder-structure.txt
|   README.md
|   requirements
|   requirements.txt
|   Docker.txt
+---.dvc
|   |   .gitignore
|   |   config
  
|   +---.vscode
|   |       settings
+---Data
|   |   .gitignore
|   |   raw.dvc
|   |   
|   +---interim
|   |       .gitignore
|   |       MachineLearningRating_v3.txt
|   |       
|   +---processed
|   |       cleaned_data.csv
|   |       
|   +---raw
|   |       MachineLearningRating_v3.zip
|   |       
|   \---visualizations
|           correlation_heatmap.png
|           geographical_trends.png
|           outliers_boxplot.png
|           premium_by_cover.png
|           
+---notebooks
|       eda_notebook.ipynb
|       hypothesis_testing_notebook.ipynb
|       model_training.ipynb

|       __init__.py
|       
+---scripts
|   |   data_processing.py
|   |   data_visualization.py
|   |   hypothesis_testing.py
|   |   load_data.py
|   |   eda.py
|   |   evaluation.py
|   |   feature_importance.py
|   |   hypothesis_testing.py
|   |   modeling.py
|   |   save_model.py
|   |   __init__.py

+---src
|       __init__.py
|       main.py
|       
\---tests
        test_data_processing.py
        test_hypothesis_testing.py
        test_eda.py
        __init__.py
        


```


## How to Get Started

### Prerequisites

- Python 3.8+
- Libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `xgboost`, `dvc`, `shap`, `lime`, `seaborn`,`scipy`, etc.
- Jupyter Notebook for running the analysis.
- DVC for data version control.

### Setup Instructions

1. **Clone the Repository**

   ```bash

   git clone https://github.com/Alebachew424/insurance-risk-analytics
   cd insurance-risk-analytics

   git checkout task-4
   ```

2. **Install Dependencies**
3. **Set up DVC (if working on task-2 & 3)**

   ```

2. **Install Dependencies**
3. **Set up DVC (if working on task-2)**
4. **Run Notebooks**


## Key Insights and Recommendations

- **Risk Analysis**: Early insights suggest significant risk differences between provinces and gender groups, which could be used to tailor marketing strategies and adjust premiums.
- **Geographic Trends**: Zipcode-level analysis shows disparities in claim rates and insurance types, suggesting location-based pricing strategies.
- **Predictive Modeling**: Random Forest and XGBoost models showed strong predictive power for total claims, with features such as car age and geographic location being the most important predictors.

## Conclusion

This project provides actionable insights to optimize marketing strategies, improve customer segmentation, and enhance premium pricing models for AlphaCare Insurance Solutions. By leveraging data analytics, statistical testing, and machine learning, we aim to drive business growth and customer satisfaction.

Thank you for using this repository! For any issues or contributions, please feel free to submit a pull request or contact the project maintainers.
Thank you for using this repository! For any issues or contributions, please feel free to submit a pull request or contact the project maintainers.
