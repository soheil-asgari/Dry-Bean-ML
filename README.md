# Dry Bean Classification

This repository contains code for classifying dry beans using machine learning techniques. Dry beans are an important agricultural product and being able to accurately classify them can have significant applications in agriculture and food processing industries.

## Dataset

The dataset used in this project is the Dry Bean Dataset, which consists of various physical properties of different classes of dry beans. The dataset is stored in an Excel file named `Dry_Bean_Dataset.xlsx` located in the `data` directory.

## Getting Started

To run the code, follow these steps:

1. Clone this repository to your local machine:

https://github.com/soheil-asgari/Dry-Bean-ML.git


2. Navigate to the project directory:

cd dry-bean-classification


3. Install the required dependencies. It's recommended to create a virtual environment before installing dependencies:

pip install -r requirements.txt


4. Run the Jupyter Notebook `main.ipynb`. This notebook contains the entire pipeline from data loading and preprocessing to model training and evaluation.

## Overview of Files

- `main.ipynb`: Jupyter Notebook containing the main code for data analysis, preprocessing, model training, and evaluation.
- `data/Dry_Bean_Dataset.xlsx`: Excel file containing the Dry Bean Dataset.
- `requirements.txt`: File listing all the Python dependencies required to run the code.

## Data Analysis and Preprocessing

The notebook starts with data analysis and visualization to understand the distribution and characteristics of the dataset. It includes:
- Loading the dataset using Pandas.
- Exploratory data analysis using various plots.
- Preprocessing steps such as handling missing data, feature engineering, and scaling.



## Model Training and Evaluation

The notebook implements several machine learning models using scikit-learn. It includes:
- Model selection using cross-validation.
- Hyperparameter tuning using GridSearchCV.
- Evaluation of the best model using classification metrics and confusion matrix.

## Results

The best model achieved an accuracy of [92.29%]%. However, it should be noted that there are certain challenges in accurately classifying some bean classes due to their similarities.



