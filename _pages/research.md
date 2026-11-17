---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My goal is to make foundation models **inspectable, correctable, and robust**: to move from "the model was wrong" to "here is the mechanism that made it wrong, and here is a minimal fix."

## 1. Interpretability of vision–language models

How do large vision–language models represent visual concepts, and which components are responsible for their behaviour?

- **Concept discovery without dense labels.** Text-guided concept learning extracts sparse, faithful concept vectors from patch-level activations of LVLMs. *([NeurIPS 2026 Spotlight](/publication/2026-tgcl))*
- **Auditing interpretability tools.** Testing what popular "visual head" discovery scores really measure, and where random controls and attention-source confounds mislead. *([arXiv 2026](/publication/2026-visual-head-discovery))*
- **Beyond saliency maps.** Unsupervised concept graphs that explain predictions as structured reasoning rather than heatmaps. *([IJCAI-ECAI XAI 2026](/publication/2026-beyond-heatmaps))*

## 2. Robustness and backdoor security

Where do adversarial behaviours live inside a network, and can we remove them cheaply?

- **Localising backdoors.** In BN-based networks, backdoor training is absorbed mainly by Batch Normalization. FlashBN (training-free) and ReBN (few-shot) exploit this to neutralise attacks. *([NeurIPS 2026](/publication/2026-flashbn-rebn))*
- **Attacks on explanations.** Explanation-aware backdoors that manipulate attribution maps, and defenses against them. *([arXiv 2024](/publication/2024-explanation-aware-backdoors))*

## 3. Reliable models for high-stakes domains

Deploying foundation models where errors are expensive, with explanations experts can check.

- **Finance and auditing.** LLM-based fraud detection in double-entry bookkeeping with auditable rationales. *([NeurIPS 2025 Workshop](/publication/2025-auditcopilot))*
- **Medical imaging.** Concept-bottleneck, multi-agent RAG for interpretable radiology reports; active learning for OCT segmentation. *(ECIR 2025, EICS 2025, MICCAI 2023)*

## Open source

- [TGCL-LVLM](https://github.com/Mak-Ta-Reque/TGCL-LVLM): concept learning for vision–language models
- [FlashBN / ReBN](https://github.com/Mak-Ta-Reque/flashbn_rebn): backdoor defenses via Batch Normalization · [models](https://huggingface.co/abka03/flashbn_rebn-models)

## Collaboration

I supervise MSc theses on these topics. See the [open thesis topics](/thesis/) or [email me](mailto:abdul.kadir@dfki.de).
