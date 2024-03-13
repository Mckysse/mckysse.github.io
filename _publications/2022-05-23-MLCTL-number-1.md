---
title: "Multi-Level Contrastive Learning for Cross-Lingual Alignment"
collection: publications
permalink: /publication/2022-05-23-MLCTL-number-1
excerpt: 'Cross-language pre-trained models such as multilingual BERT (mBERT) have achieved significant performance in various cross-lingual downstream NLP tasks. This paper proposes a multi-level contrastive learning (ML-CTL) framework to further improve the cross-lingual ability of pre-trained models. The proposed method uses translated parallel data to encourage the model to generate similar semantic embeddings for different languages. However, unlike the sentence-level alignment used in most previous studies, in this paper, we explicitly integrate the word-level information of each pair of parallel sentences into contrastive learning. Moreover, cross-zero noise contrastive estimation (CZ-NCE) loss is proposed to alleviate the impact of the floating-point error in the training process with a small batch size. The proposed method significantly improves the cross-lingual transfer ability of our basic model (mBERT) and outperforms on multiple zero-shot cross-lingual downstream tasks compared to the same-size models in the Xtreme benchmark.'
date: 2022-05-23
venue: '2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP 2022)'
paperurl: 'https://ieeexplore.ieee.org/document/9747720'
citation: 'B. Chen, W. Guo, B. Gu, Q. Liu and Y. Wang, "Multi-Level Contrastive Learning for Cross-Lingual Alignment," ICASSP 2022 - 2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Singapore, Singapore, 2022, pp. 7947-7951, doi: 10.1109/ICASSP43922.2022.9747720. keywords: {Training;Conferences;Semantics;Bit error rate;Estimation;Benchmark testing;Signal processing;Cross-language pre-trained model;contrastive learning;multi-level;cross-zero NCE;cross-lingual alignment},'
---


## Abstract
Cross-language pre-trained models such as multilingual BERT (mBERT) have achieved significant performance in various cross-lingual downstream NLP tasks. This paper proposes a multi-level contrastive learning (ML-CTL) framework to further improve the cross-lingual ability of pre-trained models. The proposed method uses translated parallel data to encourage the model to generate similar semantic embeddings for different languages. However, unlike the sentence-level alignment used in most previous studies, in this paper, we explicitly integrate the word-level information of each pair of parallel sentences into contrastive learning. Moreover, cross-zero noise contrastive estimation (CZ-NCE) loss is proposed to alleviate the impact of the floating-point error in the training process with a small batch size. The proposed method significantly improves the cross-lingual transfer ability of our basic model (mBERT) and outperforms on multiple zero-shot cross-lingual downstream tasks compared to the same-size models in the Xtreme benchmark.

## Overall Structure
![Image text](files/ICASSP2022_ML-CTL_Struct.pdf)

## Related Resources
[[Poster]](files/ICASSP2022_ML-CTL_poster.pdf)   [[Slides]](files/ICASSP2022_ML-CTL_slides.pdf)  [[arxiv]](https://arxiv.org/pdf/2202.13083.pdf)   [[Code]](https://github.com/Mckysse/ML-CTL)  


