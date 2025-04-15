---
layout: page
title: "Diploma Thesis: GHR-VQA"
description: with background image
img: assets/img/thesis_method.png
importance: 1
category: research
related_publications: true
---
**GHR-VQA: Graph-guided Hierarchical Relational Reasoning for Video Question Answering**

For my diploma thesis, I worked on Video Question Answering, under the co-supervision of Prof. Maragos (NTUA) and Dr. Pitsikalis (Deeplab).

After extensive literature review, I discovered the need for more lightweight representations of semantic information, so I transformed videos into spatio-temporal scene graphs, as a more structured, compact, and comprehensive representation. By encoding these representations into embeddings with Graph Neural Networks, we create rich and compact representations for each video that are passed through a hierarchical conditional relation network to answer video-based questions. 

Our approach increases accuracy scores across benchmarks and produces more semantically reasonable results compared to state-of-the-art methods.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/thesis_method.png" title="GHR-VQA Methodology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Our proposed architecture: The process begins with the input of a question and a corresponding video. Initially, we perform clip selection and pass the segments through an SGG model to extract scene graphs that represent the visual elements and their interrelationships. These extracted scene graphs are processed by a GNN, which generates meaningful embeddings. The embeddings are then fed into a hierarchical network, which integrates and contextualizes the information across different levels of abstraction to generate a comprehensive understanding in relation to the query and finally answer the question.
</div>

This work was submitted to the 33rd European Signal Processing Conference (EUSIPCO 2025) and the pre-print can be found [here][{{ '/assets/pdf/Brilli_GHR-VQA_final.pdf' | relative_url }}]