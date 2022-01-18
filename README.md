# Caffeine content in Various Drinks
The dataset lists caffeine and calorie content for various drinks along with the volume in which they are served. It is general knowledge that caffeine is a drug and thus its consumption needs to be monitored and limited otherwise leading to disastrous health consequences.
## Dataset

The dataset used is the Caffeine Content of Drinks(https://www.kaggle.com/heitornunes/caffeine-content-of-drinks) from Kaggle. The task is a classification task, then you must specify the number of classes and give a 1 line description of each class as follows(example of Iris Dataset). 

The 5 class labels are:

**drink**: Drink's name that it is served as, example Coffee Friend Brewed Coffee, Nescafe Gold etc.

**Volume (ml)**: Volume quantity of the drink in mililitres

**Calories**: Calories quantity of the drink

**Caffeine (mg)**: Caffeine quantity in miligrams listed for the entire contained that the drink is served in

**type**: Drink's type - tea, coffee, energy drink, soft drink, energy shots 

## Models Used
I used 3 classification algorithms on the dataset, these are discussed below

### 1. Decision Trees:
Decision Trees are a non-parametric supervised learning method used for classification and regression. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features.
A tree can be seen as a piecewise constant approximation. Decision trees use multiple algorithms to decide to split a node into two or more sub-nodes. The creation of sub-nodes increases the homogeneity of resultant sub-nodes. 
Purity of the node increases with respect to the target variable. The decision tree splits the nodes on all available variables and then selects the split which results in most homogeneous sub-nodes.

### 2. Naive Bayes
Naive Bayes classifiers are a collection of classification algorithms based on Bayes’ Theorem. It is not a single algorithm but a family of algorithms where all of them share a common principle, i.e. every pair of features being classified is independent of each other.
It is a probabilistic classifier, which means it predicts on the basis of the probability of an object.
Bayes' theorem is also known as Bayes' Rule or Bayes' law, which is used to determine the probability of a hypothesis with prior knowledge. It depends on the conditional probability.

### 3. Logistic Regression
Logistic regression (LR) is basically a supervised classification algorithm. In a classification problem, the target variable(or output), y, can take only discrete values for a given set of features(or inputs),X.
The model builds a regression model to predict the probability that a given data entry belongs to the category numbered as “1”. Just like Linear regression assumes that the data follows a linear function, Logistic regression models the data using the sigmoid function.
The setting of the threshold value is a very important aspect of Logistic regression and is dependent on the classification problem itself.
In this particular case, LR is binomial, i.e., target variable can have only 2 possible types: “0” or “1” which represent "caffeine is not present in considerable amount" for "0" and vice-versa.
## Future Work
Using heatmaps and convolution matrix to delve deeper into data visualization and improve the prediction accuracy by using more advanced and varied classification algorithms.
