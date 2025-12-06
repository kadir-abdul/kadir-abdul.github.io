---
title: "AuditCopilot: Leveraging LLMs for Fraud Detection in Double-Entry Bookkeeping"
collection: publications
category: conferences
permalink: /publication/2025-auditcopilot
date: 2025-12-02
venue: "NeurIPS 2025 Workshop on Generative AI in Finance (Poster, San Diego location track)"
paperurl: "https://neurips.cc/virtual/2025/loc/san-diego/132526"
doi: "10.48550/arXiv.2512.02726"
slidesurl: "https://arxiv.org/abs/2512.02726"
citation: 'Md Abdul Kadir, Sai Suresh Macharla Vasu, Sidharth S. Nair, and Daniel Sonntag. (2025). "AuditCopilot: Leveraging LLMs for Fraud Detection in Double-Entry Bookkeeping." Presented at the NeurIPS 2025 Workshop on Generative AI in Finance, San Diego.'
excerpt: "Benchmarks LLaMA- and Gemma-based fraud detectors against journal entry tests, showing LLMs flag subtler double-entry anomalies with human-auditable rationales."
---

AuditCopilot explores whether frontier LLMs can shoulder auditing workloads that traditionally rely on brittle rule engines. We evaluate debit/credit ledgers drawn from anonymized enterprise systems and purpose-built synthetic stress tests, comparing LLaMA-3, Gemma-2, and instruction-tuned baselines against journal entry tests (JETs) and gradient-boosted detectors. The LLM variants consistently surface fewer false positives while narrating *why* an entry is suspicious, which makes it easier for auditors to triage high-risk events.

The NeurIPS poster (Generative AI in Finance workshop, San Diego track) highlights three design pillars:

1. **Ledger-native prompting.** We serialize double-entry tuples into structured prompts so models reason over accounting primitives rather than free-form prose.
2. **Programmatic guards.** Deterministic validators still catch blatant imbalances, while the LLM specializes in judgment calls such as shell transfers or timing abuses.
3. **Explanations for trust.** Each flag ships with a natural-language rationale plus the top accounts involved, letting human auditors trace the evidence quickly.

You can revisit the virtual poster page via the NeurIPS hub or read the extended methodology on [arXiv](https://arxiv.org/abs/2512.02726), which includes ablation figures, prompts, and fraud-type partitions.
