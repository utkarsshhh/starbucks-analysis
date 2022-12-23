# starbucks-analysis
This project is an application analysing the past data and predicting the best promotional offers for any user


## Introduction
I have built this project using past data from [Starbucks](https://www.starbucks.com) that I got from [Udacity](https://www.udacity.com/) for this project.
The aim of this project is to predict that if a customer is provided with an offer whether they will avail the benefits of the offer or not. 
The results of this analysis can have the following applications:

1. The customers that are responsive towards the rewards can be kept engaged by sending them offers that they are most likely to avail.
2. To reduce providing benefits to users who are engaged in regular transactions regardless of the offers.


## Usage

### Installation
The code is in a Jupyter Notebok __model_creation.ipynb__ and requires Python 3.9 to run it. The Jupyter Notebook can be run in browser or installed from [here](https://jupyter.org)

### Data
The dataset is present in __data__ folder in the project directory. The folder is not present in the repository because of data privacy concerns.

### Libraries
The following libraries have been used for the application:
1. [pandas](https://pandas.pydata.org)
2. [numpy](https://numpy.org)
3. [matplotlib](https://matplotlib.org)
4. [scikit-learn](https://scikit-learn.org)
5. [seaborn](https://seaborn.pydata.org)
6. [pickle](https://docs.python.org/3/library/pickle.html)
7. [xgboost](https://xgboost.readthedocs.io/en/stable/)


## Result
Classification models from scikit-learn library have been used to predict whether the user will avail the benefits of the offer or not using multi target classification. The trained model in a pickle format as __updated_model.pkl__ . The detailed analysis and result can be found [here](https://medium.com/@utkarshpadia/how-to-improve-customer-engagement-by-analysing-past-data-27a702ff8f60)







