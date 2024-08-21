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

  ```bash
 pip install pandas numpy matplotlib seaborn scikit-learn

## Usage

### 1. Clone the Repository
First, clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/groundwater-quality-classification.git
cd groundwater-quality-classification
