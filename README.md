# Random-Forest
I have applied random forest algorithm to the Boston dataset to predict **medv**. In other words, **medv is the label**, and the other **13 variables** in the dataset are the attributes.

Then I Split the dataset randomly into **two equal parts**, which will serve as the training set and the test set. 

Generated B = 100 bootstrapped training sets (BTS) from the training set

Used each BTS to train for a decision tree of height h = 3. At each node of random forest I do not considering all attributes, but only a sample of them.

Calcualted the training MSE and test MSE


