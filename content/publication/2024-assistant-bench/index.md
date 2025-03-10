---
title: AssistantBench Can Web Agents Solve Realistic and Time-Consuming Tasks?
authors:
- Ori Yoran
- admin
- Chaitanya Malaviya
- Ben Bogin
- Ofir Press
- Jonathan Berant
date: '2024-07-22'
publishDate: '2024-07-22T09:16:29.109019Z'
publication_types:
- article-journal
publication: 'Proceedings of the Conference on Empirical Methods in Natural Language Processing'
abstract: Language agents, built on top of language models (LMs), are systems that can interact with complex environments, such as the open web. In this work, we examine whether such agents can perform realistic and time-consuming tasks on the web, e.g., monitoring real-estate markets or locating relevant nearby businesses. We introduce AssistantBench, a challenging new benchmark consisting of 214 realistic tasks that can be automatically evaluated, covering different scenarios and domains. We find that AssistantBench exposes the limitations of current systems, including language models and retrieval-augmented language models, as no model reaches an accuracy of more than 26 points. While closed-book LMs perform well in terms of accuracy, they exhibit low precision and tend to hallucinate facts. State-of-the-art web agents reach a score of near zero. Additionally, we introduce SeePlanAct (SPA), a new web agent that significantly outperforms previous agents, and an ensemble of SPA and closed-book models reaches the best overall performance. Moreover, we analyze failures of current systems and highlight that open web navigation remains a major challenge.
links:
  - icon_pack: fas
    icon: scroll
    name: Link
    url: 'https://www.semanticscholar.org/reader/2026c795a2c0ea07d860bc01843c01f02ed16faf'
  - icon_pack: fab
    icon: github
    name: Code
    url: 'https://assistantbench.github.io/'
---