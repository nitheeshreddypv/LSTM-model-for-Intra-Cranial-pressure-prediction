Objective:continuous prediction of intracranial pressure using a lstm model which is fine tuned for this work.
Dataset:charis dataset from physionet repository or download it by using the wfdb package in python.
final outcome: events classification as high or low based on the future 10 prediction values.
workflow:downloading the data ,preprocessing the data, building a lstm model, predicting the icp values and events classification and finally evaluating the model.
for more information about the base paper:https://ieeexplore.ieee.org/document/9786851
title of base paper:Machine Learning-Based Continuous Intracranial Pressure Prediction for Traumatic Injury Patients
NOTE:
1.i have implemented the code completly in google colab and you may use any one of your choice.
2.comments are neatly documented along with the code itself in the .ipynb file.
3. install the required packages.
