---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

<p class="hero__lead">My goal is to make foundation models <strong>inspectable, correctable, and robust</strong>: to move from "the model was wrong" to "here is the mechanism that made it wrong, and here is a minimal fix."</p>

<div class="card-grid">
  <div class="card">
    <span class="card__num">01</span>
    <h3>Interpretability of vision–language models</h3>
    <p>How do large VLMs represent visual concepts, and which components drive their behaviour?</p>
    <ul>
      <li><strong>Concept discovery without dense labels.</strong> Text-guided concept learning extracts sparse, faithful concept vectors from patch-level activations. <a href="/publication/2026-tgcl">NeurIPS 2026 Spotlight</a></li>
      <li><strong>Auditing interpretability tools.</strong> What "visual head" discovery scores really measure, and where random controls mislead. <a href="/publication/2026-visual-head-discovery">arXiv 2026</a></li>
      <li><strong>Beyond saliency maps.</strong> Unsupervised concept graphs that explain predictions as structured reasoning. <a href="/publication/2026-beyond-heatmaps">IJCAI-ECAI XAI 2026</a></li>
    </ul>
  </div>
  <div class="card">
    <span class="card__num">02</span>
    <h3>Robustness and backdoor security</h3>
    <p>Where do adversarial behaviours live inside a network, and can we remove them cheaply?</p>
    <ul>
      <li><strong>Localising backdoors.</strong> Backdoor training is absorbed mainly by Batch Normalization; FlashBN (training-free) and ReBN (few-shot) exploit this to neutralise attacks. <a href="/publication/2026-flashbn-rebn">NeurIPS 2026</a></li>
      <li><strong>Attacks on explanations.</strong> Explanation-aware backdoors that manipulate attribution maps, and defenses against them. <a href="/publication/2024-explanation-aware-backdoors">arXiv 2024</a></li>
    </ul>
  </div>
  <div class="card">
    <span class="card__num">03</span>
    <h3>Reliable models for high-stakes domains</h3>
    <p>Deploying foundation models where errors are expensive, with explanations experts can check.</p>
    <ul>
      <li><strong>Finance and auditing.</strong> LLM-based fraud detection in double-entry bookkeeping with auditable rationales. <a href="/publication/2025-auditcopilot">NeurIPS 2025 Workshop</a></li>
      <li><strong>Medical imaging.</strong> Concept-bottleneck multi-agent RAG for interpretable radiology reports; active learning for OCT segmentation. ECIR 2025 · EICS 2025 · MICCAI 2023</li>
    </ul>
  </div>
</div>

## Open source

<div class="card-grid card-grid--2">
  <a class="card card--link" href="https://github.com/Mak-Ta-Reque/TGCL-LVLM"><h3>TGCL-LVLM</h3><p>Concept learning for vision–language models.</p></a>
  <a class="card card--link" href="https://github.com/Mak-Ta-Reque/flashbn_rebn"><h3>FlashBN / ReBN</h3><p>Backdoor defenses via Batch Normalization, with released models.</p></a>
</div>

## Collaboration

I supervise MSc theses and welcome collaborations on these topics. See the <a href="/thesis/">open Master thesis topics</a> or <a href="mailto:abdul.kadir@dfki.de">email me</a>.
