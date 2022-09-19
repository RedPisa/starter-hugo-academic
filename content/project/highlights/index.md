---
title: Punctate Highlight Removal for Microscopic Images Based on Pix2pixHD
summary: A novel punctate highlight removal network based on pix2pixHD for microscopic images.

tags:
  - Deep Learning
date: '2021-09-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Results of Highlignt Removal
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
**Punctate Highlight Removal for Microscopic Images Based on Pix2pixHD**
- Designed a framework based on pix2pixHD to remove punctate highlights in microscopic images. 
- Proposed a microscopic image dataset consisting of 7500 microscopic images in the size of 256×256 with punctate highlights and 7500 corresponding images without highlights.
- We combine the traditional method of highlight removal with the deep learning model pix2pixHD. The traditional method is employed to generate a binary mask indicating the approximate highlight area as the priori information. Then the mask is concatenated with the 3-channel highlighted microscopic image as the input of the generator.
- Our model is trained by calculating a weighted GAN loss to achieve a better performance of highlight removal. Specifically, we simply increase the weight of loss of highlighted pixels according to the binary mask.

