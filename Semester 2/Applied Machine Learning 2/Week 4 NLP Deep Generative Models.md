--> Week 4 review and analysis

### Summary

- This is a topic about deep generative models

### Generative models
	What is a Generative Model?
- A generative model is a focus on the learning of the underlying data and augmentation
- This is based on the handling of 
- A big example is through diffusion models, for instance a Text2Image generation is like Gemeni 

An example of this is an inverse problem 
 - Taking a regular image and trying to adjust the colour. greyscale to colored. 
### Generative Model maths
-> Generative models take training data, that gives a probability which tells you what domain a value belongs in, which samples a new image that should resemble the dataset

- How do we learn this probability distribution or data?
- The answer is we have an Maximum likelihood error or discriminative system to determine what belongs to which family

- This distribution can be implicitly or explicitly learned. 
- The distribution can be learned in the original data space or in the latent space

#### Discriminative vs Generative task

- Discriminative is when you have high dimensaional data and the task is to predict a label for any given datapoint

- For generative, the high dimensaional data is the learnable output
- The focus is on modelling the joint distribution
- So we are trying to model p(x,y) from a probabilistic perspective

### Why is this problem high dimensional?
- how do we model the joint distribution p(x_1, x_2 ..., x_n) of an image?
- Imagine the numbers greyscale image.
- even a 784 pixel (28x28) greyscale image, there are 10^236 possible conditions, effectively too large to learn the entire distribution of p(x,y) joint distribution
- So we need assumptions to make this easier, we need "priors and inductive biases"

### Priors and indutive bias
- Conditional independence (foundfation of LLM and autoregressive models)
	- We can create a series of bayes for conditional independence

The goal of a generative model is to approximate the data distribution, that 

Types of generative modellings:
There are different parameterized models

- Autoregresiive, VAEs GANs, Diffusion models

### Autoregressive models
- join distributed factorized via the chain rule of probability