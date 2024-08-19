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

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/DesignSim/semanticandvisualsim.PNG" alt = "Figure that shows process of extracting image features and using support vector machine classification with semantic labels" class="img-fluid" height="100%" width="auto" %}
    </div>
</div>

## <u>Key Insights and Impact</u>
#### **1. Product similarity along the functional dimension**
Perceptions of what products are considered functionally similar are complicated by framing, with humans considering similarity at various levels of abstraction. The dynamic nature of humans' structuring of the similarity space makes it particularly challenging to quantify functional similarity using static measures on static product representations, due to misalignment with humans' internal representations. Depending on what is important for the context (e.g., capturing low-level features of the product function vs. a higher-level functional goal), the choice of similarity measure may need to change. Therefore, creativity support systems such as those for analogical reasoning must be flexible in their similarity representations, perhaps adapting measures or quantification based on inference of a user's intent.  

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/DesignSim/analogicalreasoning.PNG" alt = "Figure that shows process of extracting functional analogies using abstract schema and products that are near (e.g., chairs and chairs) vs. far (e.g., chairs and toys)" class="img-fluid" height="100%" width="auto" %}
    </div>
</div>

#### **2. Product similarity along the semantic dimension** 
Semantic representations of products (e.g., product descriptions) contain rich information about product including its function and form. Machine learning (ML) models can encode humans' representations of language, enabling their use for establishing a semantic space of product similarity. When the semantic representation is more abstract, referring to high-level, conceptual descriptions of a product (e.g., *luxurious*, *sporty*), this information is built into humans' internal representations of the key words. While state-of-the-art ML models can capture these more abstract concepts to an extent, they cannot necessarily make the subtle distinctions connecting these concepts to specific classes of products, particularly new types of products, without additional training. Therefore, new methods may need to be developed to utilize semantic similarity for product design (e.g., methods for breaking abstract words down into more concrete and interpretable formats for natural language systems).

#### **3. Product similarity along the visual dimension**
Visual similarity can be captured using image or geometric 3D representations of the products. Products that have relatively similar function may or may not be visually similar. For instance, consider the concept of a "hands-free smart phone," which can be functionally implemented in many ways, including smart glasses (e.g., Google Glass or Ray-Ban Meta Smart Glasses), which will be visually similar to each other, or a visually dissimilar wearable (e.g., Humane AI Pin). With improvements in multi-model AI, it is increasingly possible to use pixel-level representations, but capture semantic (or perhaps functional) meaning. At the same time, it is important to note that in product design, it may be important to capture only visual similarity across far domains (e.g., silhouettes for bio-inspired design) to enable inspiration for a product's form or aesthetic.

**These insights can be applied to the development of creativity support tools, specifically those meant for product design. In particular, this work demonstrates the various dimensions of similarity that need to be considered for design-related cognition and decision making, as well as how they can be operationalized computationally.**
