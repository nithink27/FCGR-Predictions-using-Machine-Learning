# FCGR-Predictions-using-Machine-Learning
Fatigue Crack Growth Rate Predictions of Ti6Al4V which is processed using LPBF and post Processed.
The data is collected from the Literature (Cain et al) where variables are Post Processing Technique and Built Orientation.
Data is taken from the FCGR graphs, which are plotted after conducting the experiments.
Making this data into Regression Problem, trying to predict the FCGR with 3 variables which are Stress Intensity factor, Post Processing technique, Built Orientation.
Label Encoded the Categorical columns and Normalized the Numerical columns for faster convergence.
Used 4 ML Algorithms and compared R2 scores
Used the better performing algorithm for Hyper Parameter Tuning
Used the best Hyperparameters on the better performing algorithm for Feature Importance.
