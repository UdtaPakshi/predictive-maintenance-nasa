# documenting my key take aways while building this project!! 
Dataset has multiple multivariate time series and has training and test subsets. 
Data is from many engines of the same type. 
Each engine starts with normal levels of wear and tear (not considered fault condition).
Contaminated with sensor noise.
There are 3 operational settings included in dataset which have big effect on engine performance.
Engine operates normally at the start of each time series but later develops faults at some point. Fault grows till engine/system failure in training dataset.



## objective
The objective is to predict the number of remaining operational cycles before failure in test set. In other words, the goal is to predict the number of operational cycles after the last cycle for which the engine will continue to operate before failure. 

