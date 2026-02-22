---
layout: article
title: "Training Brain-Scale Neural Networks on Marlowe"
pi_name: Dan Yamins
---

# Training Brain-Scale Neural Networks on Marlowe

<div class="article-meta">
<strong>PI:</strong> Dan Yamins, Associate Professor of Psychology and Computer Science<br>
<strong>Lab:</strong> Stanford Computational Neuroscience Lab<br>
<strong>Marlowe Allocation:</strong> 24 nodes (192 H100 GPUs) | Hero run: February 7, 2026
</div>

## The Science

How does the brain give rise to cognition? Dan Yamins' lab is attacking this question by training an 80-billion-parameter neural network inspired by the architecture of biological brains. The model — called a Counterfactual World Model — learns to predict how the physical world changes in response to actions, a capacity that neuroscientists believe is fundamental to biological intelligence.

"The brain doesn't just passively observe the world," Yamins explains. "It builds internal models that predict what will happen next — and those predictions are what let us plan, imagine, and reason."

Training a model of this scale demands computational resources that go far beyond what a typical university lab can access. The 80B-parameter architecture requires coordinated training across hundreds of GPUs communicating at high bandwidth — exactly the kind of capability-scale workload that Marlowe was built for.

## The Hero Run

On February 7, 2026, Yamins' team completed a proof-of-concept hero run on Marlowe: 24 nodes (192 H100 GPUs) running for 24 hours, achieving 45% model FLOPS utilization (MFU). This validated that the massive model can train efficiently at scale on Marlowe's architecture and set the stage for a proposed 30-day dedicated training campaign that would produce a landmark result in computational neuroscience.

The hero run used internet-scale video data as training input — the same kind of rich, dynamic visual experience that biological brains learn from during development.

## Why Marlowe

This research simply cannot happen on conventional computing clusters. Single-node GPU jobs are orders of magnitude too small. Cloud computing at this scale would cost tens of thousands of dollars per run. Marlowe provides the combination of massive GPU count, high-bandwidth interconnect (InfiniBand), and dedicated scheduling that makes capability-scale neuroscience training possible at a university.

At $0.25 per GPU-hour, Yamins' team can pursue ambitious experiments that would be financially prohibitive on commercial cloud platforms — enabling the kind of high-risk, high-reward research that universities are uniquely positioned to support.

## What's Next

The team is preparing for a 30-day dedicated training campaign using 24 nodes, which would produce a fully trained 80B-parameter brain model — a first-of-its-kind result that bridges computational neuroscience and frontier AI research.
