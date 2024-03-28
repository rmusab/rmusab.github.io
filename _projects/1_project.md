---
layout: page
title: Vulnerability and Malware Detection (Cybersecurity) 
description: Exploring key research questions in the field of cybersecurity. What are the challenges and future directions in ensuring software security?
img: assets/img/cybersecurity.jpg
importance: 1
category: work
related_publications: Mussabayev2023-dissecting, Shestov2024-finetuning
giscus_comments: true
---

Using the instruments of machine learning, my team at Huawei is trying to answer the following broad research questions:

1. What is the minimal context size necessary to represent and unambiguously classify a vulnerability in a static piece of source code (written in Java or C++)?
2. How can we build a tool that would automatically locate this minimal context size inside a given big piece of source code (like the entire code of a GitHub project), as well as rank the relevance of different parts of the context?
3. How can we train this vulnerability-locating tool so that it maximizes the coverage of potential vulnerabilities in the input code?
4. What kind of more powerful model could we use to perform a more precise analysis of the extracted context? Would a Large Language Model (LLM), like GPT-4, suffice for that purpose? If yes, what combination of generation regimes would be most effective (like data flow analysis with chain-of-thought reasoning and self-reflection)?
5. How to compile a real-world high-quality dataset without mislabeling for training and testing all the above-mentioned hypotheses?