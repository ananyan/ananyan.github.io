---
layout: page
title: Measures of product similarity
description: research
img: assets/img/DesignSim/analogyexample.png
category: 2021
---

## <u>Overview</u>
**My Role:** Lead researcher   
**Tools/Skills:** Network Analysis, Survey Design, Triplet Embedding, Semantic Embedding, Image Classification, Statistical Analysis, MATLAB, Python   
**Timeline:** August 2019 - August 2021, May 2023 - August 2024 (3.25 years)  
**Team:** N/A

## <u>Context</u>
Similarity is a fundamental concept that helps humans make sense of the world around them, ranging from recognizing and categorizing objects, to conducting more complex tasks like analogical reasoning. Therefore, the way humans internally represent similarity can influence how they structure their ideas, knowledge, and even decisions. Aside from relevance to cognition, capturing similarity is crucial for enabling large-scale search, informational retrieval, recommendation, or decision-support systems. For example, e-commerce websites try to recommend products that are similar to ones consumers have searched for and music streaming applications try to enhance playlists by adding similar songs. Quantifying similarity in the right way is challenging, but critical, for a multitude of applications, one of which is supporting creativity and ideation during early-stage design. In this context, similarity can be considered from functional, visual, and semantic perspectives. Functional similarity can help designers transfer knowledge about the purpose and mechanism of a system into an innovative solution to a new problem. Visual and semantic similarity are relevant in enabling designers to convey the meaning of a product, in comparison to other products and the external environment, to users. 

## <u>Goal</u>
- Evaluate different similarity measures, including mathematical approaches and human-centered approaches, and how they impact product retrieval at a functional level
- Understand how product similarity can be conveyed at a visual and semantic level
- Establish an understanding of how similarity plays a role in product design, providing guidelines for the development and use of similarity measures for relevant contexts and application

## <u>Outcomes</u>
1) Analyzed 100 products (ranging in complexity from systems like wind turbines to household appliances to toys) for their similarity in function using 6 different mathematical measures across 2 different mathematical representations (vectors and graphs)
   
2) Designed surveys to collect over 1000 triplet ratings ("Is A more similar to B or to C?") that considered variable dimensions of product similarity (Are the products similar in their purpose or in how they work?). Used the triplets to train low-dimensional embeddings from the triplet ratings to obtain measures of human-perceived functional similarity between products

3) Determined that graph-based measures could *better* capture human-perceived similarity across the variable dimensions, but that general-purpose measures and human perceptions were misaligned

4) Analyzed the semantic similarity of abstract words to describe products ("A chair that is *dependable*" or "A chair that is *friendly*) utilizing semantic embeddings from Transformer models

5) Discovered, through image classification, that semantic similarity of the above prompts were reflected visually in the products (decreased semantic similarity was associated with increased ability for a machine to distinguish the images perceptually)

