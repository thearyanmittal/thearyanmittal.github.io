---
layout: paper
id: hateful-memes
categories: papers
permalink: papers/hateful-memes
title: "Mamba-Based Approaches to the Identifying Hateful Memes Challenge"
authors:
  - Aryan Mittal
  - Michael Liu
  - Eric Yeon
  - Prajwal Mohan Kumar
url: /papers/hateful-memes
pdf: /papers/hateful-memes-paper.pdf
feature-title: Identifying Hateful Memes with Mamba
feature-description: "Fine-tuning and evaluating multimodal Mamba architectures on detecting hateful memes."
image: /images/featured/hateful-memes.png
featured: false
dissertation: true
feature-order: 6
selected: true
type: journal
figure: /images/papers/hateful-memes.png
---

The [hateful memes challenge](https://papers.neurips.cc/paper_files/paper/2020/file/1b84c4cee2b8b3d823b30e2d604b1878-Paper.pdf) is a multimodal classification task posed by FAIR that requires models to detect hate speech by understanding subtle relationships between the captions and images of memes. [Mamba](https://arxiv.org/abs/2312.00752) is a state-space model (SSM) that processes sequences using a selective scan mechanism that purports to be more efficient than transformers. In this paper, we implement multiple variations of Mamba-based architectures and apply them to the hateful memes dataset. Our experiments show that Mamba generally performs worse than transformer-based architectures at the task, in line with [later](https://dl.acm.org/doi/10.5555/3692070.3693514) [works](https://aclanthology.org/2023.tacl-1.31/) that confirm transformer dominance over state-space models. This was completed as the final project for Georgia Tech's CS 7643: Deep Learning course.