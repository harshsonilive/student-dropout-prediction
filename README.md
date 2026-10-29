# Student Dropout Prediction Using Machine Learning

## Overview
A predictive analytics project that uses machine learning to classify students based on academic, socioeconomic, and behavioral indicators, with the goal of identifying students at risk of dropping out.

## Objectives
- Analyze factors associated with student dropout.
- Preprocess data and perform exploratory data analysis.
- Train and compare machine learning classification models.
- Evaluate models using accuracy, precision, recall, F1-score, and ROC-AUC.
- Explore decision-threshold optimization for dropout-risk detection.

## Models Evaluated
- Logistic Regression
- Random Forest
- Gradient Boosting
- MLP Neural Network
- XGBoost

## Key Results
- Test accuracy: 81.55%
- Test ROC-AUC: 0.8206
- Cross-validation ROC-AUC: 0.8210 ± 0.0097
- Dropout-class recall after threshold optimization: 76.6%
- Dropout-class F1-score after threshold optimization: 0.591

These results are from the evaluated Logistic Regression model and its threshold-tuning experiment. Refer to the notebook for the complete methodology and evaluation.

## Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## How to Run
1. Clone this repository.
2. Install the dependencies listed in `requirements.txt`.
3. Open `notebooks/student_dropout_prediction.ipynb` in Jupyter Notebook.
4. Update the dataset path if necessary.
5. Execute the notebook cells in order.

## Potential Application
The model could support educational early-warning systems by helping institutions identify students who may benefit from additional academic support. Predictions should support, not replace, human assessment.

## Limitations
Model performance depends on dataset quality and representativeness. Predictive associations do not establish causation, and real-world deployment requires additional validation.

## Author
Harsh
