# Customer Purchase Prediction using Support Vector Machine (SVM)

## Overview

This project focuses on predicting whether customers of a company will purchase one of the company's products. This prediction is based on the available customer features. We utilize a dataset named "Customer_Purchases," which contains information about a sample of these customers. The dataset comprises the following features:

- 'Gender': Customer's gender.
- 'Age': Customer's age.
- 'Income': Customer's income (in $ per year).
- 'Purchase': Product purchase (1 if the customer buys the product, 0 otherwise).

In this repository, we implement a Support Vector Machine (SVM) for classification. The goal is to create a predictive model for customer purchase behavior.

## Dataset

You can find the dataset in the file named "Customer_Purchases.csv" in the "data" directory.

## Project Structure

This repository includes the following files and directories:

- `data/`: Contains the dataset file.
- `Customer_Purchase_Prediction_SVM.ipynb`: Jupyter Notebook with the code for data preprocessing, SVM model training, and evaluation.
- `README.md`: You are currently reading the project's README file.

## Usage

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Open the Jupyter Notebook, `Customer_Purchase_Prediction_SVM.ipynb`, to run and explore the code.
3. The notebook will guide you through data preprocessing, model training, and evaluation.

Feel free to customize and adapt the code to your specific use case.

## Dependencies

This project uses the following Python libraries:

- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn

You can install these libraries using pip:

```bash
pip install scikit-learn pandas numpy matplotlib seaborn
