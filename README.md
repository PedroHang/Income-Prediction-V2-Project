# Income Prediction v2

[Kaggle](https://www.kaggle.com/code/hangpedro/income-prediction-v2-project)

## Overview

This project consists of the analysis of a dataset containing data from thousands of fictional people. The objective of the analysis and modeling is to predict the income (renda) of the subject.

Note: The dataset was originally available in Portuguese (pt-BR), but it is completely understandable.

## Dataset Description

| Variable                | Description                                                                            | Type         |
| ----------------------- |:--------------------------------------------------------------------------------------:| ------------:|
| `data_ref`              | Date of data collection                                                                | datetime     |
| `id_cliente`            | Unique customer ID                                                                     | int          |
| `sexo`                  | Customer's gender                                                                      | object       |
| `posse_de_veiculo`      | Owns a vehicle or not                                                                  | bool         |
| `posse_de_imovel`       | Owns property or not                                                                   | bool         |
| `qtd_filhos`            | Number of children the customer has                                                    | int          |
| `tipo_renda`            | Income type: Entrepreneur, Salaried, Public Servant, Pensioner, or Scholar             | object       |
| `educacao`              | Education level: Primary, Secondary, Incomplete Higher, Complete Higher, or Postgraduate | object     |
| `estado_civil`          | Marital status: Single, Married, Widowed, Union, or Separated                          | object       |
| `tipo_residencia`       | Residence type: House, Governmental, With parents, Rent, Studio, or Communal           | object       |
| `idade`                 | Customer's age                                                                         | int          |
| `tempo_emprego`         | Customer's employment duration (in years)                                              | float        |
| `qt_pessoas_residencia` | Number of people living in the customer's residence                                    | float        |
| `renda`                 | Customer's income (Dependent variable)                                                 | float        |

## Project Structure

The project follows a structured approach to analyze and model the dataset:

1. **Data Cleaning**
   - Handling missing values
   - Data type conversion

2. **Exploratory Data Analysis (EDA)**
   - Descriptive statistics
   - Data visualization (histograms, boxplots, scatter plots)

3. **Feature Engineering**
   - Creating dummy variables for categorical data
   - Scaling numerical features

4. **Model Building**
   - Splitting data into training and test sets
   - Model selection and training (e.g., Linear Regression, Decision Trees, Random Forest)
   - Model evaluation using metrics such as R-squared, Mean Absolute Error (MAE), and Mean Squared Error (MSE)

5. **Principal Component Analysis (PCA)**
   - Implementing PCA to reduce dimensionality
   - Plotting cumulative explained variance

## Installation

To run this project, ensure you have the following libraries installed:

- pandas
- numpy
- scikit-learn
- matplotlib
- statsmodels
- seaborn
- scipy

You can install them using pip:

```bash
pip install pandas numpy scikit-learn matplotlib statsmodels seaborn scipy
