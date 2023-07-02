---
layout: post
title: Social Commonsense Reasoning with Structured Knowledge in Text 
date: 2022-04-23 15:53:00-0400
description: Social Commonsense Reasoning with Structured Knowledge in Text
categories: PhD_Thesis blockquotes
giscus_comments: true
related_posts: true
---



Understanding a social situation requires the ability to reason about the underlying emotions and behaviour of others. For example, when we read a \textit{personal story}, we use our prior commonsense knowledge and social intelligence to infer the emotions, motives, and anticipate the actions of the characters in a story. For machines to understand text related to *personal stories and social conversations*, they must be able to make commonsense inferences. While most people can reason deeply about the social implications of the text, it is challenging for natural language processing systems as these implications are often subtle and implicit. 

This dissertation argues that NLP systems must learn to reason more explicitly about the underlying social knowledge in text to perform social commonsense reasoning. We divide the above argument into two sub-problems: (i) understanding the underlying social knowledge and (ii) explicitly reasoning about such knowledge for social commonsense reasoning. To address these problems, we propose building NLP systems that integrate neural network based learning with structured knowledge representations. 

In the first part of this dissertation, we study the role of structured commonsense knowledge in understanding the social dynamics of characters and their actions in stories. Our motivation behind enriching the model with structured commonsense knowledge is to bridge the gap between surface meanings of texts and the underlying social implication of each event in the stories. We develop a novel model that incorporates commonsense knowledge into neural models and showcases the importance of commonsense knowledge in understanding social dynamics of story characters. Further, we investigate the role of temporal dynamics of story events in understanding social situations. We develop a model that can explicitly learn about *what social event follows another event* from personal narrative stories. We demonstrate that *implicitly* leveraging such temporal knowledge about story events can support social commonsense reasoning tasks. 

In the second part of this dissertation, we investigate methods to explicitly reason about the knowledge related to social dynamics of characters (*behavior, mental states*) and cause/effect of social events. We propose a novel model named as *multi-head knowledge attention* that incorporates such social knowledge into state-of-the-art neural NLP models to address two complex commonsense inference tasks. We demonstrate that our method of incorporating knowledge can improve -- (i) the robustness and the interpretability of the model and (ii) the overall performance of the model compared to other knowledge integration methods. We also aim to investigate social commonsense reasoning as a natural language generation task. We design a story completion task that requires natural language generation models to perform both forward and backward reasoning. We study the role of contextualized commonsense knowledge in natural language generation tasks. We propose a model that jointly learns to generate contextualized inference rules as well as narrative stories. We demonstrate that our model can outperform state-of-the-art non-contextualized commonsense knowledge-based generation models. 

We hope that the research presented in this dissertation will open up interesting scopes for future research involving social commonsense reasoning and other related topics.
