---
layout: post
title: A Probabilistic Method for Inferring Preferences from Clicks
comments: true
date: 2011-10-26 22:12:16.000000000 +01:00
type: post
author: Katja Hofmann
published: true
status: publish
categories:
- Conference
- Publications
tags:
- information retrieval
- evaluation
- implicit feedback
- research
- search engines
---

At <a href="http://www.cikm2011.org/">CIKM 2011</a>, I presented our paper "<a href="http://ilps.science.uva.nl/biblio/probabilistic-method-inferring-preferences-clicks">A Probabilistic Method for Inferring Preferences from Clicks</a>". It proposes a new method, called Probabilistic Interleaving, for inferring feedback for comparing rankers using click data.

Interleaved comparison methods have been developed recently to compare two candidate rankings (e.g., two similar versions of the ranking algorithm of a search engine) by observing user behavior (in particular clicks on displayed result documents). This form of evaluation is highly scalable, as click data can be collected at very low cost, as long as the search engine is used. It is also assumed to more accurately capture true user preferences than the most common form of evaluation - manual editorial judgments.

Our proposed method addresses problems of sensitivity and fidelity that we identify in previous methods. It is based on a probabilistic interleaving process, where a result list that combines documents from both candidate rankers is generated in such a way that documents that were ranked highly by either ranker are likely to be displayed towards the top of the interleaved list. This interleaved list is displayed to the user, instead of showing either original ranking. User clicks on documents are then assigned to the original rankers in a way that reflects how highly each ranker initially placed these documents. The result is a comparison method that naturally re-weights clicks according to the distance between the original rankings. It is sensitive to even small changes between rankings and at the same time only infers large differences when the distance between the original rankings is large.

An intriguing direction for follow-up work is to investigate how effective the inferred feedback is beyond evaluation setups, e.g., for online learning to rank.
