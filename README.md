#  BITCOIN ADDRESS DETECTION
![bitcoin-3089728_1920](https://user-images.githubusercontent.com/90555069/141302997-084bf37b-8082-4361-9f7e-edc7882a44a3.jpeg)

## Introduction
Bitcoin is a cryptocurrency based on peer-to-peer technology that involves no central authority like a bank.
For all intents and purposes, transactions done over bitcoin cannot be traced. Now you might understand, why this is perfect for scammers.
In this project, we will use AI to analyse how these transactions take place and try to build models that predict if a given Bitcoin address is being used for malicious intent or not.
## Problem statement
Given a bitcoin address along with some meta-data pertaining to that address, we are challenged to predict if that address has been used to receive ransoms in the past.
## Data Description
The dataset that to be tested is from the [UCI Machine Learning Repository](https://archive-beta.ics.uci.edu/ml/datasets/bitcoinheistransomwareaddressdataset) that contains parsed Bitcoin transaction graphs from 2011 until 2018 This data-set contains labelled data of transactions and if whether they are white or if they belong to a class of Ransomware.

## Tools
- Software Platform :Jupyter Notebook
- Programming Language: Python
- Python Libraries:
    - Statistics libraries
        - Sklearn
        - Statsmodels
    - Data manipulation libraries
        - Pandas
        - Numpy
    - Visualization libraries
        - Matplotlib
        - Seaborn
    - Storage libraries
        - Pickle
