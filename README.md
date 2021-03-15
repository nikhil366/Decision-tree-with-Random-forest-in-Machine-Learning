# Decision-tree-with-Random-forest-in-Machine-Learning
Basically we will  understand how Decision tree and random Forest is working with Machine Learning. 

 # Decision Tree
So before work with Decision Tree we have to understand few factors to work with Decision Tree :
1. Impurity
2. Information Gain (information is measure of purity)


# Points 
1. feature that needl less information or in pure condition it will be over root node.
2. We have to measure impurity or purity of data or sample by which we can say which one is our root node.
3. Decision tree algorithm is a tree where nodes represents features(attributes), branch represents decision(rule) and leaf nodes represents outcomes(discrete and continuous).

# Measure impurity in sample
1. Entropy
2. Gini index/ Gini impurity

# Entropy
Entropy is amount of information is needed to accurately describe the some sample. So if sample is homogeneous, means all the element are similar than Entropy is 0, else if sample is equally divided than entropy is maximum.

# Gini index/ Gini impurity
Gini index is measure of inequality in sample. It has value between 0 and 1. Gini index of value 0 means sample are perfectly homogeneous and all element are similar, whereas, Gini index of value 1 means maximal inequality among elements.

# There are Various algorithm that are used to generate decision tree from data, some are as following,
1. Classification and regression tree CART
2. ID 3
3. CHAID
4. ID 4.5

# classification tree with the help of CART algorithm,
1. It is used for generating both classification tree and regression tree.
2. It uses Gini index as metric/cost function to evaluate split in feature selection in case of classification tree.
3. It is used for binary classification.
4. It use least square as a metric to select features in case of Regression tree.

# Ensemble methods
Ensemble methods, which combines several decision trees to produce better predictive performance than utilizing a single decision tree. The main principle behind the ensemble model is that a group of weak learners come together to form a strong learner.