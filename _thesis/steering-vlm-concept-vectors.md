---
title: "Steering Vision-Language Models with Positive and Negative Concept Vectors"
excerpt: "Develop methods to steer vision-language models using concept vectors derived from Concept-Guided Dictionary Learning (CGDL) to control autoregressive generation and improve interpretability."
collection: thesis
---

# Steering Vision-Language Models with Positive and Negative Concept Vectors

## Introduction

Large vision–language models (LVLMs) generate text autoregressively, conditioning each token on evolving multimodal states. This enables rich, context-sensitive prediction but raises unique interpretability challenges: predictions may stem from spurious correlations or hallucinations rather than visual evidence. 

Existing methods, such as saliency maps or training-based grounding, localize objects but do not reveal the higher-level concepts driving model decisions. Concept-based explanations offer more conceptual insights, yet most methods assume static feature spaces. Approaches like TCAV, CRAFT, CLIP-Dissect, and Holistic cannot extend to autoregressive models and are restricted to single-object settings, while CoX-LMM additionally requires a labeled concept token, further limiting scalability.

## Research Motivation

We propose building on **Concept-Guided Dictionary Learning (CGDL)**, a weakly supervised framework for scalable concept discovery in autoregressive LVLMs. CGDL finds candidate concepts and treats each one as a one-vs-all representation learning problem with a two-basis decomposition. It constructs positive and negative patch sets using segmentation and random cropping, prompts the model with a binary question to identify whether the concept exists in each crop, and extracts the model's hidden activations for both positive and negative patches.

This thesis opportunity focuses on extending CGDL to **actively steer** vision-language models using the discovered concept vectors.

## Research Objectives

### 1. Concept Vector Extraction
- Extract positive and negative concept vectors from CGDL decompositions
- Ensure monosemanticity and multimodal alignment of discovered vectors
- Develop methods to disentangle concept activations from residual noise

### 2. Steering Mechanisms
- Develop techniques to inject concept vectors into model hidden states during generation
- Create control mechanisms that amplify or suppress concept activations
- Design steering strategies that work across different layers and timestamps

### 3. Interpretability and Control
- Demonstrate how positive/negative concept vectors influence model predictions
- Show which concepts drive specific model behaviors
- Provide human-understandable concept-based control over generation

### 4. Scalability and Evaluation
- Extend steering mechanisms to work with thousands of concepts
- Evaluate on large-scale datasets (ImageNet-1k, MSCOCO)
- Measure improvements in attribution quality, sparsity, and faithfulness

## Key Technical Challenges

1. **Multimodal Vector Alignment**: Ensuring concept vectors faithfully bridge visual and textual modalities
2. **Generalization**: Making steering effective across different input samples and concept combinations
3. **Computational Efficiency**: Scaling concept-based steering to real-time applications
4. **Evaluation Metrics**: Developing principled metrics for assessing steering effectiveness and concept fidelity

## Expected Contributions

- A framework for steering LVLMs using positive/negative concept vectors
- Empirical validation on standard benchmarks with improvements to attribution quality (targeting +9% CLIPScore, +4% BERTScore)
- Methods for scaling concept-based control to unlimited-object scenarios
- Practical tools for transparent multimodal reasoning and human-interpretable model behavior

## Research Areas

- Explainable AI (XAI) and concept-based explanations
- Vision-language model interpretability
- Concept discovery and disentanglement
- Multimodal representation learning
- Autoregressive model control and steering
- Weakly supervised learning
