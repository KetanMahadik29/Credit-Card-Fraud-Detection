# Credit Card Fraud Detection

This project aims to detect fraudulent transactions in a dataset of credit card transactions using machine learning techniques. The dataset includes features derived from anonymized credit card transactions and labels transactions as either "Normal" or "Fraud."

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Overview
Fraudulent credit card transactions are a significant concern in financial systems. This project leverages machine learning models like Isolation Forest, Local Outlier Factor, and One-Class SVM to identify anomalies that represent fraudulent activities.

## Dataset
- The dataset used for this project is included in a `credit-card.zip` file.
- It contains anonymized transaction data with features `V1`, `V2`, ..., `V28`, as well as `Time`, `Amount`, and `Class`.
- The `Class` column indicates transaction type:
  - `0`: Normal
  - `1`: Fraud

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/KetanMahadik29/credit-card-fraud-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd credit-card-fraud-detection
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Ensure the dataset (`credit-card.zip`) is present in the project directory.
2. Run the Jupyter Notebook to train and evaluate the model:
   ```bash
   jupyter notebook Credit-card-fraud-detection.ipynb
   ```

## Results
- Models evaluated include:
  - **Isolation Forest**
  - **Local Outlier Factor**
  - **One-Class SVM**
- Evaluation metrics include accuracy, precision, recall, and F1 score.
- Visualizations highlight the distribution of transactions and model performance.
