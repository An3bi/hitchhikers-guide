# Machine Learning and Practical Validity

## Motivation
By definition this work involves turning a social problem into a problem we can solve using data science methods. It is important to think carefully about how we do that, implicit and explicit assumptions, and common pitfalls.

## Concepts 
Mapping a social problem to ML problem - defining an objective function, ethical questions, potential for misuse, evaluation and validation. Social implications (and potential biases) should be worked out; contextualizing project from a data-driven, practical perspective. 

# Predictive Modeling

## Motivation
People coming from social science or stats background are usually familiar with modeling for coming up with a theory so it is a leap for them to go to throwing as many models and features as possible at a problem.

## Concepts 
Prediction vs. coming up with a theory: what this means for feature generation and model evaluation - you include all information even if it might not be useful, collinearity is not as concerning, feature selection/regularization 

# Model Evaluation 

## Motivation
You build a lot of models. You have to choose between them. How?

## Concepts
Constructing a training/test split, AUC/precision/recall, deciding on a metric based on the context of the problem (ranked list/precision at top K), generalizability (EPA test set bias)


# Temporal Cross Validation

## Motivation
Many projects will build a model to predict some outcome before it happens, so they need to construct training and test sets to evaluate models in a manner that doesn’t leak information. 

## Concepts
How to choose granularity/observation level (predicting in the next day/week/year), how to set up training and test sets (both conceptually and technically), difference between training window (observations) and aggregation windows (features), how to not cross contaminate, how does model update when more data is added
