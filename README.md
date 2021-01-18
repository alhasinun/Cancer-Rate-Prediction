# Cancer-Rate-Prediction

In this project, we are predicting cancer death rate in US. The data can be acquired from public data on github: https://raw.githubusercontent.com/dphi-official/Datasets/master/cancer_death_rate/Training_set_label.csv.

We are doing supervised learning with different methods before and after hyperparameter tuning and feature selection to get the best result.

Here are the results of each method:\
**MSE Random Forest Test**         =  362.70451119101614\
**MSE Decision Tree Test**         =  741.3705802773657\
**MSE Random Forest test cv**      =  364.9028463985019\
**MSE Boruta**                     =  356.6822673784834

Based on the MSE value above, it can be seen that Random Forest with hyperparameter tuning and feature selection gives the best result. It has MSE of **356.68**, although it is still a large number but for a starter it gives me confidence to do more.

If you want to look more in depth of the process, you can click the ipynb file above.
Thank you, hope you enjoy it!
