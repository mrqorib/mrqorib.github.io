---
layout: post
title: Frustratingly Easy System Combination for Grammatical Error Correction
subtitle : Muhammad Reza Qorib, Seung-Hoon Na, Hwee Tou Ng
venue: Annual Conference of the North American Chapter of the Association for Computational Linguistics (NAACL). 2022
tags: [Grammatical Error Correction]
pdf: ESC.pdf
code: https://github.com/nusnlp/esc
author: M. Reza Qorib
comments : False
---

In this paper, we formulate system combination for grammatical error correction (GEC) as a simple machine learning task: binary classification. We demonstrate that with the right problem formulation, a simple logistic regression algorithm can be highly effective for combining GEC models. Our method successfully increases the F0.5 score from the highest base GEC system by 4.2 points on the CoNLL-2014 test set and 7.2 points on the BEA-2019 test set. Furthermore, our method outperforms the state of the art by 4.0 points on the BEA-2019 test set, 1.2 points on the CoNLL-2014 test set with original annotation, and 3.4 points on the CoNLL-2014 test set with alternative annotation. We also show that our system combination generates better corrections with higher F0.5 scores than the conventional ensemble.
