---
title: QAMPARI A Benchmark for Open-domain Questions with Many Answers
authors:
- admin
- Tomer Wolfson
- Ohad Rubin
- Ori Yoran
- Jonathan Herzig
- Jonathan Berant
date: '2022-05-25'
publishDate: '2023-12-18T09:16:29.109019Z'
publication_types:
- article-journal
publication: 'Proceedings of the Third Workshop on Natural Language Generation, Evaluation, and Metrics (GEM), ACL'
abstract: Existing benchmarks for open-domain question answering (ODQA) typically focus on questions whose answers can be extracted from a single paragraph. By contrast, many natural questions, such as "What players were drafted by the Brooklyn Nets?" have a list of answers. Answering such questions requires retrieving and reading from many passages, in a large corpus. We introduce QAMPARI, an ODQA benchmark, where question answers are lists of entities, spread across many paragraphs. We created QAMPARI by (a) generating questions with multiple answers from Wikipedia's knowledge graph and tables, (b) automatically pairing answers with supporting evidence in Wikipedia paragraphs, and (c) manually paraphrasing questions and validating each answer. We train ODQA models from the retrieve-and-read family and find that QAMPARI is challenging in terms of both passage retrieval and answer generation, reaching an F1 score of 32.8 at best. Our results highlight the need for developing ODQA models that handle a broad range of question types, including single and multi-answer questions.
links:
  - icon_pack: fas
    icon: scroll
    name: Link
    url: 'https://aclanthology.org/2023.gem-1.9.pdf'
  - icon_pack: fab
    icon: github
    name: Code
    url: 'https://github.com/samsam3232/qampari'
---