---
layout: post
title: State of Tabular AI Report -- Foreword
date: 2026-11-25
featured: false
description: Foreword I wrote for the first State of Tabular AI Report by Gaël Varoquaux and Cailean Osborne (Probabl)
---

Below follows the foreword I was honored to write for the first State of Tabular AI Report, authored by Gaël Varoquaux and Cailean Osborne from Probabl.

---


## Foreword for the State of Tabular AI Report

Tabular data has been the bread and butter of organizations for ages, driving high-value tasks in healthcare, the humanities, finance, logistics, you name it! So back in 2021, fresh from a data scientist role in industry, where scikit-learn was my primary tool and tables were all I saw, I was surprised that tabular data wasn’t yet a first-class citizen of the deep learning era, unlike text and images. What was missing was a community for Tabular AI, akin to those for language and vision. Long story short, while wrapping up my PhD on AI for tabular semantics, I proposed the first Tabular AI workshop at NeurIPS 2022. And there we were, in a small room in New Orleans: researchers and practitioners from all over the world, with a shared love for tables and a common belief in the potential of Tabular AI. One of them was Gaël Varoquaux, a suggested panel guest (hat-tip Sebastian Raschka!). I’m glad he joined, as he brought a lot of passion to the table, and has since become a much-valued member of the community and a leader in the field.

What always excites me is how the scientific Tabular AI community involves perspectives from machine learning, information retrieval, natural language processing, and databases. Pre-training had already been explored for tabular reasoning, retrieval, and data preparation, but predictive tasks were still mainly tackled with table-specific deep learning models. At that same workshop, however, Noah Hollmann, Samuel Müller, Katharina Eggensperger, and Frank Hutter presented TabPFN, which extended pre-training and in-context learning to predictive tasks. Tabular foundation models (TFMs) were born. The paper went viral, but also triggered criticism from seasoned data scientists who considered deep learning for tables a dead end: “XGBoost For The Win.” Gaël, who had been at the forefront of building the statistical principles, methodological rigor, and infrastructure of data science through scikit-learn, was instead genuinely excited. As a true scientist, he understood that new ideas take time to mature. Naturally, it didn’t take long for Gaël, Marine Le Morvan, David Holzmüller and Jingang Qu to introduce a strong new TFM architecture, TabICL, which not only headed the leaderboards but also pushed the standards for open-source, open-weight, and permissively-licensed models. Now, many TFMs adopt ideas Gaël and the TabICL team introduced.

Over the years, at conferences and during visits to the SODA team in Paris, Gaël and I discussed how TFMs could be trained on real data, whether their true value lies in scaling to enterprise-level datasets, and how the stages of data science from retrieval and data preparation to model selection and validation, might come together in end-to-end systems, as we now see in agentic data science. It might not be said often, but having open-minded, principled but constructive, and kind researchers like Gaël at the heart of a community matters a lot. It makes the Tabular AI community healthy, inspiring, and vibrant.
Fast-forward to the end of 2026, and Tabular AI is a flourishing research community, with persistent contributors, solid benchmarks, cross-group collaborations, and successful startups – impact! And so many questions remain open. What should the scope of a tabular foundation model be? Where do synthetic priors thrive, and when are real tables necessary? How can we best use world knowledge? Where can we give agents autonomy, and where not? And what are the moonshots and boundaries for Tabular AI?

The report in front of you, the first report on the “State of Tabular AI”, reflects on the developments across the community. I was excited to hear about this initiative, and to see how it fittingly starts with the always-returning questions of what constitutes a table and what is the scope of Tabular AI. Discussing these fundamental questions with Cailean Osborne, who has a background in social data science, through the lens of observed phenomena, was so refreshing. His overarching views and clarity of thought read throughout the report. Together, Cailean and Gaël weave the foundation and modern trends in Tabular AI neatly together throughout the core constructs of modern data science: methodological principles and infrastructure established in scikit-learn (Chapter 2), tabular foundation models as the new predictive kid on the block (Chapter 4), and the promising agentic paradigm that can supercharge data science, if done well (Chapter 5). To me, this report signals the maturity and potential of this community, and I hope it is the first in the series.

Enjoy reading, reflecting, imagining, and hopefully contributing to the future State of Tabular AI!

Madelon Hulsebos

Amsterdam, November 2026


---


<b><a href="https://hello.probabl.ai/state-of-tabular-ai-report-2026?" target="blank">Link to report here (unfortunately it's behind an email wall, but it is free!)</a></b>