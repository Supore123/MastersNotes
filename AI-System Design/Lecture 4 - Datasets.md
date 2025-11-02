
**Course:** [[ELEC0136 AI System Design]]
**Date:** 2025-10-29
**Source:** [Lecture Slides](url)

---
##### Lecture notes
 - Important requirements for the notes: 
 - Lab 4 and remaining labeling with sampling
 - Dataset doesn't mean the same thing -- dataset is the formatting and the remaining method in how we access our data. 
- **Dataset**: A dataset is a collection of data in the form of (A,B) pairs that induces an empirical probability distribution over another unknown, true distribution
	- In simpler terms; it needs:
	- 1) It has to be in A,B pairs
	- 2) It represents an empirical distribution of a theoretical one


##### Machine Learning Anatomy
We can classify the process through 3 sets
1) Regression: A regression problem is a type of supervised learning task where to goal is to predict a continuous numerical value based on input data. Regression problems are concerned with predicting quantities or trends.
2) Classification: 
3) Sequence modelling: A type of supervised learning task where the goal is to model the next temporal state of a dynamical system, given its previous states in time

--> 
In the pipeline, we need to consider how we get a dataset from our data. First we require labelling, then sampling, 
##### Data Labeling
- How does one actually get the label?
- Label's are expensive and difficult to place on data. Also known as the ground truth for what we consider

Function given to skills for approximating 
	--> 

##### Statistical Learning
- CAn be done in a number of methods: 
	- Uniform sampling
	- Random
	- Imbalanced dataset
$$
	E_{P(x)}[x] = \sum_{x}{P(x)x} = \sum_{x}\frac{Q(x)xP(x)}{Q(x)}
$$
^ The above equation is utilised for the imbalanced dataset

Need to review the deep learning to assess why gradient descent is better. It is utilized 

###### Class imbalance
Review in notes later

