reboot
**Date:** 2026-01-28
**Status:** #status/review
**Topic:** #ml/theory

---

## Executive Summary
> Context: Using the text as required and listed
> Using the transision of Log-Linear Models (NLP Pillars)
> Word embeddings (Feature represesntations: Dense Vectors)

## Initial Notes
 - How do we handle text classification for something simple like email sorting? 
 - How were things done prior to LLMs? 
	 - They were shifted towards NLP in the 90's after the 70s and 80s used language rules and lexicon
 - 
Pipeline: data--> tokenization--.Features-->statisical model--> prediction

Statistical NLP uses one hot encoder and word embedding to check the relation to words.
Deep learning added feature engineering (Word2Vec) and Token Embeddings

## Statistical Model
- Statistical NLP: 
- Score --> Model. How do we define this? We use a Log-Linear Model
- Some representation of the text --> the function handling for the training paramterer (the theta)
- Log linear models: 
-
$$
\text{This is the Log Linear Model example } 
p(y |x,\theta)=\,exp({\theta} . f(x,y))

 $$
## Exponential Models
- We can use linear scoring functions for handling this remaining set of feature and function handling

## Feature Extraction and Feature Learning
- Features are a cruicial part of the log-linear model
- Features are part of feature engineering, which used to be a big part between tokenization and statistical modelling
- ### Preprocessing
	- The requirement is to convert raw text into a more amenable feature deisng
	- **Tokenization**:
			- Convert each section into the token's as properly expected
	- Implementing things like lower casing, stemming etc... to format the words properly
- ### Feature Design
	- After preprocessing, we can obtain our features
	- One-hot encoding --> The method is how we take the words to be represented as oone-hot vectors.
	- Each word is seen as equally dissimilar. 
- ## Discrete revolution
- Richer representation of what occured during the semantic handling d
- For handling the remaining feature obtaining, to take the rest of the One hot (word level): Discrete and bag of words sentence level, we can utilise the remaining set of n-grams 



- --> Need to review each section to consider how the rest of what occurs for breakdown
- 
## Maximum Likeligood principle

$$\theta_{MLE} = \underbrace{argmax}_{\theta\epsilon\emptyset}L(\theta)$$
$$\text{This is the MLE equation, where  }\emptyset \text {represents the remaining requiemrent} $$ Log linear models requires us to be able to estimate the paramters, where the objective is convex and typically we can view the gradient-based methods.

 -->  How do we derive the gradient of the log-linear model.
- If we start from the initial model settings and try to maxize the probability of the gradient, we need to find the partial derivative. This remaining set of requirements at the local optimum, so when gradient is 0 --> we an find the gradient tends to ward the expected feature count.m 

--> How does this operate with the remaining set of the operational model for our function f --> this leads to the remaining set of counts needed. 

## Softmax
- **Softmax**: How do i classify?
- --> Softmax is the default way of building probabilitic models using nn. It's effectively the same as log-linear modelling.
Softmax is used to build the probablistic models of natural language
Log linear is effectively a dot product followed by a softmax function. 

Temperature paramters can be used as a hyper-paramter. 
- Softmax is called so because we can determine what the temperature paramter can be handled on as the argmax of the distribution being used This process is the annealing process. 
- --> For the annealing paramter T we can smoothly interpolate as the softmax and the argmax being used for the following: 
- Will need a review of the remaining hnalind -- how do we handle featureslearning and remaining setup/layout for our requirements needed 

---

## Reference Links
- [Lecture Slides](url)
- [Original Paper](url)
- [[Related Note A]] | [[Related Note B]]