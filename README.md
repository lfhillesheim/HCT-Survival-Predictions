# CIBMTR - Equity in Post-HCT Survival Predictions

This project aims to improve the accuracy and fairness of survival predictions following hematopoietic cell transplantation (HCT) by leveraging comprehensive clinical and demographic data. It focuses on addressing disparities in healthcare outcomes and optimizing resource allocation.

## Table of Contents


Introduction
Data Description
Project Structure
Installation
Usage
Methodology
Results
Contributing
License
Acknowledgments


## Introduction

Hematopoietic cell transplantation is a critical treatment for patients with severe hematological and immunological diseases. This project seeks to enhance survival predictions post-HCT, ensuring equitable healthcare outcomes and efficient resource utilization. By developing robust predictive models and addressing racial and socioeconomic disparities, this project aims to contribute significantly to medical research and patient care.

## Data Description

The dataset includes a wide range of clinical and demographic variables, such as:

- Disease risk indices
- Genetic compatibility scores
- Comorbidities and medical history
- Demographic information (age, ethnicity, etc.)

These variables are crucial for understanding and predicting patient outcomes post-HCT.

## Project Structure

    ├── data│ ├── raw│ └── processed├── notebooks│ ├── exploratory_analysis.ipynb│ ├── data_preprocessing.ipynb│ ├── modeling.ipynb├── src│ ├── data_preprocessing.py│ ├── modeling.py│ ├── evaluation.py├── README.md└── requirements.txt

## Installation

To set up the project environment, follow these steps:

1. Clone the repository:

        git clone https://github.com/yourusername/hct-survival-predictions.git
2. Navigate to the project directory:

        cd hct-survival-predictions
3. Install the required packages:

        pip install -r requirements.txt

## Usage

1. **Data Preprocessing**: Use the `data_preprocessing.ipynb` notebook to clean and prepare the data.
2. **Exploratory Analysis**: Explore the dataset using `exploratory_analysis.ipynb`.
3. **Modeling**: Train and evaluate predictive models using `modeling.ipynb`.

## Methodology

- **Exploratory Data Analysis (EDA)**: Conducted to understand data distributions and identify patterns.
- **Data Preprocessing**: Included data cleaning, normalization, and encoding of categorical variables.
- **Model Development**: Implemented various machine learning models, including Random Forest and XGBoost, with hyperparameter tuning.
- **Evaluation**: Used metrics such as accuracy, precision, and recall to assess model performance.

## Results

The project successfully developed predictive models that improve the accuracy and fairness of survival predictions post-HCT. Detailed results and model evaluations can be found in the `modeling.ipynb` notebook.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes. Ensure that your code adheres to the project's coding standards and includes relevant tests.

## Acknowledgments

We would like to thank the CIBMTR for providing the data and support for this project. Special thanks to all contributors and collaborators who made this project possible.
