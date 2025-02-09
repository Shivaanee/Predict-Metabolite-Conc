# Predict-Metabolite-Conc
Predict metabolite concentrations from NIR spectral data

## Overview
This project explores various machine learning approaches, including exploratory data analysis (EDA), regression models, neural networks, and the use of unlabeled data for training. The dataset used is provided in `Dataset.xlsx`, and the analysis is carried out through multiple Jupyter notebooks and scripts.

## Files and Structure

### Data
- **Dataset.xlsx**: The original dataset used for training and evaluation.
- **data/** and **modified_data/**: The datasets used for training and evaluation.

### Exploratory Data Analysis (EDA)
- **eda.ipynb**: Initial exploratory data analysis (EDA) to understand the dataset.
- **EDA2.ipynb**: Additional or refined exploratory data analysis. (Also includes the regression models and neural network implementation, and the use of unlabelled data)

### Machine Learning Models
- **automl.ipynb**: Explored automated machine learning (AutoML) implementation for model selection and optimization.
- **regression.ipynb**: Implementation of regression models for predictive analysis.
- **nn.ipynb**: Neural network implementation for classification or regression tasks.
- **NN2.ipynb**: Additionally implemented neural network model.
- **EDA2.ipynb**: Additionally implemented regression models.

### Using Unlabeled Data
- **UsingUnlabelled.ipynb**: Experimented with using unlabeled data in the training process.

## Dependencies
Ensure you have the following installed:
- Python (>=3.7)
- Jupyter Notebook
- Pandas, NumPy, Scikit-learn, TensorFlow/PyTorch
- AutoML libraries - H2O
