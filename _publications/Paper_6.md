---
title: "LASER: An LLM-based ASR Scoring and Evaluation Rubric"
collection: publications
ispaper: "yes"
permalink: /publication/6
excerpt: 'LASER is an LLM-based ASR evaluation metric that aligns closely with human judgments by capturing linguistic nuances across Indian languages better than traditional metrics.'
date: 2025-11-11
venue: 'Published at EMNLP 2025 (Main conference)'
slidesurl: 'http://amparulekar.github.io/files/EMNLP-2025_main-2768_POSTER.pdf'
paperurl: 'https://arxiv.org/pdf/2510.07437'
citation: 'Amruta Parulekar and Preethi Jyothi. 2025. LASER: An LLM-based ASR Scoring and Evaluation Rubric. In Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing, pages 24773–24782, Suzhou, China. Association for Computational Linguistics.'
---

Standard ASR evaluation metrics like Word Error Rate (WER) tend to unfairly penalize morphological and syntactic nuances that do not significantly alter sentence semantics. We introduce an LLM-based scoring rubric LASER that leverages state-of-the-art LLMs' in-context learning abilities to learn from prompts with detailed examples. Hindi LASER scores using Gemini 2.5 Pro achieved a very high correlation score of 94% with human annotations. Hindi examples in the prompt were also effective in analyzing errors in other Indian languages such as Marathi, Kannada and Malayalam. We also demonstrate how a smaller LLM like Llama 3 can be finetuned on word-pair examples derived from reference and ASR predictions to predict what kind of penalty should be applied with close to 89% accuracy.
