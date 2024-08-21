# Groundwater Quality Classification using Support Vector Machines (SVM)

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Results](#results)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview

This project aims to classify groundwater quality data collected over three years (2018, 2019, and 2020) using Support Vector Machines (SVM) with various kernels. The classification is based on features like SAR (Sodium Absorption Ratio) and EC (Electrical Conductivity), and the goal is to predict water quality labels.

## Dataset

The datasets used in this project include:
- `ground_water_quality_2018_post.csv`
- `ground_water_quality_2019_post.csv`
- `ground_water_quality_2020_post.csv`

Each dataset contains multiple features related to groundwater quality, collected from various locations.

## Installation

To run the code in this repository, you'll need to have Python installed along with the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install the required libraries using the following command:


 pip install pandas numpy matplotlib seaborn scikit-learn

## Usage

### 1. Clone the Repository
First, clone this repository to your local machine:


git clone https://github.com/yourusername/groundwater-quality-classification.git
cd groundwater-quality-classification

Prepare the Data

Ensure the necessary CSV files (ground_water_quality_2018_post.csv, ground_water_quality_2019_post.csv, ground_water_quality_2020_post.csv) are available in the working directory.

Run the Analysis

You can run the analysis by executing the Jupyter notebook or Python script provided in the repository. The code includes all steps from data preprocessing to model evaluation.

Explore the Results

The results will include various performance metrics like accuracy, precision, recall, F1-score, and confusion matrices, which are visualized using heatmaps.

Exploratory Data Analysis (EDA)
Before diving into model training, an exploratory data analysis (EDA) was performed, including:

Visualizing relationships between features and target labels.
Checking the distribution of features using histograms and KDE plots.
Identifying and handling outliers.
Model Training and Evaluation
##The project uses SVM models with different kernels:

Linear Kernel
Polynomial Kernel
RBF (Radial Basis Function) Kernel
Sigmoid Kernel
Steps Involved:

##Data Preprocessing:

Handle missing values by filling with the mean.
Log transformation for select features to reduce skewness.
Feature selection based on correlation with target labels.
Model Training:

Train SVM models on the preprocessed data using different kernels.
Split the data into training and testing sets to evaluate performance.
Model Evaluation:

Evaluate models using accuracy, precision, recall, F1-score, and confusion matrices.
Hyperparameter tuning using Grid Search with cross-validation.
Results
The results are presented as:

Best parameters and accuracy scores for each SVM model.
Confusion matrices for each kernel, visualized using heatmaps.
Detailed classification reports showing precision, recall, and F1-score for each class.
License
This project is licensed under the MIT License. See the LICENSE file for details.

##Acknowledgments
This project utilizes groundwater quality data obtained from public datasets. Special thanks to the data providers for making this project possible.
