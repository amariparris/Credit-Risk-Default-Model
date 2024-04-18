# Credit-Risk-Default-Model

## Introduction
The **Credit Risk Default Model** is a Python-based machine learning project aimed at predicting the probability that a borrower will default on a loan. This project utilizes various predictive models to analyze a borrower's credit history, evaluate risk, and provide insights into the potential default risks.

## Motivation
This project was developed to assist financial institutions in making informed decisions regarding loan approvals. By accurately predicting credit risk, lenders can minimize losses associated with defaults while providing fair opportunities to potential borrowers. The model's predictions can help tailor the terms of loans such as interest rates based on individual risk profiles.

## Prerequisites
Before you can run this project, you need to meet the following requirements:
- **Python 3.8** or above
- **pip** (Python package installer)
- A basic understanding of Python and machine learning concepts is beneficial but not required.

## Installation

To set up the project environment:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/amariparris/Credit-Risk-Default-Model.git
   cd Credit-Risk-Default-Model
   
2. **Install the required libraries:**
Run the following command to install the dependencies listed in requirements.txt:
   ```bash
   pip install -r requirements.txt
This command will install all the necessary Python packages defined in requirements.txt, which includes libraries like pandas, scikit-learn, matplotlib, and numpy.

## Usage 

The primary purpose of the provided scripts is to reproduce the results of our experiments with various machine learning models. To do this, follow these steps:

1. **Unzip the Data Files:**
Navigate to the Data folder and unzip the provided CSV files:
   ```bash
   cd Data
   unzip Final_version_cleaned.csv.zip
   unzip model_data.csv.zip

2. **Run the Scripts:**
Return to the main project directory and run the Jupyter notebooks to train the models:
   ```bash
   cd ..
   jupyter notebook randomforest.ipynb
   # Run the above command for each notebook
   jupyter notebook Log_Regression_ensemble.ipynb
   jupyter notebook 6.XG_Boost.ipynb
   
These steps will train the models using the data extracted from the zipped files and should reproduce the experiment results as documented in the notebooks.

### Example of Use

After setting up and activating the project as described above, the Jupyter notebooks can be used to train the models and visualize the results. Each notebook corresponds to a different modeling approach (Random Forest, Logistic Regression Ensemble, and XG Boost), providing insights into their performance and accuracy regarding credit risk prediction. Once trained the models can also be applied to new data for predictions. 

## Contributing

Contributions to the Credit Risk Default Model are welcome. Here’s how you can contribute:

Filing an issue: Use GitHub Issues to report bugs, request features, or ask for clarification on the documentation.
Submitting a pull request: If you want to add features or resolve issues, you can make changes to the project and submit a pull request.
Please adhere to this project's code style guidelines, including commenting on your code and using meaningful variable names.

## Libraries and Tools Used

Pandas: For data manipulation and analysis.
Scikit-Learn: For implementing machine learning algorithms.
Matplotlib: For creating static, interactive, and animated visualizations in Python.
Numpy: Library for numerical calculations.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
