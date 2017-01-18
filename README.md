# Overview

This report is the report for the Machine Learning Course Project, from the John Hopkins University on Coursera.

You can find the report : 
- [here in pdf](https://github.com/breenbo/DS_08_Machine_Learning/blob/master/report.pdf "pdf format")
- here in html, 
- or [here for the .rnw file](https://github.com/breenbo/DS_08_Machine_Learning/blob/master/report.rnw "Rnoweb file"), containing all reproducible code and research.

***

# Work quick explanation

This study contains some functions to :
- download datas from the web and them them on working directory
- take list of algorithms to test with the caret package. The shortcuts of algorithms must be understable by the train function.
- train and test the algorithms, with cross validation on 10 folders, repeated 3 times, on a small datasets to order them on their accuracy
- select the 5 bests models, then train and test them on the global dataset, with cross-validation on 10 folders, repeated 3 times
- let the scientist to choose which model is finally the best

PreProcess, metrics, seed, control method, number of folder and repeats are arguments of functions, and can be tweaked.


Please note that I'm not a native english, but I'm working on it ;-)


Thanks for reading.
Bruno Berrehuel.
