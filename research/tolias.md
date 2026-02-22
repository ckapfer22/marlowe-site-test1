---
layout: article
title: "The Enigma Project: Building a Foundation Model of the Brain"
pi_name: Andreas Tolias
---

# The Enigma Project: Building a Foundation Model of the Brain

<div class="article-meta">
<strong>PI:</strong> Andreas Tolias, Professor of Ophthalmology and of Electrical Engineering<br>
<strong>Lab:</strong> Tolias Lab<br>
<strong>Affiliations:</strong> Bio-X · Wu Tsai Neurosciences Institute<br>
<strong>Marlowe Allocation:</strong> 8 nodes (64 H100 GPUs) | Cycle 5
</div>

## The Science

What if we could build a foundation model of the brain — a single AI system trained on the full complexity of neural activity, visual input, and behavior? That's the goal of the Enigma Project, led by Andreas Tolias and his team at Stanford.

The project trains large multimodal transformers (approximately 1 billion parameters) on time-resolved experimental data: simultaneous recordings of neuronal activity, visual stimulation, and animal behavior. By learning the relationships between what an animal sees, how its neurons respond, and what it does, the model aims to become a general-purpose tool for understanding brain function.

"We're not just building a model that fits one experiment," the team explains. "We're building a model that captures the fundamental computational principles of the brain across modalities and conditions."

## The Scale

Foundation models in neuroscience face the same challenge as foundation models in language and vision: they need massive compute to train. The Enigma Project's billion-parameter transformers require multi-node GPU training with high-bandwidth communication between nodes — the kind of workload where Marlowe's InfiniBand interconnect makes a critical difference.

The team has submitted multiple applications across Marlowe's Beta test and allocation cycles, progressively scaling their training from 8 to 64 GPUs as their models and datasets have grown. Their Cycle 5 allocation provides 8 nodes (64 H100 GPUs) for sustained training campaigns.

## Why It Matters

Foundation models have transformed language (GPT, Claude) and vision (DALL-E, Stable Diffusion). The Enigma Project applies the same paradigm to neuroscience — building a model that could accelerate research across the entire field by providing a pre-trained understanding of how the brain works.

The potential applications range from basic neuroscience research to clinical translation: understanding neurological disorders, developing brain-computer interfaces, and building AI systems that learn more like biological brains.

## Related Coverage

- [Scientists build 'digital twin' of mouse brain (Stanford Report, April 2025)](https://news.stanford.edu/stories/2025/04/digital-twin)
