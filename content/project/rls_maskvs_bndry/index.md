---
title: Retinal Layer Segmentation - Boundary vs Mask Labels
date: 2025-06-22

summary: Experimenting boundary vs masks segmentations.



external_link: ""
tags:
  - Experimentation
  - Deep learning
  - Generative AI
  - Pixel level precision
  - Medical image analytics
  - Metrics
  - Inter-grading reliability 
---
<!-- ## Mask vs Boundary Label Training: A Comparative Analysis for Retinal Layer Segmentation -->

## Introduction

The spark for this project was ignited by a question that echoed through the research community after my earlier work on weakly supervised retinal layer segmentation: *Why generate images with boundary labels instead of the conventional mask-based approach?* This curiosity set the stage for a journey of rigorous experimentation and discovery.

## Experimentation
Determined to find answers, I designed a comprehensive study to compare these two labeling strategies head-to-head. The goal was simple yet ambitious: to empirically test whether boundary-based training could offer tangible advantages over traditional mask-based training, and to see if these benefits would hold across a variety of neural network architectures.

The experimental process was both challenging and enlightening. I assembled a diverse suite of UNet architectures, ranging from classic designs to deeper, more complex variants. Each model was trained and evaluated under two regimes: one using detailed boundary labels that highlight the edges of retinal layers, and the other using conventional pixel-wise masks. To ensure fairness, every experiment used identical datasets, standardized training protocols, and carefully controlled variables.

## Results

As the results began to emerge, a clear pattern took shape. Boundary-based training consistently outperformed mask-based training across all tested architectures. The models trained on boundaries not only achieved higher subjective scores—especially in capturing fine anatomical details—but also demonstrated more stable and scalable performance, whether in standalone UNets or within adversarial GAN frameworks. Interestingly, while convolutional neural networks are naturally adept at detecting edges due to their differential kernels, achieving high pixel-level accuracy for boundaries remained a nuanced challenge, reflecting the inherent variability in human grading and inviting a better metric than dice score or mean pixel error. 

What made these findings particularly exciting was their architecture-agnostic nature. Whether using a simple UNet or a sophisticated GAN-enhanced model, the benefits of boundary training persisted. This robustness suggested that the approach could be widely adopted, offering practical value for both research and clinical deployment.

Beyond the technical achievements, this project stands as a testament to the importance of research validation. By proactively addressing questions from the community and designing experiments that go beyond single-model validation, I was able to advance my understanding while supporting real-world applications. The journey from hypothesis to evidence not only deepened my appreciation for experimental rigor but also reinforced the value of curiosity-driven inquiry in shaping the future of medical AI.

---

*This story highlights the evolution from research innovation to research validation, emphasizing the power of thoughtful experimentation and the impact of challenging conventional wisdom in AI-driven medical imaging.*
