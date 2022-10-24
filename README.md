# Random-Forest Classification

I have applied random forest algorithm to the **Boston dataset** to predict **medv**. In other words, **medv is the label**, and the other **13 variables** in the dataset are the attributes.

CRIM - per capita crime rate by town
ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS - proportion of non-retail business acres per town.
CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX - nitric oxides concentration (parts per 10 million)
RM - average number of rooms per dwelling
AGE - proportion of owner-occupied units built prior to 1940
DIS - weighted distances to five Boston employment centres
RAD - index of accessibility to radial highways
TAX - full-value property-tax rate per $10,000
PTRATIO - pupil-teacher ratio by town
B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT - % lower status of the population
MEDV - Median value of owner-occupied homes in $1000's


Then I Split the dataset randomly into **two equal parts**, which will serve as the training set and the test set. 

Generated **B = 100 bootstrapped** training sets (BTS) from the training set

Used each BTS to train for a decision tree of **height h = 3**. At each node of random forest I do not considering all attributes, but only a sample of them.

Calcualted the **training MSE and test MSE**


