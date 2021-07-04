# Machine Learning Projects
**CPSC 483 - Introduction to Machine Learning**

## **Project 1 - Female 200m Data Analysis**

### **Problem description:**

Analyze a female 200m run data set and find a best fit line to the data.

### **Goals:**
1. Practice using linear regression
2. Compare linear model, 3rd order polynomial model and 5th order polynomial model
3. Practice with L2 regularization

### **How it works:**

This analysis will perform linear regression on the data and display the result on a graph. We can then compare the results from the 3 different regressions and decide which model is best. It will then perform L2 regularization to compare the results of different lambda values.

## **Project 2 - Wage Data Analysis**

### **Problem description:**

Analyze a wage data set and find a model that best predicts wage given the person's age.

### **Goals:**
1. Practice using linear regression, polynomial regression and ridge regression
2. Compare the R2 values of the different models
3. Practice with feature selection

### **How it works:**

This analysis will create 3 different models to predict a person's wage given their age. We can then compare the resulting R2 score to decide which model fits best. It then adds education as a feature to see if the model can be improved.

## **Project 3 - Bank Data Analysis**

### **Problem description:**

Analyze a banking data set to predict if a client has subscribed a term deposit (binary yes/no). Compare the results of different classifiers.

### **Goals:**
1. Practice using guassian naive bayes, logistic regression and support vector machines
2. Compare the difference between the classifiers
3. Practice creating and interpretting ROC Curves
4. Check any assumptions made from the dataset

### **How it works:**

This analysis preprocesses the dataset's features into ordinal, categorical and numerical features. The numerical features are scaled to normalize the range. It then performs guassian naive bayes, logistic regression and support vector machine analysis on the data. ROC curves are graphed in order to compare the results from each. The assumptiion tests how well a classifier will do if it simply predicted 0.

---

### **Links:**
[UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
