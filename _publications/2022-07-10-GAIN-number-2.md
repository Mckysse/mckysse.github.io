---
title: "USTC-NELSLIP at SemEval-2022 Task 11: Gazetteer-Adapted Integration Network for Multilingual Complex Named Entity Recognition"
collection: publications
permalink: /publication/2022-07-10-GAIN-number-2
excerpt: 'This paper presents GAIN, a gazetteer-adapted integration network for enhancing multilingual complex NER by aligning gazetteer and language model representations via KL divergence minimization and integrating them during training. Applied to various Transformer-based models with a Wikidata-based gazetteer, GAIN achieves strong generalization and ranks 1st or 2nd across all tracks in SemEval-2022 Task 11.'
date: 2022-07-10
venue: 'Proceedings of the 16th International Workshop on Semantic Evaluation (SemEval-2022)'
paperurl: 'https://aclanthology.org/2022.semeval-1.223/'
citation: 'Beiduo Chen, Jun-Yu Ma, Jiajun Qi, Wu Guo, Zhen-Hua Ling, and Quan Liu. 2022. USTC-NELSLIP at SemEval-2022 Task 11: Gazetteer-Adapted Integration Network for Multilingual Complex Named Entity Recognition. In Proceedings of the 16th International Workshop on Semantic Evaluation (SemEval-2022), pages 1613–1622, Seattle, United States. Association for Computational Linguistics.'
---

## [Code](https://github.com/Mckysse/GAIN)

## Abstract
This paper describes the system developed by the USTC-NELSLIP team for SemEval-2022 Task 11 Multilingual Complex Named Entity Recognition (MultiCoNER). We propose a gazetteer-adapted integration network (GAIN) to improve the performance of language models for recognizing complex named entities. The method first adapts the representations of gazetteer networks to those of language models by minimizing the KL divergence between them. After adaptation, these two networks are then integrated for backend supervised named entity recognition (NER) training. The proposed method is applied to several state-of-the-art Transformer-based NER models with a gazetteer built from Wikidata, and shows great generalization ability across them. The final predictions are derived from an ensemble of these trained models. Experimental results and detailed analysis verify the effectiveness of the proposed method. The official results show that our system ranked 1st on three tracks (Chinese, Code-mixed and Bangla) and 2nd on the other ten tracks in this task.'


## [Poster](https://mckysse.github.io/files/SemEval2022_GAIN_poster.pdf)
<object data="https://mckysse.github.io/files/SemEval2022_GAIN_poster.pdf" type="application/pdf" width="900px" height="900px">
    <embed src="https://mckysse.github.io/files/SemEval2022_GAIN_poster.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://mckysse.github.io/files/SemEval2022_GAIN_poster.pdf">Download PDF</a>.</p>
    </embed>
</object>


## [Arxiv](https://arxiv.org/pdf/2203.03216)
<object data="https://arxiv.org/pdf/2203.03216" type="application/pdf" width="900px" height="900px">
    <embed src="https://arxiv.org/pdf/2203.03216">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://arxiv.org/pdf/2203.03216">Download PDF</a>.</p>
    </embed>
</object>


## [Slides](https://mckysse.github.io/files/SemEval2022_GAIN_slides.pdf)
<object data="https://mckysse.github.io/files/SemEval2022_GAIN_slides.pdf" type="application/pdf" width="900px" height="900px">
    <embed src="https://mckysse.github.io/files/SemEval2022_GAIN_slides.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://mckysse.github.io/files/SemEval2022_GAIN_slides.pdf">Download PDF</a>.</p>
    </embed>
</object>

## Citation
