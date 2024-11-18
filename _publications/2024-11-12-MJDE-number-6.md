---
title: "“Seeing the Big through the Small”: Can LLMs Approximate Human Judgment Distributions on NLI from a Few Explanations?"
collection: publications
permalink: /publication/2024-11-12-MJDE-number-6
excerpt: 'Human label variation (HLV) is a valuable source of information that arises when multiple human annotators provide different labels for valid reasons. In Natural Language Inference (NLI) earlier approaches to capturing HLV involve either collecting annotations from many crowd workers to represent human judgment distribution (HJD) or use expert linguists to provide detailed explanations for their chosen labels. While the former method provides denser HJD information, obtaining it is resource-intensive. In contrast, the latter offers richer textual information but it is challenging to scale up to many human judges. Besides, large language models (LLMs) are increasingly used as evaluators (“LLM judges”) but with mixed results, and few works aim to study HJDs. This study proposes to exploit LLMs to approximate HJDs using a small number of expert labels and explanations. Our experiments show that a few explanations significantly improve LLMs’ ability to approximate HJDs with and without explicit labels, thereby providing a solution to scale up annotations for HJD. However, fine-tuning smaller soft-label aware models with the LLM-generated model judgment distributions (MJDs) presents partially inconsistent results: while similar in distance, their resulting fine-tuned models and visualized distributions differ substantially. We show the importance of complementing instance-level distance measures with a global-level shape metric and visualization to more effectively evaluate MJDs against human judgment distributions.'
date: 2024-11-12
venue: 'Findings of the Association for Computational Linguistics: EMNLP 2024'
paperurl: 'https://aclanthology.org/2024.findings-emnlp.842/'
citation: 'Beiduo Chen, Xinpeng Wang, Siyao Peng, Robert Litschko, Anna Korhonen, and Barbara Plank. 2024. “Seeing the Big through the Small”: Can LLMs Approximate Human Judgment Distributions on NLI from a Few Explanations?. In Findings of the Association for Computational Linguistics: EMNLP 2024, pages 14396–14419, Miami, Florida, USA. Association for Computational Linguistics.'
---

## [Code](https://github.com/mainlp/MJD-Estimator/)

## Abstract
Human label variation (HLV) is a valuable source of information that arises when multiple human annotators provide different labels for valid reasons. In Natural Language Inference (NLI) earlier approaches to capturing HLV involve either collecting annotations from many crowd workers to represent human judgment distribution (HJD) or use expert linguists to provide detailed explanations for their chosen labels. While the former method provides denser HJD information, obtaining it is resource-intensive. In contrast, the latter offers richer textual information but it is challenging to scale up to many human judges. Besides, large language models (LLMs) are increasingly used as evaluators (“LLM judges”) but with mixed results, and few works aim to study HJDs. This study proposes to exploit LLMs to approximate HJDs using a small number of expert labels and explanations. Our experiments show that a few explanations significantly improve LLMs’ ability to approximate HJDs with and without explicit labels, thereby providing a solution to scale up annotations for HJD. However, fine-tuning smaller soft-label aware models with the LLM-generated model judgment distributions (MJDs) presents partially inconsistent results: while similar in distance, their resulting fine-tuned models and visualized distributions differ substantially. We show the importance of complementing instance-level distance measures with a global-level shape metric and visualization to more effectively evaluate MJDs against human judgment distributions.

## [Poster](https://github.com/Mckysse/mckysse.github.io/blob/master/files/EMNLP2024_MJDE_poster.pdf)
<object data="https://mckysse.github.io/files/EMNLP2024_MJDE_poster.pdf" type="application/pdf" width="900px" height="900px">
    <embed src="https://mckysse.github.io/files/EMNLP2024_MJDE_poster.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://mckysse.github.io/files/EMNLP2024_MJDE_poster.pdf">Download PDF</a>.</p>
    </embed>
</object>


## [Arxiv](https://arxiv.org/pdf/2406.17600)
<object data="https://arxiv.org/pdf/2406.17600" type="application/pdf" width="900px" height="900px">
    <embed src="https://arxiv.org/pdf/2406.17600">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://arxiv.org/pdf/2406.17600">Download PDF</a>.</p>
    </embed>
</object>


## [Slides](https://mckysse.github.io/files/EMNLP2024_MJDE_slides.pdf)
<object data="https://mckysse.github.io/files/EMNLP2024_MJDE_slides.pdf" type="application/pdf" width="900px" height="900px">
    <embed src="https://mckysse.github.io/files/EMNLP2024_MJDE_slides.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://mckysse.github.io/files/EMNLP2024_MJDE_slides.pdf">Download PDF</a>.</p>
    </embed>
</object>

## Citation
