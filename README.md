# One-Pixel Attack and Defenses in PyTorch

This repository contains a Google Colab notebook that demonstrates **one-pixel, multi-pixel, and targeted attacks** on convolutional neural networks (CNNs) using **Differential Evolution (DE)** optimization.  
We further explore several **defense mechanisms** against such attacks, highlighting the importance of adversarial robustness in modern AI systems.


### For best results run this as a notebook in Google Colab.
---

##  Features

- **Attacks**
  - One-pixel attack (DE-based)
  - Multi-pixel attack (configurable number of pixels)
  - Targeted attack (user selects the desired misclassification class)

- **Defenses**
  - Fine-tuning with poisoned/adversarial samples
  - Preprocessing (pixel-sanitization to remove adversarial perturbations)
  - Ensemble defense (combine predictions from multiple CNN architectures)

- **Visualization**
  - Side-by-side comparison of **original vs. attacked images**
  - Interactive widgets (sliders, buttons, progress bar)
  - Probability distributions before and after attack
  - Attack Success Rate (ASR) evaluation
  - Defense performance plots (stacked bar charts)
