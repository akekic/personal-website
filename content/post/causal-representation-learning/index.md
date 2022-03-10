---
title: Causal Representation Learning
subtitle: Some subtitle on Causal Representation Learning.

# Summary for listings and search engines
summary: Some summary about Causal Representation Learning.

# Link this post with a project
projects: []

# Date published
date: "2021-12-21T00:00:00Z"

# Date updated
lastmod: "2021-12-21T00:00:00Z"

# Is this an unpublished draft?
draft: true

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Schölkopf et al.**](https://arxiv.org/abs/2102.11107)'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin

tags:
- Academic

categories:
- Demo
---

# How Deep Learning Models fail

Modern deep learning models are great but often fail.

## Cow and Camels - Learning Shortcuts

In this paper they look at a model trained on pictures of cow and camels. 
Tyipcally cows are photographed on a green field, whereas cows are often on images with sand in the background.
When we train a model and test it on similar data everything looks fine.
However, when we evaluate the model on images where cows are shown with sand in the background or camels with grass in the background the model miserably fails.

Why is that?
The model has learned that a green background is a good predictor for a cow in the image and sand in the background means that with high probability there is a camel in the image.
It is arguably easier to recognize grass or sand in an image than recognizing the right animal.
Hence the model learns this shortcut and avoids the harder task of distinguishing animals.


## Cows and Camels - Causal Perspective

You can view the cows and camels example from a causal persepective.
There is a confounder between the background and the animal.
If the model was able to reason about the causal relationships going on in the background it might be more robust under the types of distribution shift described above.
This is what Causal Representation Learning is concerned with.

# Model of the World

Causal Representation Learning considers a particular view of how the data is generated.
Some latent causal model is sampled and then a mixing function is applied.

# Disentanglement

The simplest form of generative model you can imagine is one where all latent variables are independent.
Methods in disentanglement are trying to find these independent latent factors.

## Zoo of Methods

There are many methods that try to disentangle.
Here are some of them:
- model 1
- model 2

## Fundamental Constraints on Disentanglement

Francesco has found that there are limits to disentanglement.

# Causal Representation Learning
