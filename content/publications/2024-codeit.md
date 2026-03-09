---
date: "2024-02-07"
title: "CodeIt: Self-Improving Language Models with Prioritized Hindsight Replay"
authors: "N. Butt*, B. Manczak*, A. Wiggers, C. Rainone, D.W. Zhang, M. Defferrard, T. Cohen"
venue: "ICML 2024"
link: "https://arxiv.org/abs/2402.04858"
github: "https://github.com/Qualcomm-AI-research/codeit"
---

Developed a post-training self-improvement loop for code-generating LMs: the model samples programs, relabels failed attempts via hindsight, and trains on a prioritized replay buffer. A ~220M parameter model achieved SOTA on the Abstraction and Reasoning Corpus (15% of evaluation tasks solved), outperforming all prior neural and symbolic baselines. First neuro-symbolic method to scale to the full ARC evaluation set.
