AlphaCare Insurance Solutions Data Analytics

This repository contains the code and analysis for AlphaCare Insurance Solutions, focusing on data analytics related to insurance policies, premiums, and claims. The project involves several key tasks including Exploratory Data Analysis (EDA), Hypothesis Testing, Statistical Modeling, and the use of version control with Git and DVC. This project is aimed at extracting actionable insights to enhance business strategy and customer experience in the insurance industry.
Table of Contents

    Project Overview
    Tasks
        Task 1: Git and GitHub
        Task 2: Data Version Control (DVC)
        Task 3: A/B Hypothesis Testing
        Task 4: Statistical Modeling
    Folder Structure
        notebooks
          hypothesis-testing
          eda
        models
         stat_modeling
    Installation
    Usage
    Contributing
    License

Project Overview

This project aims to perform a series of data analysis and modeling tasks related to AlphaCare's insurance policies. The focus is on using Exploratory Data Analysis (EDA), statistical hypothesis testing, and statistical modeling to uncover insights that will guide business decisions.
Tasks
Task 1: Git and GitHub

    Created a Git repository for the project and performed version control using Git.
    Set up Continuous Integration/Continuous Deployment (CI/CD) pipelines using GitHub Actions.
    Performed Exploratory Data Analysis (EDA) to uncover insights related to insurance policies and claims, including univariate, bivariate, and multivariate analyses.

Task 2: Data Version Control (DVC)

    Installed and configured DVC for version control of datasets.
    Created local remote storage and tracked data changes with DVC.
    Pushed data to the remote storage using DVC to ensure versioned datasets.

Task 3: A/B Hypothesis Testing

    Conducted A/B testing to validate hypotheses related to insurance policy risk differences across provinces, zip codes, gender, and other features.
    Performed statistical tests (e.g., t-tests, chi-squared tests) to accept or reject null hypotheses.

Task 4: Statistical Modeling

    Performed data preparation including handling missing values and feature engineering.
    Built and evaluated machine learning models, including Linear Regression, Decision Trees, Random Forest, and XGBoost.
    Used SHAP and LIME for feature importance analysis and model interpretation.

Folder Structure

The repository contains the following key folders:
notebooks

This folder contains Jupyter notebooks for performing data analysis and visualizations. The analysis is divided into the following notebooks:

    EDA: Contains code for performing Exploratory Data Analysis (EDA) on the dataset.


    hypothesis-testing

    This folder contains scripts related to A/B hypothesis testing, where statistical methods are applied to test various business assumptions.
models

This folder contains the code for training and evaluating different machine learning models such as Linear Regression,  Random Forest, and XGBoost.
Installation

To get started with this project, clone the repository and install the necessary dependencies.

    Clone the repository:

git clone https://github.com/duresaguye/AlphaCare-Insurance-Solutions-data-analytics.git

Navigate into the project directory:

cd AlphaCare-Insurance-Solutions-data-analytics

Install required Python packages:

pip install -r requirements.txt

Install DVC (for version control of data):

pip install dvc

Initialize DVC and set up remote storage:

    dvc init
    dvc remote add -d localstorage /path/to/your/local/storage

Usage
Running Notebooks

To run the notebooks for EDA and hypothesis testing, open the Jupyter notebooks in the notebooks folder:

    Start Jupyter Notebook:

    jupyter notebook

    Open and run the notebooks in the browser.

Running Models

To train and evaluate models, navigate to the models folder and run the respective scripts. The models include Linear Regression, Random Forest, and XGBoost.

    stat_modeling.ipynb

Contributing

If you would like to contribute to the project, please fork the repository, make your changes, and submit a pull request. Contributions are welcome!
License

This project is licensed under the MIT License.
