---
title: 'Spatial Temporal Graph Convolution with Graph Structure Self-learning for Early MCI Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Fugen Zhou
  - Bin Guo
  - Bo Liu

# Author notes (optional)
author_notes:
  -
  -
  - corresponding author
  - corresponding author

date: '2022-11-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *arXiv*, submitted to *ISBI* 2023
publication_short: In *arXiv*, submitted to *ISBI* 2023

abstract: Graph neural networks (GNNs) have been successfully applied to early mild cognitive impairment (EMCI) detection, with the usage of elaborately designed features constructed from blood oxygen level-dependent (BOLD) time series. However, few works explored the feasibility of using BOLD signals directly as features. Meanwhile, existing GNN-based methods primarily rely on hand-crafted explicit brain topology as the adjacency matrix, which is not optimal and ignores the implicit topological organization of the brain. In this paper, we propose a spatial temporal graph convolutional network with a novel graph structure self-learning mechanism for EMCI detection. The proposed spatial temporal graph convolution block directly exploits BOLD time series as input features, which provides an interesting view for rsfMRIbased preclinical AD diagnosis. Moreover, our model can adaptively learn the optimal topological structure and reﬁne edge weights with the graph structure self-learning mechanism. Results on the Alzheimer’s Disease Neuroimaging Initiative (ADNI) database show that our method outperforms state-of-the-art approaches. Biomarkers consistent with previous studies can be extracted from the model, proving the reliable interpretability of our method.

# Summary. An optional shortened abstract.
summary: This paper proposes a spatial temporal model for EMCI classification with a novel graph structure self-learning mechanism, which can adaptively learns the optimal spatial dependencies between brain regions. Our model exploits BOLD time series as input features directly, which provides a new perspective for rsfMRI-based preclinical AD diagnosis. Results on the ADNI database show superior performance of our method compared with state-of-the-art models. Moreover, EMCI-contributory brain regions consistent with existing literature can be excavated, proving the reliable interpretability of our framework.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: Framework Overview
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
