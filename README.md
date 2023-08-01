# Easy Rejection Sampling

This repository hosts our research code for the Easy Rejection Sampling (ERS) algorithm. The goal is that ERS be easy from a user's perspective - in that they only need to pass a function that computes the (unnormalized) density they wish to draw samples from, and optionally the domain of that function if not infinite. In this code any function defined in a JAX compatible way should work. 

This is research quality code with no warranty or support. 


## Citations

If you use the ERS algorithm or code, please cite our work! 

```
@inproceedings{ERS,
author = {Raff, Edward and McLean, Mark and Holt, James},
booktitle = {European Conference on Artificial Intelligence (ECAI)},
title = {{An Easy Rejection Sampling Baseline via Gradient Refined Proposals}},
year = {2023}
}

```
