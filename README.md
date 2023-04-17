# BestTextClassificationAlgo
I compare 4 algorithms to classify text on a small-medium sized news dataset from Scikit-Learn.
## SVM, MNB, random forest, and k-nearest neighbor.
We can see that **SVM** has the highest accuracy among the three algorithms, followed by MNB and random forest and k-nearest neighbor 
(I adjusted the neighbors to 6). 
This suggests that for our small-medium size text dataset, SVM works better. 
However, accuracy is not the only metric we should look at when evaluating a classifier. 
We should also consider other aspects such as precision, recall, f1-score, and confusion matrix.
