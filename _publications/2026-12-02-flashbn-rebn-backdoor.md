---
title: "Backdoor Attacks Rerouted: Batch Normalization as a Sink for Adversarial Signals"
collection: publications
category: conferences
permalink: /publication/2026-flashbn-rebn
date: 2026-12-02
highlight: "Poster"
venue: "Advances in Neural Information Processing Systems (NeurIPS 2026)"
paperurl: "https://openreview.net/forum?id=1YqAFIeJti"
projecturl: "https://mak-ta-reque.github.io/flashbn_rebn/"
codeurl: "https://github.com/Mak-Ta-Reque/flashbn_rebn"
authors: "Abdul Kadir, Tuan Tran, and Daniel Sonntag"
citation: 'Md Abdul Kadir, Tuan Tran, and Daniel Sonntag. (2026). "Backdoor Attacks Rerouted: Batch Normalization as a Sink for Adversarial Signals." In Advances in Neural Information Processing Systems (NeurIPS).'
excerpt: "**Poster at NeurIPS 2026.** Shows that backdoors in BN-based CNNs are stored mainly in Batch Normalization layers, and proposes FlashBN and ReBN as defenses."
---

**NeurIPS 2026 Poster.** We show that in CNNs with Batch Normalization, backdoor training predominantly updates the BN layers, so the trigger lives there rather than in the core weights. Building on this, we propose two defenses:

- **FlashBN** — training-free; re-estimates BN statistics at inference time.
- **ReBN** — few-shot; fine-tunes only BN layers on a small clean set.

Across eight black-box and three explanation-aware attacks, both lower attack success rates and improve triggered-sample accuracy compared with nine baseline defenses.

[Project page](https://mak-ta-reque.github.io/flashbn_rebn/) · [OpenReview](https://openreview.net/forum?id=1YqAFIeJti) · [Code](https://github.com/Mak-Ta-Reque/flashbn_rebn) · [Models](https://huggingface.co/abka03/flashbn_rebn-models)
