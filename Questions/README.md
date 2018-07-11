Machine Learning Questions
==========================

### 1. What is the *curse of dimensionality*? Why is it important in modeling?
As the number of features or dimensions grows, the amount of data that we need to generalize accurately grows exponentially.

Non-parametric approaches, such as KNN, tend to perform poorly as the number of features grow [[2]](#Gareth2013).

[Curse of dimensionality explained](http://www.visiondummy.com/2014/04/curse-dimensionality-affect-classification/)
> The more features we use, the more sparse the data becomes such that accurate estimation of the classifier’s parameters (i.e. its decision boundaries) becomes more difficult.

>  Overfitting is a direct result of the curse of dimensionality.

> The smaller the size of the training data, the less features should be used

> Classifiers that tend to model non-linear decision boundaries very accurately (e.g. neural networks, KNN classifiers, decision trees) do not generalize well and are prone to overfitting. Therefore, the dimensionality should be kept relatively low when these classifiers are used. If a classifier is used that generalizes easily (e.g. naive Bayesian, linear classifier), then the number of used features can be higher since the classifier itself is less expressive.

### 2. How to estimate the test error of the model?

### 3. What is the difference between feature engineering, feature selection and feature extraction?

[stackexchange](https://datascience.stackexchange.com/questions/29006/feature-selection-vs-feature-extraction-which-to-use-when)

### 4. How to evaluate model performance?

### 5. How to deal with missing values and why is it necessary?

[Jason Brownie](https://machinelearningmastery.com/handle-missing-data-python/)
* Constant value that has a meaning in the domain.
* A value from randomly selected record.
* A mean, median or mode value for the column.
* A value estimated by another predicitve model.

Bibliography
============
<a name="Hastie2009"> [1] Trevor Hastie, Robert Tibshirani & Jerome Friedman, *The elements of statistical learning*, Springer (2009). </a>
<br>
<a name="Gareth2013"> [2] James Gareth, Daniela Witten, Trevor Hastie & Robert Tibshirani, *An introduction to statistical learning with applications in R*, Springer (2013).
<br>
<a name="Murphy2012"> [3] Kevin P. Murphy, *Machine learning: a probabilistic perspective*, The MIT Press (2012). </a>
<br>
<a name="Bishop2006"> [4] Christopher M. Bishop, *Pattern Recognition and machine learning*, Springer (2006). </a>
<br>
<a name="Mohri2012"> [5] Meshryar Mohri, Afshin Rostamizadeh & Ameet Talwalkar, *Foundations of machine learning*, The MIT Press (2012).
