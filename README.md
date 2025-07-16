# Loan Eligibility Prediction

This project predicts whether a loan application should be approved based on applicant information. The goal is to assist financial institutions in automating the loan approval process using machine learning.

## Project Overview

The project uses a dataset containing information such as gender, marital status, income, loan amount, and credit history. The steps involved include:

* Data loading and cleaning
* Exploratory data analysis (EDA)
* Feature engineering
* Model training and evaluation
* Prediction generation

## Folder Structure

```
Loan_Eligibility_Prediction/
├── Loan_Eligibility_Prediction.ipynb
├── README.md
├── requirements.txt
└── data/
    └── loan_dataset.csv  # Place your dataset here
```

## Technologies Used

* Python 3.x
* Jupyter Notebook
* pandas, numpy
* seaborn, matplotlib
* scikit-learn

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Loan_Eligibility_Prediction.git
   cd Loan_Eligibility_Prediction
   ```

2. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook Loan_Eligibility_Prediction.ipynb
   ```

## Usage

* Load the dataset into the notebook (CSV format).
* Run all cells to train and evaluate models.
* You can modify the input data section to predict eligibility for custom applicants.

## Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (optional)

## License

This project is licensed under the MIT License.


