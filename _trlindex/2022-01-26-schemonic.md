---
title: "Generating Succinct Descriptions of Database Schemata for Cost-Efficient Prompting of Large Language Models"
link: "https://itrummer.github.io/drafts/SchemonicDraft.pdf"
authors: "Immanuel Trummer"
venue: "VLDB"
year: 2024
abstract: "Using large language models (LLMs) for tasks like text-to-SQL translation often requires describing the database schema as part of
the model input. LLM providers typically charge as a function of the number of tokens read. Hence, reducing the length of the schema description saves money at each model invocation. This paper introduces Schemonic, a system that automatically finds concise text descriptions of relational database schemata. By introducing abbreviations or grouping schema elements with similar properties, Schemonic typically finds descriptions that use significantly fewer tokens than naive schema representations. Internally, Schemonic models schema compression as a combinatorial optimization problem and uses integer linear programming solvers to find guaranteed optimal or near-optimal solutions. It speeds up optimization by starting optimization from heuristic solutions and reducing the search space size via pre-processing. The experiments on TPC-H, SPIDER, and Public-BI demonstrate that Schemonic reduces schema description length significantly, along with fees for reading them, without reducing the accuracy in tasks such as text-to-SQL translation."
---