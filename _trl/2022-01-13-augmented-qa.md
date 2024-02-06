---
title: "Augment before You Try: Knowledge-Enhanced Table Question Answering via Table Expansion"
link: https://arxiv.org/pdf/2401.15555.pdf
authors: "Liu et al."
venue: "ArXiv"
year: 2024
abstract: "Table question answering is a popular task that assesses a model’s ability to understand and interact with structured data. However, the given table often does not contain sufficient information for answering the question, necessitating the integration of external knowledge. Existing methods either convert both the table and external knowledge into text, which neglects the structured nature of the table; or they embed queries for external sources in the interaction
with the table, which complicates the process.

In this paper, we propose a simple yet effective method to integrate external information in a given table. Our method first constructs an augmenting table containing the missing information and then generates a SQL query over the
two tables to answer the question. Experiments show that our method outperforms strong baselines on three table QA benchmarks. Our code is publicly available at https://github.com/UCSB-NLP-Chang/Augment_tableQA."
---