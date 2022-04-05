# Perceiver IO: A General Architecture for Structured Inputs & Outputs Summary

## Overview

### Discussion
With transformer, why we have limited text size?

---

- Due to its self-attention mechanism, it scales very poorly in both compute and memory. In every layer, all inputs are used to produce queries and keys, for which a pairwise dot product is computed. Hence, it is not possible to apply self-attention on high-dimensional data without some form of preprocessing.

---

Current architectures cannot be applied beyond a small set of stereotyped settings, as they bake in domain & task assumptions or scale poorly to large inputs or outputs. Therefore, in this study, the researchers proposed Perceiver IO, a general-purpose architecture that handles data from arbitrary settings while scaling linearly with the size of inputs and outputs.

- Proposed an architecture, with the ultimate goal of building a network that can easily integrate and transform arbitrary information for arbitrary tasks.
- Perceiver IO does this using a fully attentional read-process-write architecture: inputs are encoded (read) to a latent space, the latent representation is refined (process) via many layers of processing, and the latent space is decoded (write) to produce outputs.
- The proposed architecture can be applied with unprecedented levels of generality. 

## Related Work

### Discussion
- When do you think the earliest trials to realize high-dimensional inputs start from?

---

1994, Hinton & Zemel, Autoencoding: encode and reproduce high-dimensional inputs like images             
Since 2012, Krizhevsky et al. and many other reseachers, Neural nets led to breakthroughs in image understanding             
Since 2011, Collobert et al., natural language applications research has made extensive progressive in capturing the structured nature of language, typically via autoregressive models                   
Since 2017, Kaiser et al. , several groups have proposed to solve tasks in multiple domains      
...              
Several groups have proposed to use attention to manipulate the size of arrays or to introduce bottlenecks in processing

## The Perceiver IO Architecture


## Conclusion




## Critical Analysis

## Resources:

[Original Paper](https://arxiv.org/abs/2107.14795) Perceiver IO: A General Architecture for Structured Inputs & Outputs          
[HuggingFace Blog](https://huggingface.co/blog/perceiver) Perceiver IO: a scalable, fully-attentional model that works on any modality
