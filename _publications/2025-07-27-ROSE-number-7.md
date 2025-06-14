---
title: "A Rose by Any Other Name: LLM-Generated Explanations Are Good Proxies for Human Explanations to Collect Label Distributions on NLI"
collection: publications
permalink: /publication/2025-07-27-ROSE-number-7
excerpt: "This paper investigates whether large language models (LLMs) can generate explanations that effectively approximate human judgment distributions (HJDs) in natural language inference (NLI). By replacing human-written explanations with LLM-generated ones for a small set of human labels, the study finds that model explanations can match human performance in estimating HJDs, even on datasets lacking human explanations and in out-of-distribution settings."
date: 2025-07-27
venue: 'Findings of the Association for Computational Linguistics: ACL 2025'
paperurl: 'https://arxiv.org/abs/2412.13942'
citation: 'Beiduo Chen, Siyao Peng, Anna Korhonen, Barbara Plank. 2025. A Rose by Any Other Name: LLM-Generated Explanations Are Good Proxies for Human Explanations to Collect Label Distributions on NLI. In Findings of the Association for Computational Linguistics: ACL 2025, Vienna, Austria. Association for Computational Linguistics.'
---

## [Code](https://github.com/mainlp/MJD-Estimator/)

## Abstract
Disagreement in human labeling is ubiquitous, and can be captured in human judgment distributions (HJDs). Recent research has shown that explanations provide valuable information for understanding human label variation (HLV) and large language models (LLMs) can approximate HJD from a few human-provided label-explanation pairs. However, collecting explanations for every label is still time-consuming. This paper examines whether LLMs can be used to replace humans in generating explanations for approximating HJD. Specifically, we use LLMs as annotators to generate model explanations for a few given human labels. We test ways to obtain and combine these label-explanations with the goal to approximate human judgment distributions. We further compare the resulting human with model-generated explanations, and test automatic and human explanation selection. Our experiments show that LLM explanations are promising for NLI: to estimate HJDs, generated explanations yield comparable results to human's when provided with human labels. Importantly, our results generalize from datasets with human explanations to i. datasets where they are not available and ii. challenging out-of-distribution test sets.

## [Poster](https://mckysse.github.io/files/ACL2025_ROSE_poster.pdf)
<object data="https://mckysse.github.io/files/ACL2025_ROSE_poster.pdf" type="application/pdf" width="900px" height="900px">
    <embed src="https://mckysse.github.io/files/ACL2025_ROSE_poster.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://mckysse.github.io/files/ACL2025_ROSE_poster.pdf">Download PDF</a>.</p>
    </embed>
</object>


## [Arxiv](https://arxiv.org/pdf/2412.13942)
<object data="https://arxiv.org/pdf/2412.13942" type="application/pdf" width="900px" height="900px">
    <embed src="https://arxiv.org/pdf/2412.13942">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://arxiv.org/pdf/2412.13942">Download PDF</a>.</p>
    </embed>
</object>


## [Slides](https://mckysse.github.io/files/ACL2025_ROSE_slides.pdf)
<object data="https://mckysse.github.io/files/ACL2025_ROSE_slides.pdf" type="application/pdf" width="900px" height="900px">
    <embed src="https://mckysse.github.io/files/ACL2025_ROSE_slides.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://mckysse.github.io/files/ACL2025_ROSE_slides.pdf">Download PDF</a>.</p>
    </embed>
</object>

## Citation
