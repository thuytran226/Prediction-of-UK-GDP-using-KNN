Project's topic: "Prediction UK GDP using KNN regression".

The process is summarized as follows:

- Quarterly data of UK GDP from Q1 1980 to Q4 2019 is collected from various sources.
- Data is splited with 2 different ratios: train/test 70/30 and 80/20
- Gridsearch with 10-fold CV is used for turning hyperparameters
- Out-of-sample forecast for one-step-ahead using KNN regression is performed to get the prediction.
- The results from KNN predictions are compared to the results from ARIMA and VAR.
