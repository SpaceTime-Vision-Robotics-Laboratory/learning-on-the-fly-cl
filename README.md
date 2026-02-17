# Learning on the Fly - Presentation Website

<!-- TODO: Update badges when paper is published -->
[![Hugging Face Dataset](https://img.shields.io/badge/🤗-Dataset-yellow)](https://huggingface.co/datasets/sebnae/UAV-IndoorCL)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

This repository contains the source code and assets for the official project website of the paper
**"Learning on the Fly: Replay-Based Continual Object Perception for Indoor Drones"**.

<!-- TODO: Update with actual GitHub Pages link -->
**Live Website:** [spacetime-vision-robotics-laboratory.github.io/learning-on-the-fly-cl](https://spacetime-vision-robotics-laboratory.github.io/learning-on-the-fly-cl/)

## Paper Summary

**Authors:** Sebastian-Ion Nae, Mihai-Eugen Barbu, Sebastian Mocanu, Marius Leordeanu

**Abstract:**

> Autonomous agents such as indoor drones must learn new object classes in real-time 
> while limiting catastrophic forgetting, motivating Class-Incremental Learning (CIL). 
> We introduce an indoor dataset of 14,400 frames capturing inter-drone and ground 
> vehicle footage, annotated via a semi-automatic workflow with 98.6% first-pass 
> labeling agreement. Using this dataset, we benchmark three replay-based CIL strategies: 
> Experience Replay (ER), Maximally Interfered Retrieval (MIR), and Forgetting-Aware 
> Replay (FAR), using YOLOv11n as a resource-efficient detector. Across strict memory 
> budgets (5–10% replay), FAR yields the best performance, achieving an average accuracy 
> of 82.96% (mAP₅₀₋₉₅) with 5% replay.

## Resources
<!-- TODO: Update all links when available -->
- [Paper (PDF)](#)
- [arXiv](https://arxiv.org/abs/2602.13440)
- [Code](#)
- [Dataset](https://huggingface.co/datasets/sebnae/UAV-IndoorCL)

## Local Development

Simply open `index.html` in a browser, or serve with any static file server:
```bash
python -m http.server 8000
```

## Deployment

The site auto-deploys to GitHub Pages via the included workflow
[.github/workflows/github-pages.yml](.github/workflows/github-pages.yml),
which handles image compression and CSS/JS minification.

## Citation
<!-- TODO: Update with full publication details when accepted -->
```bibtex
@article{nae2026learningflyreplaybasedcontinual,
    title   = {Learning on the Fly: Replay-Based Continual Object Perception for Indoor Drones},
    author  = {Nae, Sebastian-Ion and Barbu, Mihai-Eugen and Mocanu, Sebastian and Leordeanu, Marius},
    journal = {arXiv preprint arXiv:2602.13440},
    year    = {2026}
}
```