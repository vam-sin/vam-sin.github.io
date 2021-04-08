---
title: COVID-19 Diagnosis 
summary: Designed an deep learning model to diagnose COVID-19 from Chest X-rays 
tags:
- DL
date: "2020-07-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Deep learning is being increasingly used in tasks of medical imaging. With the ongoing COVID-19 pandemic, it is crucial to leverage these latest advancements to develop quick and inexpensive methods for diagnosing COVID-19. In this study we curated a DeepC19x (Deep COVID-19 x-ray) image dataset by aggregating chest x-ray images from eight different sources. Five state-of-the-art convolutional neural network models were trained on the DeepC19x dataset and the two best performing models were used to build two fusion models. The proposed DeepC19 model in this study is the prediction fusion model that attained an accuracy of 99.81%, precision of 99.69% and recall of 99.92% on the test portion of the dataset and showcased better performance in terms of the six metrics when compared to the five individual models and the other fusion model. The classification of one input image takes 0.243 of a second on average.