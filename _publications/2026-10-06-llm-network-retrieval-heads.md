---
title: "Where Do LLMs Retrieve Network Information? Identifying the Responsible Heads and Neurons"
collection: publications
category: preprints
permalink: /publication/2026-llm-network-retrieval-heads
date: 2026-10-06
venue: "arXiv preprint"
paperurl: "https://arxiv.org/abs/2610.08200"
doi: "10.48550/arXiv.2610.08200"
authors: "Abdul Kadir, Md Mohasin Hossain, Omair Shahzad Bhatti, Abdulrahman Mohamed Selim, Daniel Sonntag, et al."
citation: 'Md Abdul Kadir, Md Mohasin Hossain, Omair Shahzad Bhatti, Abdulrahman Mohamed Selim, Daniel Sonntag, et al. (2026). "Where Do LLMs Retrieve Network Information? Identifying the Responsible Heads and Neurons." arXiv:2610.08200.'
excerpt: "Traces how LLMs retrieve network facts (e.g., domain–IP relations) to a handful of causally validated attention heads, which yield near-perfect detectors, while single neurons prove unreliable."
---

Can an LLM's knowledge of relationships between network entities, such as domain names and IP addresses, be traced to specific components? Across five LLMs from three architecture families, we identify a small set of causally validated attention heads (1–9 out of 128–1152 candidates) that support detectors with 99.5–100% held-out accuracy. Neuron-level findings are model-dependent: on independent CAIDA data, head-based detectors keep AUC ≥ 0.971, while single-neuron detectors fall below chance in three of five models.

[arXiv:2610.08200](https://arxiv.org/abs/2610.08200)
