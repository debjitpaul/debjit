---
layout: page
title:  COMMA 2020
slides: Slide
description: Argument Relation Classification presented at 8th International Conference on Computational Models of Argument 
img: assets/img/comma_paper.png
slide_pdf: COMMA_67_slides.pdf
importance: 1
category: work
---
Abstract: 
A common conception is that the understanding of relations that hold between argument units requires knowledge beyond the text. But to date, argument analysis systems that leverage knowledge resources are still very rare. In this paper, we propose an unsupervised graph-based ranking method that extracts relevant multi-hop knowledge from a background knowledge resource. This knowledge is integrated into a neural argumentative relation classifier via an attention-based gating mechanism. In contrast to prior work, we emphasize the selection of relevant multi-hop knowledge and apply methods to automatically enrich the knowledge resource with missing knowledge. We assess model performance on two datasets, showing considerable improvement over strong baselines.


<div class="post">
  <header class="post-header">
        <h1 class="post-title">{{ page.slides }} {% if page.slide_pdf %}<a href="{{ page.slide_pdf | prepend: 'assets/pdf/' | relative_url}}" target="_blank" rel="noopener noreferrer" class="float-right"><i class="fas fa-file-pdf"></i></a>{% endif %}</h1>
  </header>
</div>

