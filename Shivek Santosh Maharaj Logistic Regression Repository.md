# Field: Machine Learning

## Topic of Testing: Logistic Regression

#### Description:
This file contains interview-standard questions and answers about the Logistic Regression Algorithm used in the field of Machine Learning.
*________________________________________________________________________________________________________________________________________________________*

### Q1. When would you use standard Logistic Regression Algorithm (or Logistic Regression in it's base form)?
#### Difficulty: Junior.
__*Answer:*__ Logistic Regression, despite having __*regression*__ in it's name, is actually a binary classification algorithm in it's default state. This means that one
would use Logistic Regression Algorithm when one requires a categorical value to be predicted. This means that the target vector values are __text__ or __classes__, in which
each observation may take one of two values, such as "yes"/"no"; "red"/"blue"; hence the description of __Binary Classifier__. Logistic Regression should be used to predict
non-quantitative values, i.e., Non-Numerical values.

### Q2. Provide a short explanation about the use of ROC curves and the AUC-ROC Evaluation metric.
#### Difficulty: Medium.
__*Answer:*__ ROC Curve is short for Receiving Operating Characteristic Curve. In the visual form, this visualization (graph) is used to show the performance of a Binary
Classification model, such as standard Logistic Regression. The Graph plots two important Classification Evaluation metrics- viz. True Positive Rate (TPR) and False Positive
Rate (FPR)- for all model threshold values which range from integer 0 to 1. AUC-ROC is short for Area Under Curve- it is the area under the ROC Gradient. One will find that
the closer the value for AUC-ROC is to 1, the better the quality of the Binary Classification model. Upon drawing a diagonal gradient from the bottom-left to top-right of
the plot, this particular gradient will be used to represent the values that will be received if the model is not efficient in it's predictions and is randomly guessing,
hence, the model will lack predictive power.

### Q3. Given the following information, provide a short logical reason for your answer. 
_The logit function will accept input values, and will effectively convert those into a value ranging between 0 and 1. It is a probability. The Odds Function has
the ability to transform the Logit Function into an Equivalence Function which will change the output range from initially, probabilities between 0 to 1, to log
odds between 0 and ∞. **The Log Odds Function effectively converts each probability into Log Odds**._ **What is the possible range of values for the Odds Function
if the Logit Function has an x-axis in which X ε [0, 1].**
#### Difficulty: Senior.
__*Answer:*__  Upon applying and understanding the mathematices of Logistic Regression, one will find that the odds converts probabilities which range from 0 to 1, into
logarithmic odds. Hence if X is an element of 0 to 1, the Odds Function will have a value range of -∞ (negative infinity) to ∞ (positive infinity).


