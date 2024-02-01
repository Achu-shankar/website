---
title: Non-intrusive Reduced Order Modelling Using Autoencoders
summary: An example of using the in-built project page.
tags:
  - Deep Learning
  - Data-Driven modelling
date: '2023-10-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
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
This project explores the integration of Reduced Order Modeling (ROM) and machine learning, specifically using Autoencoders to perform ROM for fluid systems. The motivation lies in addressing the computational limitations of simulating complex physical systems. ROM techniques aim to reduce computational costs by projecting full-order equations from a high-dimensional space to a lower-dimensional space. Traditional methods, like proper orthogonal decomposition, face challenges with nonlinear mappings, making artificial neural networks, particularly Autoencoders, relevant.

The paper focuses on applying this approach to flow simulation, crucial in fields like aerospace and biomedical engineering. Simulating blood flow aids in understanding diseases, such as predicting aneurysms accurately. ROM is classified into intrusive and non-intrusive methods. Intrusive ROMs manipulate governing equations, requiring access to numerical solver routines, while non-intrusive ROMs learn surrogate models from data. Autoencoders, a type of neural network, play a pivotal role by reconstructing inputs through a bottleneck, compressing data into a latent space representation.

The project's ROM using Autoencoders involves generating training data from a trigonometric function and training the network with randomly generated smooth functions. Results show successful reduction of degrees of freedom, demonstrating the effectiveness of the Autoencoder-based ROM in reconstructing test data. The model's capability to handle unrelated test data highlights its potential for diverse applications, contributing to advancements in reduced-order modeling and fluid simulation.