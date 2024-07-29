# Customer Churn Prediction and Salary Estimation using ANN

This repository contains the implementation of an Artificial Neural Network (ANN) for customer churn prediction and salary estimation using the `churn_modelling.csv` dataset. The project includes both classification and regression tasks, leveraging TensorBoard for visualization and Streamlit for deployment.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)

## Introduction
The aim of this project is to predict whether a customer will exit (classification) and estimate their salary (regression) using an Artificial Neural Network (ANN). The project utilizes the `churn_modelling.csv` dataset, TensorBoard for better visualization, and Streamlit for deployment.

## Dataset
The `churn_modelling.csv` dataset consists of various customer attributes. The key features used for prediction include:
- Customer ID
- Surname
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Exited (Target for classification)

## Installation
To run this project, you need to have Python installed along with the required libraries. You can install the dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Usage

### 1. Clone this repository:

```bash
git clone https://github.com/Keerthan04/ANN_Churn_ENDtoENd.git

```

### 2. Navigate to the project directory:

```bash
cd ANN_Churn_ENDtoENd
```

### 3.Run the app using Streamlit:

```bash
streamlit run app.py

```
Open your browser and go to http://localhost:8501/ to use the application.
