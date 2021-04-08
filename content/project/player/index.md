---
title: Player Detection in Football Match Videos
summary: Constructed a deep learning model to detect, classify, and track players in a football match video 
tags:
- DL
- CB
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

This task could be divided into three parts:

1. Player Detection
2. Player Classification
3. Player Tracking

To conduct this firstly, the field and the stands were isolated from each frame to leave only the players. The players were then detected using a OpenCV and MobileNetv2 ensemble model. The detected players were then classified based on the color percentages in the bounding boxes. 