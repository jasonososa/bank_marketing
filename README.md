## Bank marketing campaign 
#### This is an exercise I did using a dataset were classes are very imbalanced.

I tried working with the imbalanced dataset and using an algorithm robust to imbalance classes, but failed to to get good perfomance (precision and recall < 0.65).
I then downsampled the majority class, and used three classifiers that should performed great fr this classification task (logistic regression, SVC, random forest). 
The performance for each of them was great (precision > 0.85 and recall > 0.9). I optimized each classifier for recall, as I didn't want to miss any positive class.
I them use drop-out feature to identify the most important features using the random forest classifier.
