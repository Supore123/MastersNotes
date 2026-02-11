# [[AMLS II]]: Week 3 Joint lecture with NLP
**Date:** 2026-02-04
**Status:** #status/review
**Topic:** #ml/theory

---
# Combined Lecture with NLP
## Executive Summary
> MLP for NLP tasks and sentiment analysis
> Needs to be the same lecture setup for handling the CNN and MLP so it is required

## Recap of NLP and AMLS II
- The NLP Pipeline:
	- Raw text -> Breaking text into units(tokenization) --> Creating a vector from these tokens (vectorization) -> Capturing context is required from the vector pairing, what should be represented (text representation))-> Statistical model for making the prediction --> Prediction
- The goal of this pipeline for NLP is to transform raw unstructured data into mathematical format for probabilitic decision-making
- Modern deep learning is to do with contentualisation, moving from static word meaning to sentence-dependent meanings
## Statistical Pipeline
- A more formal setup of what is occuring is when tokenization is just the seperating and handling of each part --> i.e: breaking down each part of the token. 
- One hot encoding is needed or using encode bigrams
- N.B.: One hot encoding, it is just "activating" each word , i.e: setting it's "lightbulb" as on while everything else is off on this point.

## Context
- How do we keep the context of words and what we do We can using an N-grams encoder, which is a list of hot encoding groups of words or tokens to make it aware. All words are orthogonal and equally dissimilar. 
- This is to do with features engineering and handles its own dimensionality and there is no information in the above
	
	**So How Do We Get Real Context?**
- This is handled by using a word-embedder to which doesn't one hot encoded and show a discrete setting, a word embedder shows contiunous non orthogonal embedding of the words
- Word2Vect is handled by the skip gram context
		$$p(c|w) = {1/{Z(w)}* exp(e_{wrd}* e_{ctx}(c))}$$
- The above is the p(c|w) as a log-bilinear model. This is the handling of the skip gram model for handling learnable embedding for the word w and context handling.
- So there are contexts between words and the activation in layers
- Word representation and text representation and handling
- The sum of all this encoding from a one hot encoding is known as pooling. So it effectively lights up all the words being used in an embedding. They are summed, weighted or maxed out, so we know the value of each word; 

## Feed Forward Model
**Why is a linear classifier not enough?**
- This system and pupeline for linearsation is good but not enough for our classification issues.
- If we wanted to say classify a sentence as positive(sentiment) or negative(sentiment) , with only a label set of a +1 or -1
- Using a log0linear model and softmax, this is a standard application system
- Sigmoid function is typically used, review the derivation  
- Sometimes a linear classifier is not needed. We need to handle different types of classifier
Review required for the changes in the systematic usage here
# MLP
- Review MLP derifation: #3blue1brown
- MLPs are universal approximators in the unit cube, so they are being used appropriately for any function, 
- MLPs can effectively represent any function! 
- However the optimisation or backprop or overfitting may occur, many problems, but can be a universal approimator
- That pipeline is the statistical NLP pipeline, but it is different for the Deep learning pipeline, using MLP and softmax


# Sentiment Analysis Task
- Trying to review the NLP and other AMLS content required. 
- **What is Sentiment Analysis? Why is it difficult? How to build a sentiment analyzer?**
==Sentiment Analysis==
- The NLP task of classifying utterances according to how they make the interlocutor feel:
- i.e: How to class stuff on sentiment
- We have some terminology for this, **polarity** and **subjectivity**
- polarity refers to identifying the sentiment orientation
- Subjectiveity refers to the expression of personal feelings, views or belief
- https://text-processing.com/demo/sentiment/ is an example

- Need to be able to review the MLP paper, review what is being utilised for sentiment analysis. 
- Using this system, we can use a Deep Average Network -DAN. This shows the benefit of going deep. using Kaggle, I can implement this myself now. 
- In a DAN order doesn't matter
## Language Modelling
- Language modelling is the task of predicting what is coming next
- It's effectively given a sequence, calculating the probability of the next term, A system doing this is called a language model
- It's taking all the tokens and applying a probability onto it for the next token
### Text Classification vs Language model
- Text classification predicts one label from K picking one discrete output, whereas the language model produces a structured, combination sequence, which combinationally join and get larger
### Learning Framework
- There are different systems in the language modelling, but what is important is this: can we apply the same learning framework? No
- 
This is the importance of handilng word embeddings for the model systems, review Berngio for intiial history on not needing to observe n-gram , but there are still issues with windows and size, but this causes different weights. This is resolved by convolutions later on.

## Language modelling and RNNs

- Recurreant Neural Networks (RNNs)
- An RNN takes your h (hidden states) and the context evolves over time, Need to review how RNNs operate entirely for the fix here
  
  RNN can process any length input, , which leads to models being utilised so model size doesnt increase for longer input context, however recurrent computation is slow and is difficult to access info from history which is really far back, but theoretically you can do so.
- 
