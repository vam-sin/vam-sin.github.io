---
title: Adaptive Bitrate Estimation using Reinforcement Learning
summary: Advanced the state-of-the-art A3C model implemented in Pensieve by increasing exploration using the Follow then Forage technique 
tags:
- RL
date: "2020-09-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
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

Adaptive Bitrate (ABR) algorithms are highly important when it comes to a greater video streaming experience. Reinforcement learning has proved to be extremely useful in this domain. In this study, we propose the NANCY-FFE model which uses the Asynchronous Advantage Actor-Critic network with Follow then Forage Exploration to increase the entropy-based explorations in the Pensieve model. The model was trained on the 3G/HSDPA dataset and compared with 6 other ABR models by testing on the 3G/HSDPA and FCC traces datasets using three different Quality of Experience (QoE) metrics. On two of the metrics, it showcased a maximum increase of 12.44%. In addition, it takes less time for training. This presents a promising advancement of state-of-the-art reinforcement learning based adaptive bitrate algorithms.