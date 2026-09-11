---
layout: about
title: About
permalink: /
subtitle: 

profile:
  align: right
  image: piplup.png
  image_circular: false

selected_papers: true
social: false

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: true
  scrollable: true
  limit: 3
---

Broadly, I work on building systems for efficient, reliable language model training and inference.

Previously: [AISC](https://www.aisafety.camp/), [BAIR](https://bair.berkeley.edu/), [TAFLab](https://taflab.berkeley.edu/), [Berkeley](https://www.berkeley.edu/)

**Some stuff I've been working on:**

- [weight-sync-bench]({{ '/projects/weight-sync-bench/' | relative_url }}): Benchmarks trainer-to-inference weight synchronization for async RL and checks that transferred weights are correct. Measured p50 sync latency of 2.76 s via filesystem and 0.48 s via NCCL with Qwen3-0.6B in [prime-rl](https://github.com/samjiawng/prime-rl).

## Research Interests

Machine learning systems, with a focus on efficient training and inference:

- Async RL training systems
- Weight synchronization and rollout scheduling
