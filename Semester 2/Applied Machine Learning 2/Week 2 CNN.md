**Date:** 2026-01-28
**Status:** #status/review
**Topic:** #ConvolutionalNeuralNetwork

---

## Executive Summary
> Covering the contents of how we use CNN
> General note covering, need to review each coding section to really undersatnd

## Theoretical Framework
- Need to understand the framework for how we can handle the CNN, this means I need to understand more of the CNN breakdown 
- Need to understand the respective field of each section. 
-

#### Locality -> Sparsity
- To understand back propogation, I need to understand how each layer works and oeperates

##### Convolution
- The convolution operations is being used in each section to evaulate each weight. Each weight going from each neuron to the next is being evaulatioed differently

- The convergence and generalisation works in 1D

#### 3D Work
- How to we get all of this operational in 3D?
- We translate the x*y*z 3D into a 1D wegiht value, to handle activation
- $$\text{"So we don't need to resahep the strucutre as 3D, but then we make a filter of }{\omega} $$ Effectively the convolution layer is where we take our 32x32x3 Image, take a dot proudct with the weights and filters, whch is convolutioed all together, creating our 6x28x28 action map, which each 1x28x28 making our activation map

--> This creates an output image which is smaller than our input layer, so we need to pad the contenets fo the array

--> Need to review how CNN's operate again, what is recommended by this section.
--> This is the convolutional compositionality of each layer being utilised. THis is the stacking principle of the ConvNets. 

--> Reviewing the previous labs for each section of how to handle each point
### Mathematical Formulation
- **Loss Function / Objective:**
$$\mathcal{L}(\theta) = \sum_x^{}$$
- **Optimization Strategy:**
- **Derivation Notes:**
Need to effectively go through each sessions Labs to get this up and runinng properly for me to work effectively. 

- 
	Need to learn and understand ResNet --> this is the best strategy
	Might need to review the DAPs as well to beable to get each section properly

---

## Reference Links
- [Lecture Slides](url)
- [Original Paper](url)
- [[Related Note A]] | [[Related Note B]]