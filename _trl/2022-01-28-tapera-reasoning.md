---
title: "TAPERA: Enhancing Faithfulness and Interpretability in Long-Form Table QA by Content Planning and Execution-based Reasoning"
link: "https://aclanthology.org/2024.acl-long.692.pdf"
authors: "Yilun Zhao et al"
venue: "ACL"
year: 2024
abstract: "Long-form Table Question Answering
(LFTQA) requires systems to generate paragraph long and complex answers to questions
over tabular data. While Large language
models based systems have made significant
progress, it often hallucinates, especially when
the task involves complex reasoning over
tables. To tackle this issue, we propose a new
LLM-based framework, TAPERA, for LFTQA
tasks. Our framework uses a modular approach
that decomposes the whole process into three
sub-modules: 1) QA-based Content Planner
that iteratively decomposes the input question
into sub-questions; 2) Execution-based
Table Reasoner that produces executable
Python program for each sub-question; and 3)
Answer Generator that generates long-form
answer grounded on the program output.
Human evaluation results on the FETAQA and
QTSUMM datasets indicate that our framework
significantly improves strong baselines on
both accuracy and truthfulness, as our modular
framework is better at table reasoning, and
the long-form answer is always consistent
with the program output. Our modular design
further provides transparency as users are able
to interact with our framework by manually
changing the content plans."
---