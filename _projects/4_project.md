---
layout: page
title: Glioblastoma Pseudoprogression Detection
description:
img: 
importance: 1
category: research
---

To deepen my skills in biomedical imaging I am currently working as a researcher in Prof. Davatzikos' lab at the University of Pennsylvania. My work leverages generative machine learning for analyzing brain mpMRI data aiming to distinguish true glioblastoma recurrence from pseudo-progression.


After studying relevant literature, I realized that tumor pseudo-progression is a very under-documented setting, with very few confirmed cases, as compared to tumor recurrence cases. Thus, I reformulated the question of classifying suspicious lesions as glioblastoma recurrence or pseudo-progression (discriminative modeling) into learning the distribution of true recurrence (generative modeling). This way, I can identify pseudo-progression cases as the outliers of the data distribution.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/glioblastoma_method.jpg" title="AIris Methodology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Our methodology for glioblastoma pseudoprogression detection, leveraging generative AI to model the true progression cases' distribution and detect pseudoprogression as outliers.
</div>

This work is currently in progress.