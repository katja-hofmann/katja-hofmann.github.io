---
layout: post
title: Fast and Reliably Online Learning to Rank for Information Retrieval
comments: true
date: 2013-04-25 16:59:20.000000000 +01:00
type: post
author: Katja Hofmann
published: true
status: publish
categories:
- Thesis
tags:
- information retrieval
- online learning to rank
- reinforcement learning
- search engines
- user behavior
---

My PhD thesis is out! Download a copy from this page, or get in touch if you would like a printed copy. The public defense will be on May 28. at the Agnietenkapel in Amsterdam.

<a href="http://khofm.files.wordpress.com/2013/04/thesis-katja-hofmann-online-learning.pdf"><img class="size-medium wp-image-122" style="border:1px solid #DDDDDD;" alt="Thesis Cover: Fast and Reliable Online Learning to Rank for Information Retrieval" src="{{ site.baseurl }}/assets/thesis-cover-katja-hofmann.png" width="212" height="300" /></a>

Fast and Reliable Online Learning to Rank for Information Retrieval. <a href="http://khofm.files.wordpress.com/2013/04/thesis-katja-hofmann-online-learning.pdf">Download a copy</a> (PDF, 2.9 MB).

*Summary:*

The amount of digital data we produce every day far surpasses our ability to process this data, and finding useful information in this constant flow of data has become one of the major challenges of the 21st century. Search engines are one way of accessing large data collections. Their algorithms have evolved far beyond simply matching search queries to sets of documents. Today's most sophisticated search engines combine hundreds of relevance signals to provide the best possible results for each searcher.

Current approaches for tuning the parameters of search engines can be highly effective. However, they typically require considerable expertise and manual effort. They rely on supervised learning to rank, meaning that they learn from manually annotated examples of relevant documents for given queries. Obtaining large quantities of sufficiently accurate manual annotations is becoming increasingly difficult, especially for personalized search, access to sensitive data, or search in settings that change over time.

In this thesis, I develop new online learning to rank techniques, based on insights from reinforcement learning. In contrast to supervised approaches, these methods allow search engines to learn directly from users' interactions. User interactions can typically be observed easily and cheaply, and reflect the preferences of real users. Interpreting user interactions and learning from them is challenging, because they can be biased and noisy. The contributions of this thesis include a novel interleaved comparison method, called probabilistic interleave, that allows unbiased comparisons of search engine result rankings, and methods for learning quickly and effectively from the resulting relative feedback.

The obtained analytical and experimental results show how search engines can effectively learn from user interactions. In the future, these and similar techniques can open up new ways for gaining useful information from ever larger amounts of data.
