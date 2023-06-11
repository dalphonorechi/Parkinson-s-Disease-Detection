
# Prediction of Parkison's Disease : Logistic Regression, Decision Tree Classifier.

In this project, we will be trying to develop an end-to-end data science application. The aim of the project is to predict if a person has Parkison's Disease using biomedical voice measurements based on the following variables.

* name - ASCII subject name and recording number.
* MDVP:Fo(Hz) - Average vocal fundamental frequency.
* MDVP:Fhi(Hz) - Maximum vocal fundamental frequency.
* MDVP:Flo(Hz) - Minimum vocal fundamental frequency.
* MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP - Several measures of variation in fundamental frequency
* MDVP:Shimmer, MDVP:Shimmer(dB), Shimmer:APQ3, Shimmer:APQ5, MDVP:APQ, Shimmer:DDA - Several measures of variation in amplitude.
* NHR, HNR - Two measures of ratio of noise to tonal components in the voice.
* RPDE, D2 - Two nonlinear dynamical complexity measures.
* DFA - Signal fractal scaling exponent.
* spread1, spread2, PPE - Three nonlinear measures of fundamental frequency variation.


### What we are trying to predict.

* status - Health status of the subject (one) - Parkinson's, (zero) - healthy.