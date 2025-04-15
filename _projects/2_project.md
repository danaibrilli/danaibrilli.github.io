---
layout: page
title: Early Alzheimer's Detection
description:
img: #assets/img/3.jpg
importance: 1
category: research
giscus_comments: false
---

To deepen my background in medical imaging, I decided to apply for IEEE Student Mentoring Program 2024 and managed to get selected and partnered up with Dr. Priya E from Sri Sai Ram Engineering College. Together we decided to tackle early Alzheimer's detection using deep learning segmentation of hippocampal region. 

Deteccing Alzheimers at an early stage, even before the appearance of significant symptoms can enable timely interventions that can delay the disease progression and improve patients' quality of life. The hippocampus, a critical brain region responsible for memory and learning is one of the first areas affected by Alzheimer. Therefore, accurately identifying changes in the hippocampus is essential for diagnosing early Alzheimer's. 

The first step of our methodology is to identify the prominent slice, which is one that contains the hippocampus. To do that we leverage multifractal analysis on saggital views. We then use a foundation model, SAM,  to segment the hippocampal region and then a Visual Transformer to extract visual embeddings that provide a high-level representation of the hippocampus. Finally, the embeddings are passed through an ensemble classification model. In summary, by combining multi-fractal analysis, foundation models and advanced classification techniques, we are able to achieve a robust method for early Alzheimer's detection. 


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/alzheimer_methodology.jpg" title="Methodology early Alzheimer's" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Our methodology for early Alzheimer's detection combining multi-fractal analysis and foundation models.
</div>

The work is currently in progress - wrapping up for a publication.