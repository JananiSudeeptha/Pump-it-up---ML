# github link: https://github.com/JananiSudeeptha/Pump-it-up---ML.git

# Explotary Data Analysis, pre/post-processing
Using the python libraries an explotary data analysis was done for the features of the dataset. 
After the exploration some of the anomalies in the dataset were detected. Some features had ouliers. The existence of outliers were identified using the statistical description generated using the panads library. Some features had missing values. Missing values of the categorical data were replaced by "UNKNOWN" value. Instead of NaN, in some numerical features there were many values recorded as'0'. Those were replaced by some statistical values such as mean and mode. When going through the dataset, typing errors were identified in some features. Those were corrected by relacing with a corrected value. By plotting graphs, Heat maps and grouping, the importance of features were identified. Using mathematical transformation, new feature generated to identify how old the pump is. After cleaning the dataset by removing similar features, the categorical features were encoded using categorical encoders.

# models
Two models were trained using the dataset; Random Forest, XGBoost. The best performing model was Random forest and its hyper parameters were tuned accordingly. Althoug the resampling was done for the class imbalance, it does not improve the accuracy of the predictions.
