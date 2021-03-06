## Ensemble learning  
Ensemble methods are machine learning methods that aggregate the predictions of a group of base learners in order to form a single learning model. For example, imagine that each person in this video is a trained machine learning model and notice the average of their predictions is a much more accurate prediction that the individual predictions. In this lecture we will consider two types of ensemble concepts and methods. Namely,  
- Bagging

- Random Forests  


The algorithm of ensemble learning is really simple: take the majority vote (for classification) or average (for regression) of all weak learners, as the prediction of ensemble learning model. Weak learners could be any kinds of machine learning models, so ensemble learning is quite flexible.

But there's a key problem for ensemble Learning: learners of ensemble learning should not be similar wit each other, or there's no difference between only use one learner. That's to say, learners should be uncorrelated. This is very similar to the diversity opinion these days, as people from different religions, cultures and so on may have very different ideas, but together team with high diversity could do a good job.

To deal with this peoblem, bootstrap aggregating is a good way to reduce the correlation of training data among different learners.  


Briefly, random forest is a kind of ensemble learning which all learners are decision trees and each decision tree uses training data sample from bootstrap aggregating. It was first proposed by Ho in 1995.

Random forest is a great ensemble learning model, since each weak learner (a decision tree) is super easy and fast to train, and by bootstrap aggregating and other methods (like selecting a subset of features in each split), each decision tree is highly uncorrelated, so the results of weak learners are uncorrelated, but the majority vote or average prediction is good.  

### Advantages/Benefits of ensemble methods  
1. Ensemble methods have higher predictive accuracy, compared to the individual models.  
2. Ensemble methods are very useful when there is both linear and non-linear type of data in the dataset; different models can be combined to handle this type of data.
3. With ensemble methods bias/variance can be reduced and most of the times, model is not underfitted/overfitted.  
4. Ensemble of models is always less noisy and is more stable.  
### Disadvantages of Ensemble learning  
1. Ensembling is less interpretable, the output of the ensembled model is hard to predict and explain. Hence the idea with ensemble is hard to sell and get useful business insights.  
2. The art of ensembling is hard to learn and any wrong selection can lead to lower predictive accuracy than an individual model.  
3. Ensembling is expensive in terms of both time and space. Hence ROI can increase with ensembling.  


## Datasets
- The Palmer penguins dataset by Allison Horst, Alison Hill, and Kristen Gorman.  
The goal of the Palmer Penguins dataset is to replace the highly overused Iris dataset for data exploration & visualization.datasets contain data for 344 penguins. There are 3 different species of penguins in this dataset, collected from 3 islands in the Palmer Archipelago, Antarctica.
