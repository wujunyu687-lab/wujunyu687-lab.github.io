---
permalink: /
title: "Junyu Wu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi, I am Junyu Wu.

I am interested in embodied intelligence and currently work on world models.

This website documents my research interests, projects, and academic experience.

## Research Experience

### EvoWorld: A World-Model-Centric Framework for Continuous Self-Evolution of Modular Embodied Skills

**ECCV 2026**

- Addressed catastrophic forgetting in monolithic VLAs trained on fragmented data through a dynamics-skill decoupling framework: an action-conditioned video world model serves as the cognitive core, while VLA experts are routed by an MLLM according to scene and task semantics.
- Developed a VLM-diagnosis-driven closed-loop self-evolution mechanism, using world-model counterfactual rollouts to score candidate experts and update modules based on failure attribution.
- Improved task success rates by 62%–83% relative across four VLA backbones and five skill categories.

### [HAI: Hierarchical Anchored Interaction for Multi-View Bimanual World Models](https://hai-anon.github.io/)

**NeurIPS 2026**

- Developed a hierarchical conditional architecture for non-interchangeable bimanual actions, asymmetric multi-view evidence, and long-horizon scene drift in bimanual world models.
- Introduced anchored dynamic generation that combines action-conditioned features with persistent per-view scene anchors to suppress identity and geometric drift during long-horizon rollouts.
- Evaluated on AgiBot (11,627 trajectories) and DROID, outperforming baselines across PSNR, SSIM, LPIPS, FID, and FVD.

### [VERDI: Verified Contradictions for Continual World-Model Optimization](https://verdiwm-anno.github.io/)

**Under review**

- Designed an Optimization Fingerprint based on shared, reversible, and dose-calibrated inference probes to characterize responses to interventions such as action scaling, context preservation, first-frame anchoring, and sampling noise.
- Built an intervention-repair geometry and evidence archive that retrieve historical repairs by fingerprint distance and support-set overlap, then allocate trial budgets by confidence.
- Validated the method across nine heterogeneous backbones, 27 leave-one-out campaigns, and 216 transfer decisions, achieving 83% repair-effect sign prediction accuracy and reducing GPU cost by 69%.

### AWARE: Action Weak-spot Assessment before Robotic-world-model Execution

**Under review**

- Proposed a pre-deployment action weak-spot assessment method that identifies action directions likely to induce world-model response errors without access to future environment feedback.
- On CALVIN and RoboCasa, AWARE discovers action-response mismatches more effectively than same-budget random selection, providing a diagnostic signal before deployment.

## Internship Experience

### Beijing Academy of Artificial Intelligence

**Apr. 2026–Present · Pre-training Intern, Embodied World Models**

### NIO

**Oct. 2026–Present · Research Intern, Autonomous Driving Foundation World Models**

## Education

### City University of Hong Kong

**2026–Present · M.S. Student in Electrical and Electronic Engineering**

### Xiamen University

**2022–2026 · Undergraduate in Artificial Intelligence**

## Research Interests

- Embodied Intelligence
- World Models
- Agent-Environment Interaction

## Current Focus

I explore how world models can help intelligent agents understand environments, predict future outcomes, and make more reliable decisions through interaction.

## Contact and Code

Find my public code and future updates on [GitHub](https://github.com/wujunyu687-lab).
