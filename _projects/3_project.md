---
layout: page
title: Findings: EMNLP 2020
slides: Slide
description: Social Commonsense Reasoning with Multi-Head Knowledge Attention
img: assets/img/emnlp_2020.png
slide_pdf: emnlp_2020.pdf
importance: 1
category: work
---
Abstract: 
Social Commonsense Reasoning requires an understanding of the text, knowledge about social events and their pragmatic implications, as well as commonsense reasoning skills. In this work, we propose a novel multi-head knowledge attention model that encodes semi-structured commonsense inference rules and learns to incorporate them in a transformer-based reasoning cell. We assess the model’s performance on two tasks that require different reasoning skills: Abductive Natural Language Inference and Counterfactual Invariance Prediction as a new task. Our proposed model improves performance over strong state-of-the-art models (i.e., RoBERTa) across both reasoning tasks. Notably, we are, to the best of our knowledge, the first to demonstrate that a model that learns to perform counterfactual reasoning helps predict the best explanation in an abductive reasoning task. We validate the robustness of the model’s reasoning capabilities by perturbing the knowledge and providing qualitative analysis of the model’s knowledge incorporation capabilities.

**TL;DR:** In this paper, we investigate social commonsense reasoning in narrative contexts. Specifically, we address two different reasoning tasks: language-based abductive reasoning and counterfactual invariance prediction. 
<div class="post">
  <header class="post-header">
        <h1 class="post-title">{{ page.slides }} {% if page.slide_pdf %}<a href="{{ page.slide_pdf | prepend: 'assets/pdf/' | relative_url}}" target="_blank" rel="noopener noreferrer" class="float-right"><i class="fas fa-file-pdf"></i></a>{% endif %}</h1>
  </header>
</div>
