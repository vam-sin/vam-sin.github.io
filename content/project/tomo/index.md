---
title: Tomogram Analysis
summary: Classified sub-tomograms according to the biomolecules present in them using various deep learning techniques
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

The aim of our experiment was to successfully classify
given data into the ten different categories of protein macro-
molecules. Convolutional Neural Network (CNN) models are a
widely used classification method. It can achieve significantlyhigher classification accuracy than other rotation invariant fea-
ture based methods. Additionally, CNN models scale linearly
with respect to the number of inputs, given fixed subtomogram
size and class number. Thus, we adapted a simple CNN architecture
which achieved a high accuracy for classification tasks. The
CNN architecture consists of two blocks. Each block is com-
prised of two convolution layers and one max pool layer. The
first block uses 32 filters on each convolution layer, whereas
the second uses 64 filters on each of the two convolution
layers. All convolution layers use ‘ReLU’ activations. These
blocks are followed by two fully connected layers of 512
neurons respectively. Finally, the output layer of 10 units uses
a ‘Softmax’ activation.

We separated each of the three sets of subtomograms into
training and testing sets with ratio 4:1. We used 80% of our
data for model fitting and the rest for validation.
In our experiments, we were able to achieve relatively high
validation accuracy for all SNR levels. Our results show that
lower SNR ratios lead to lower classification accuracy. We
see that the CNN model has achieved the highest
accuracy for data with infinite SNR, and the lowest for SNR
0.03.