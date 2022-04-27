# Linear Regression  
![alt](https://files.realpython.com/media/fig-lin-reg.a506035b654a.png)  
Linear regression is a linear model, e.g. a model that assumes a linear relationship between the input variables (x) and the single output variable (y). More specifically, that y can be calculated from a linear combination of the input variables (x).  

When there is a single input variable (x), the method is referred to as simple linear regression. When there are multiple input variables, literature from statistics often refers to the method as multiple linear regression.

Different techniques can be used to prepare or train the linear regression equation from data, the most common of which is called Ordinary Least Squares. It is common to therefore refer to a model prepared this way as Ordinary Least Squares Linear Regression or just Least Squares Regression.  
## Advantages
- Linear regression performs exceptionally well for linearly separable data  
- Easier to implement, interpret and efficient to train  
- It handles overfitting pretty well using dimensionally reduction techniques, regularization, and cross-validation  
- One more advantage is the extrapolation beyond a specific data set  
## Disadvantages  
- The assumption of linearity between dependent and independent variables  
- It is often quite prone to noise and overfitting  
- Linear regression is quite sensitive to outliers  
- It is prone to multicollinearity  

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
10)Color intensity  
11)Hue  
12)OD280/OD315 of diluted wines  
13)Proline  
