---
title: "Semantically Steerable Image Tokenization"
authors:
  - Danilo de Goede
  - Mohammad Mahdi Derakhshani
  - Yuki M. Asano
  - Cees G. M. Snoek
date: "2026-10-11T00:00:00Z"
doi: ""
publication_types: ["3"]
publication: "arXiv preprint arXiv:2610.15515"
publication_short: ""
abstract: "Adaptive image tokenizers compress an image into a variable number of tokens matched to its complexity, and recent work makes this allocation controllable: conditioned on a target reconstruction error, the tokenizer itself decides how many tokens an image needs. However, the fidelity measure guiding this allocation shapes which aspects of the image are preserved under compression. The pixel-wise error used in prior work is blind to the spatial structure that carries an image's meaning, and under heavy compression such tokenizers are prone to abruptly discarding tokens that encode essential content. We introduce GIST (Guided Image Semantic Tokenizer), an adaptive tokenizer that can be steered toward a requested semantic fidelity. Its token allocation is jointly controlled by pixel-level and semantic target errors, with semantic error measured in the feature space of a frozen DINOv3 encoder. This joint control enables semantic protection: with the semantic target fixed at zero, the reconstruction target can be relaxed to discard pixel detail while preserving what the image depicts. In a controlled comparison on ImageNet-100, GIST outperforms its pixel-controlled counterpart KARL at every token count, with up to 30% lower LPIPS and 37% lower DreamSim. On average, lowering its semantic target reduces LPIPS 2× faster per token than lowering the reconstruction target, and up to 5× in the low-token regime. Semantic fidelity is thus an effective control signal for adaptive tokenization: it lets a tokenizer see, and so preserve, what an image depicts."
summary: We introduce GIST, an adaptive image tokenizer whose token allocation is jointly controlled by pixel-level and semantic target errors, so that heavy compression can discard pixel detail while preserving what the image depicts.
tags:
- Image tokenization
- Adaptive tokenization
- Semantic fidelity
- Self-supervised learning
featured: false
# No standalone page: every link to this entry goes to the project page.
external_link: '/gist-tokenizer/'
searchable: false
_build:
  render: never
  list: always
url_pdf: 'https://arxiv.org/pdf/2610.15515'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://ddgoede.github.io/gist-tokenizer/'
url_slides: ''
url_source: ''
url_video: ''
image:
  caption: ''
  focal_point: ""
  preview_only: false
projects: []
---
