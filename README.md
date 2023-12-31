# Anomaly Detection Project
The aim of this project was to do a research on performance of various anomaly detection methods, on several datasets.

Selected anomaly detection methods are:
* OneClassSVM()
* IsolationForest()
* EllipticEnvelope()

Hyperparameters of these methods are optimized with tuning alghoritms, such as Grid Search and Randomized Search. Combinations of 3 parameters, of 3 different values are tested.
In case of differences in results of search methods, the one with better best_score_ is selected for further research. In addition, for each dataset, there are several types of scoring for both tuning methods.

Following datasets were selected from http://odds.cs.stonybrook.edu/:
* 'mammography' - characteristics: large amount of data; very small number of dimensions; small percentage of outliers
* 'arrhythmia' - characteristics: small amount of data; large number of dimensions; very high percentage of outliers
* 'ionosphere' - characteristics: small amount of data; small number of dimensions; average percentage of outliers

For each method, for each dataset, the ROC curve and confusion matrix are displayed.
