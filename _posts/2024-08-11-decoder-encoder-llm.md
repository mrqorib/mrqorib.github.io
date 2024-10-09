---
layout: post
title: "Are Decoder-Only Language Models Better than Encoder-Only Language Models in Understanding Word Meaning?"
subtitle : Muhammad Reza Qorib, Moon Geonsik, and Hwee Tou Ng
venue: Findings of the Annual Meeting of the Association for Computational Linguistics (ACL). 2024
tags: [Large Language Models, Word Sense Disambiguation]
pdf: Decoder-Encoder-LLM.pdf
author: M. Reza Qorib
comments : False
---
The natural language processing field has been evolving around language models for the past few years, from the usage of n-gram language models for re-ranking, to transfer learning with encoder-only (BERT-like) language models, and finally to large language models (LLMs) as general solvers. LLMs are dominated by the decoder-only type, and they are popular for their efficacy in numerous tasks. LLMs are regarded as having strong comprehension abilities and strong capabilities to solve new unseen tasks. As such, people may quickly assume that decoder-only LLMs always perform better than the encoder-only ones, especially for understanding word meaning. In this paper, we demonstrate that decoder-only LLMs perform worse on word meaning comprehension than an encoder-only language model that has vastly fewer parameters.
