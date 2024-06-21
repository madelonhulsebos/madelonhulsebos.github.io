---
layout: post
title: "Attended SIGMOD!"
categories: Work
---

Attended SIGMOD in Chile! It was fun and busy, Santiago was lovely. Co-organized the DEEM workshop and presented the <a href="https://www.madelonhulsebos.com/assets/dataset_search_survey.pdf" target="blank">survey on dataset search in practice</a> at HILDA. Generally, discussions and talks about retrieval, (structured) data semantics, and vector databases had my particular interest this year.<br>

Panels and talks on AI for DBs reiterated the importance of semantics of relational data in tasks such as text-to-sql, and confirmed that we're not there yet. The ability to properly embed and generate from structured data came up in discussions often, which we explored in our <a href="https://x.com/MadelonHulsebos/status/1803095639238254805" target="blank">Observatory paper</a> to be presented at VLDB 2024. Definitely excited to see if the presented measures (to evaluate the reflection of table properties in table embeddings) can help inform new models, e.g. loss functions and model architectures.

As I'm currently working on dataset search through embeddings (focused on structured data, of course) at UC Berkeley, I was pleased to chat with folks on this topic, e.g. Luis Oala, Juan Sequeda, and Lennart Behme, with some exciting ideas and initiatives in the pipeline.<br>

When it comes to research: industry is making strides with integrating LLMs into data systems (or demos thereof) but discloses little about accuracy and challenges in real-world settings. As a community we seem to explore relevant and unique data management angles to generative AI, while focusing on low-hanging fruit first, food for thought.<br>

A few contributions I made to SIGMOD 2024:
- SIGMOD started with the Data Management for End-to-End ML workshop, that I co-organized with Shreya Shankar and Matteo Interlandi, which brought together an engaging audience and interesting discussions. Full proceedings can be found <a href="https://dl.acm.org/doi/proceedings/10.1145/3650203" target="blank">here</a>.<br>
- In the middle, Till Doehmen presented our work on <a href="https://schemapile.github.io/" target="blank">SchemaPile</a>, another useful large-scale corpus extracted from GitHub to fuel AI models for data management. I'm excited to see what can be done with this corpus, from (synthetic) schema and data generation/completion, to metadata enrichment tasks for existing databases, among others.<br>
- On Friday at the <a href="https://x.com/hildaworkshop/status/1801689157607244047" target="blank">human-in-the-loop data anlysis (HILDA) workshop</a>, I presented some <a href="https://www.madelonhulsebos.com/assets/dataset_search_survey.pdf" target="blank">insights from a survey on dataset search in practice</a>, and concluded:
1) while most recent research focuses on dataset search for data augmentation, "basic" dataset search (i.e. finding datasets through a set of keywords) is not a solved problem,
2) current data search systems are too inflexbile in search expression and require too many humans in the loop to inform the search need making it a time-consuming process,
3) search should be iterative (flexible search iteration instead of one-shot search query), hybrid (raw metadata and semantics), task-driven (explain what you want to do instead of what you need - data scientists typically lack deep domain data expertise), comprehsensible (navigating a list of 1000 tables is not OK).
This largely resonates with ideas expressed in this <a href="https://koaning.io/posts/search-boxes/" target="blank">nice blogpost on searching ArXiv by Vincent Warmerdam</a>, stay tuned for more on this...
