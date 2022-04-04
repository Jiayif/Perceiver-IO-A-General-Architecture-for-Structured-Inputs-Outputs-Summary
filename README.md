# Perceiver IO: A General Architecture for Structured Inputs & Outputs Summary

## Overview

Current architectures cannot be applied beyond a small set of stereotyped settings, as they bake in domain & task assumptions or scale poorly to large inputs or outputs. Therefore, in this study, the researchers proposed Perceiver IO, a general-purpose architecture that handles data from arbitrary settings while scaling linearly with the size of inputs and outputs.


-  A typical approach independently processes each input with a modality specific architecture, integrates them afterwards using a third fusion network, and reads out the result in a task-specific manner. 
-  Perceiver IO does this using a fully attentional read-process-write architecture: inputs are encoded (read) to a latent space, the latent representation is refined (process) via many layers of processing, and the latent space is decoded (write) to produce outputs.


## Discussion

## Conclusion




## Critical Analysis

## Resources:

[Original Paper](https://arxiv.org/abs/2107.14795) Perceiver IO: A General Architecture for Structured Inputs & Outputs
