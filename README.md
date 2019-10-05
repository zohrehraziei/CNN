# CNN

---------- 

 Author: Zohreh Raziei 

-----------
- To Evaluate the performance of model along with the accuracy, we have used the f1-score as an evaluation metrics. The F1 score can be interpreted as a weighted average of the precision and recall, where an F1 score reaches its best value at 1 and worst score at 0.
- F1-score is the harmonic mean of Precision and Recall and gives a better measure of the incorrectly classified cases than the Accuracy Metric.
- Stratified 10-fold cross validation has been used to train our model. It helps in knowing how the machine learning model would generalize to an independent data set. It can be also considered as resampling procedure. K-fold cross validation can be said as mirror to the performance of an algorithm.
- As the dataset is too large, Model need to be trained on GPU for the best result. By increasing the number of epochs accuracy is increasing. As we have limited resources to train the model current results are as following :  
![](https://i.imgur.com/yeF8c2X.png) 
