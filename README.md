# Breast-Cancer-Survival-Prediction

## Overview:

The project aims to predict breast cancer survival rates based on various features such as age, gender, protein levels, tumor stage, histology, and surgical type. It involves preprocessing the data, training a CatBoost model, hyperparameter tuning, and deploying a Streamlit app for interactive predictions.

## Key Components:

#### Model Training: The train.py script is responsible for training the breast cancer survival prediction model using data ingestion, preprocessing, and the CatBoost classifier.

#### Data Preprocessing: The preprocessing.py module handles data preprocessing tasks, including imputation, scaling, and encoding categorical features.

#### Hyperparameter Tuning: The hyperparameters.py script utilizes Optuna for hyperparameter optimization of the CatBoost model.

#### Streamlit App: The streamlit_app.py file contains code for a Streamlit web application enabling users to input patient data and receive survival rate predictions.

#### Data Ingestion: The ingest_data.py script fetches and preprocesses the dataset for training and evaluation.

#### Notebooks: The notebook.ipynb notebook provides exploratory data analysis and experimental code snippets.

#### Utility Scripts: Additional scripts such as run_pipeline.py for executing the training pipeline are included for automation.

## Usage:

#### Training: Execute run_pipeline.py to initiate the model training process. Ensure dependencies listed in requirements.txt are installed.

#### Model Demonstration: Run streamlit_app.py to launch the Streamlit app and interactively predict breast cancer survival rates.

#### Contribution: Contributions to the project are welcome. Fork the repository, make changes, and submit pull requests following the provided guidelines.

## License:
This project is licensed under the MIT License, granting users the freedom to use, modify, and distribute the software.
