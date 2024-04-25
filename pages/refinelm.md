---
layout: page
title: "The Balancing Act"
description:
permalink: /asrbias/
---


# Refine-LM

In the field of spoken language understanding, systems like Whisper and Multilingual Massive Speech (MMS) have shown state-of-the-art performances. This study is dedicated to a comprehensive exploration of the Whisper and MMS systems, with a focus on assessing biases in automatic speech recognition (ASR) inherent to casual conversation speech specific to the Portuguese language. Our investigation encompasses various categories, including gender, age, skin tone color, and geo-location. Alongside traditional ASR evaluation metrics such as Word Error Rate (WER), we have incorporated p-value statistical significance for gender bias analysis. Furthermore, we extensively examine the impact of data distribution and empirically show that oversampling techniques alleviate such stereotypical biases. This research represents a pioneering effort in quantifying biases in the Portuguese language context through the application of MMS and Whisper, contributing to a better understanding of ASR systems' performance in multilingual settings.

# Table of Contents
- [Introduction](#introduction)
- [Contributions](#contributions)
- [Dataset Statistics](https://biasinai.github.io/dataset)
## Introduction
With the introduction of large language models, there has been significant concern about the unintended bias such models may inherit from their training data. A number of studies have shown that such models propagate gender stereotypes, as well as geographical and racial bias, among other biases. While existing works tackle this issue by preprocessing data and debiasing embeddings, the proposed methods require a lot of computational resources and annotation effort while being limited to certain types of biases. To address these issues, we introduce \method{}, a debiasing method that uses reinforcement learning to handle different types of biases without any fine-tuning. By training a simple model on top of the word probability distribution of any LLM, our bias agnostic reinforcement learning method enables model debiasing without human annotations or significant computational resources. Experiments conducted on a wide range of models, including several LLMs, show that our method (i) significantly reduces stereotypical biases while preserving LLMs performance; (ii) is applicable to different types of biases, generalizing across contexts such as gender, ethnicity, religion, and nationality-based biases; and (iii) it is not expensive to train.
