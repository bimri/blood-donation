# Blood Donation Prediction Project

## Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
    - [Step 1: Clone the Repository](#step-1-clone-the-repository)
    - [Step 2: Explore the Dataset](#step-2-explore-the-dataset)
    - [Step 3: Build and Evaluate the Model](#step-3-build-and-evaluate-the-model)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository contains a Python-based project aimed at predicting whether an individual donates blood based on various features such as `Recency`, `Frequency`, `Monetary`, `Time` and the target variable `Donated_Blood`. The project uses a logistic regression model for prediction purposes.

## Objectives

- Load and explore a dataset containing information about blood donors.
- Conduct Exploratory Data Analysis (EDA) to understand the distribution and relationships within the dataset.
- Develop a logistic regression model for predicting blood donation behavior.
- Assess the model's performance through metrics like accuracy and confusion matrix.

## Requirements

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Installation

1. Ensure Python is installed on your system.
2. Create a virtual environment and activate it:
`bash python3 -m venv env source env/bin/activate` # On Windows use `env\Scripts\activate`
3. Install the required packages using pip:
```bash pip install pandas matplotlib seaborn scikit-learn```

## Usage

### Step 1: Clone the Repo

Clone this repository to your local machine:
```bash git clone https://github.com/bimri/blood-donation.git cd blood-donation```

### Step 2: Explore the Dataset

Run the Jupyter notebook ('blood.ipynb') to load the dataset, preform intial exploratory data analysis, and analyze the data distribution and correlations.
bash jupyter notebook blood.ipynb

### Step 3: Build and Evaluate the Model

Follow the steps outlined in the Jupyter Notebook to prepare the dataset, split it into training and test sets, intialize the model and train it with logistic regression model, make predictions, and evaluate the model's performance.


## Contributing

Contributions are welcome. Please feel free to submit a pull request or open an issue if you encounter any problmes or have suggestions for improvement.


## License

This project is licensed under the MIT License.