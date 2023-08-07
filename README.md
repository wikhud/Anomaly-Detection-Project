# AnomalyDetectionProject
The task of this project is to investigate various anomaly detection methods in real-life datasets.

For the research, following anomaly detection methods were chosen:
* OneClassSVM()
* IsolationForest()
* EllipticEnvelope()

From http://odds.cs.stonybrook.edu/ following datasets were selected:
* 'mammography' - characteristics: large amount of data; very small number of dimensions; small percentage of outliers
* 'arrhythmia' - characteristics: small amount of data; large number of dimensions; a very high percentage of outliers
* 'ionosphere' - characteristics: small amount of data; small number of dimensions; average percentage of outliers

The anomaly detecion methods are selceted with tuning alghoritms such as Grid Search and Randomized Search. Combinations of 3 parameters of 3 different values are tested.
In case of difference in results of search methods, the one with the better best_score_ is selected for further research. In addition, for each dataset, there are several types of scoring for both tuning methods.

For each method, for each dataset, the ROC curve and confusion matrix are displayed.
