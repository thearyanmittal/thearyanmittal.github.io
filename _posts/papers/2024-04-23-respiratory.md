---
layout: paper
id: respiratory
categories: papers
permalink: papers/respiratory
title: "Detecting Disease from Respiratory Audio"
authors:
  - Aryan Mittal
  - Akshay Raj
  - Arush Verma
  - Mithun Subhash
  - Prajwal Mohan Kumar
url: /papers/respiratory
pdf: https://msub9.github.io/
slides: /slides/respiratory-slides.pdf
video: https://www.youtube.com/watch?v=CtWJa8nO2mg
code: https://github.com/thearyanmittal/respiratory-audio-classification
feature-title: Respiratory Audio Disease Detection
feature-description: "Identifying pulmonary diseases from breathing audio samples."
image: /images/featured/respiratory.png
featured: false
dissertation: true
feature-order: 5
selected: true
type: journal
figure: /images/papers/respiratory.png
---

A supervised and unsupervised learning approach to analyzing breathing audio data collected via stethoscope. We achieve a 91.3% accuracy rate in distinguishing between 7 different respiratory conditions using a ResNet-based architecture on audio spectrograms. This was completed as my final project for Georgia Tech's CS 7641: Machine Learning.

Due to the scarcity of examples in the dataset compared to the number of disease categories, future work on this project will be targeted towards (1) solving the original ICBHI problem of detecting crackles and wheezes in the audio files themselves, (2) making the repo self-contained (e.g., adding a script for data acquisition), and (3) deploying a web app demo for the model. Leading concepts for further research include deep sequential models modified for audio (e.g., [Mamba](https://doi.org/10.1109/SLT61566.2024.10832304), [xLSTM](https://doi.org/10.48550/arXiv.2408.16568), [Degramnet](https://doi.org/10.1007/s00521-023-08849-7), etc.), intelligent encoding of audio clip metadata (e.g., recording device, auscultation location, patient demographics), and more advanced preprocessing methods, such as those implemented in [RespireNet](https://ieeexplore.ieee.org/document/9630091).