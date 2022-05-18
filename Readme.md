# Conversion rate competition

www.datascienceweekly.org is a famous newsletter curated by independent data scientists. Anyone can register his/her e-mail address on this website to receive weekly news about data science and its applications !
The goal of this project is to build a model that allows to predict the conversions (i.e. when a user will subscribe to the newsletter)

They designed a competition aiming at building a model that allows to predict the conversions (i.e. when a user will subscribe to the newsletter). To do so, they open-sourced a dataset containing some data about the traffic on their website. To assess the rankings of the different competing teams, they decided to use the f1-score

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 
See deployment for notes on how to deploy the project on a live system.

### Data

* data_train.csv contains labelled data, which means there are both X (explanatory variables) and Y (the target to be predicted). You will use this file to train the model

* data_test.csv contains "new" examples that have not be used to train the model, in the same format as in data_train.csv but it is unlabeled, which means the target Y has been removed from the file. Once you've trained a model, you will use data_test.csv to make some predictions. 

### Prerequisites

The source code is written in Python 3
The python packages can be installed with pip : pip3 install or !pip install if in jupyter notebook

### Installing

Check the packages needed to run the project in the requirements.txt 


## Deployment

If you need to deploy this repo, you will need to upload the 2 datasets in the repo "data_train.csv" and "data_test.csv"

## Built With

* name of the main notebook : conversion_rate_prediction_AdaBoost.ipynb

## Authors

**Amina Nasri** - [SpeedyAmy](https://github.com/SpeedyAmy)

## Acknowledgments

