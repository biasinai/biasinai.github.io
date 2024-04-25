---
layout: page
title: "Refine-LM"
description:
permalink: /refinelm/
---


# Refine-LM

With the introduction of large language models, there has been significant concern about the unintended bias such models may inherit from their training data. A number of studies have shown that such models propagate gender stereotypes, as well as geographical and racial bias, among other biases. While existing works tackle this issue by preprocessing data and debiasing embeddings, the proposed methods require a lot of computational resources and annotation effort while being limited to certain types of biases. To address these issues, we introduce \method{}, a debiasing method that uses reinforcement learning to handle different types of biases without any fine-tuning. By training a simple model on top of the word probability distribution of any LLM, our bias agnostic reinforcement learning method enables model debiasing without human annotations or significant computational resources. Experiments conducted on a wide range of models, including several LLMs, show that our method (i) significantly reduces stereotypical biases while preserving LLMs performance; (ii) is applicable to different types of biases, generalizing across contexts such as gender, ethnicity, religion, and nationality-based biases; and (iii) it is not expensive to train.


# Table of Contents
- [Introduction](#introduction)
- [Contributions](#contributions)
- [Dataset Statistics](https://biasinai.github.io/dataset)
