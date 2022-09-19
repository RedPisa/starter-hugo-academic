---
title: Bachelor Thesis
summary: A Weakly-Supervised Image Classification Framework Based on Graph Convolutional Networks

tags:
  - Deep Learning
date: '2022-06-30T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Framework Overview
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
**Bachelor Thesis:** A Weakly-Supervised Image Classification Framework Based on Graph Convolutional Networks
- A feasible framework based on graph convolutional networks (GCN) for weakly supervised image classification is built, including deep feature extraction, graph construction, and weakly supervised graph convolutional networks.
- Considering a single image as a vertex, autoencoder and SimCLR are employed to extract discriminative node features. Then two similarity-based strategies for adjacency matrix construction are designed.
- Initial residual connection and identity mapping methods are injected into SelfSAGCN, a model for weakly-supervised node classification, to ease the over-smoothing problem and improve its performance.
- The framework achieves better performance on CIFAR-10 and STL-10 datasets, compared with existing weakly-supervised image classification models based on GCNs.
