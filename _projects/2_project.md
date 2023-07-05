---
layout: page
title: NAACL 2019
slides: Slide
description: Ranking and Selecting Multi-Hop Knowledge Paths 
img: assets/img/naacl_2019.png
slide_pdf: naacl_2019.pdf
importance: 1
category: work
---
Abstract: 
To make machines better understand sentiments, research needs to move from polarity identification to understanding the reasons that underlie the expression of sentiment. Categorizing the goals or needs of humans is one way to explain the expression of sentiment in text. Humans are good at understanding situations described in natural language and can easily connect them to the character's psychological needs using commonsense knowledge. We present a novel method to extract, rank, filter and select multi-hop relation paths from a commonsense knowledge resource to interpret the expression of sentiment in terms of their underlying human needs. We efficiently integrate the acquired knowledge paths in a neural model that interfaces context representations with knowledge using a gated attention mechanism. We assess the model's performance on a recently published dataset for categorizing human needs. Selectively integrating knowledge paths boosts performance and establishes a new state-of-the-art. Our model offers interpretability through the learned attention map over commonsense knowledge paths. Human evaluation highlights the relevance of the encoded knowledge.


**TL;DR:** In our work, we aim to go beyond the detection of sentiment toward explaining sentiments. 
<div class="post">
  <header class="post-header">
        <h1 class="post-title">{{ page.slides }} {% if page.slide_pdf %}<a href="{{ page.slide_pdf | prepend: 'assets/pdf/' | relative_url}}" target="_blank" rel="noopener noreferrer" class="float-right"><i class="fas fa-file-pdf"></i></a>{% endif %}</h1>
  </header>
</div>
