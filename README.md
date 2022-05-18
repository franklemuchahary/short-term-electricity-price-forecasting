# Very Short Term Electricity Price Forecasting #

This repository contains the python code for a two level bootstraped model obtained using a combination of Relevance Vector Machines and Extreme Gradient Boosting which is used for predicting hour-ahead Electricity Prices. It also contains the code for other models the performances of which were tested against this ensemble model for the same task. There is a *.py* and *.ipynb* version of all the code files. The models trained have been stored as a pickle file to avoid retraining for testing purposes. 

1) *Very Short Term Price Forecasting- RVM.ipynb (Very+Short+Term+Price+Forecasting-+RVM.py)* is the main code file.
2) loaddata1.xls contains ISO New England electricity dataset of 2012.
3) loaddata2.xls contains ISO New England electricity dataset of 2013.
4) loaddata3.xls contains ISO New England electricity dataset of 2014.
5) CrudeOil.csv contains crude oil prices dataset from Quandl.
6) naturalgas.csv contains natural gas prices dataset from US Henry Hub.
7) *ARIMAX_FeatureImp* directory has the ARIMAX implementation and Feature Importance calculation using Mutual Information Value

The findings have been published in Elsevier Applied Energy. DOI: https://doi.org/10.1016/j.apenergy.2019.05.062
