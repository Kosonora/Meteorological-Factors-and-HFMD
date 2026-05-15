# Folder Description
This folder contains the results of an analysis of the association between meteorological factors and HFMD. 
The analysis of the association with meteorological factors covers two aspects:
* For all meteorological factors, meteorological variables with lags of 0, 1, and 2 were constructed, and Spearman’s correlation coefficient
was used in conjunction with Bonferroni correction and VIF analysis to examine the time-delay effects between meteorological factors and HFMD.
* By incorporating meteorological factors associated with the time-delay effect into the analytical framework, we used a Poisson GAM model to
analyze the nonlinear relationship between meteorological factors and HFMD.
# Folder Contents
* Code for data analysis, built in Notebook mode.
* The results of the data analysis are saved in .csv format.
* The computational models built during the data analysis process are stored in .joblib format and can be read using the joblib library in Python.
