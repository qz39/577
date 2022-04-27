# Logistic Regression  
Logistic regression is a classification algorithm used to find the probability of event success and event failure. It is used when the dependent variable is binary(0/1, True/False, Yes/No) in nature. It supports categorizing data into discrete classes by studying the relationship from a given set of labelled data. It learns a linear relationship from the given dataset and then introduces a non-linearity in the form of the Sigmoid function.  
Logistic regression is also known as Binomial logistics regression. It is based on sigmoid function where output is probability and input can be from -infinity to +infinity.   
## Advantages
- Logistic regression is easier to implement, interpret, and very efficient to train.  
- It makes no assumptions about distributions of classes in feature space.  
- It can easily extend to multiple classes(multinomial regression) and a natural probabilistic view of class predictions.  
- It not only provides a measure of how appropriate a predictor(coefficient size)is, but also its direction of association (positive or negative).  
## Disadvantages  
- If the number of observations is lesser than the number of features, Logistic Regression should not be used, otherwise, it may lead to overfitting.  
- It constructs linear boundaries.  
- The major limitation of Logistic Regression is the assumption of linearity between the dependent variable and the independent variables.  
- It can only be used to predict discrete functions. Hence, the dependent variable of Logistic Regression is bound to the discrete number set.  
# Datasets  
- Wine dataset  
These data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines.  

I think that the initial data set had around 30 variables, but for some reason I only have the 13 dimensional version. I had a list of what the 30 or so variables were, but a.) I lost it, and b.), I would not know which 13 variables are included in the set.  

The attributes are (dontated by Riccardo Leardi, riclea '@' anchem.unige.it )
1) Alcohol  
2) Malic acid  
3) Ash  
4) Alcalinity of ash  
5) Magnesium  
6) Total phenols  
7) Flavanoids  
8) Nonflavanoid phenols  
9) Proanthocyanins  
10) Color intensity  
11) Hue  
12) OD280/OD315 of diluted wines  
13) Proline  

