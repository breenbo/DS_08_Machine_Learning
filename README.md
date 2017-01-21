# Overview

This report is the report for the [Machine Learning Course Project](https://www.coursera.org/learn/practical-machine-learning/home/welcome), from the John Hopkins University on Coursera.

You can find the report : 

- for LaTeX users : [here in pdf](https://github.com/breenbo/DS_08_Machine_Learning/blob/master/report.pdf "pdf format") and the [.rnw file](https://github.com/breenbo/DS_08_Machine_Learning/blob/master/report.rnw "Rnoweb file"), containing all reproducible code and research.
- for Markdown users : [here in html](https://github.com/breenbo/DS_08_Machine_Learning/report.html) and the [.Rmd file](https://github.com/breenbo/DS_08_Machine_Learning/report.Rmd)

***

# Work quick explanation

This study contains some functions to :
- download datas from the web and them them on working directory
- take list of algorithms to test with the caret package. The shortcuts of algorithms must be understable by the train function.
- train and test the algorithms, with cross validation on 10 folders, repeated 3 times, on a small datasets to order them on their accuracy
- select the 5 bests models, then train and test them on the global dataset, with cross-validation on 10 folders, repeated 3 times
- let the scientist to choose which model is finally the best

PreProcess, metrics, seed, control method, number of folder and repeats are arguments of functions, and can be tweaked.


21 algorithms have been tested with this functions, and the best one, the *Bagged CART model*, chosen with a accuracy of more than 98 % and a computation of 160 seconds with parallel work on 6 cores i7.


Please note that I'm not a native english, but I'm working on it ;-)


Thanks for reading. 

[Bruno Berrehuel](https://fr.linkedin.com/in/brunoberrehuel).
