# Predicting SEP Events Using Machine Learning Timeseries Classifiers

Definitions:

a. Events are those strong SEPs crossing the 10 pfu threshold in the GOES 10 MeV channels.

b. Non-events are weak SEPs with GOES 10 MeV protons below 10 pfu threshold.

Source code documentation:

1. data:
This folder contains all the time series (events and non-events) required in the jupyter notebook.
2. labels.csv:
This file contains the binary labels of the dataset.
3. TS_Classifiers_60_min.ipynb:
This jupyter notebook contains the code of our model architecure including reading the input, training the models and generating predictions. The model currently runs for short-term (~one hour) prediction of SEP events.