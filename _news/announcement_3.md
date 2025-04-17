---
layout: post
title: Our paper was accepted to PLOS Genetics.
date: 2025-03-19 16:00:00+0900
inline: false
related_posts: false
---

Our paper "<a href="https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1011420">Mouse-Geneformer: A deep learning model for mouse single-cell transcriptome and its cross-species utility</a>" was accepted to <a href="https://journals.plos.org/plosgenetics/">PLOS Genetics</a>.

***

### Mouse-Geneformer: A deep learning model for mouse single-cell transcriptome and its cross-species utility

*Keita Ito・Tsubasa Hirakawa・Shuji Shigenobu・Hironobu Fujiyoshi・Takayoshi Yamashita*

PLOS Genetics, 2025

#### Abstract

Deep learning techniques are increasingly utilized to analyze large-scale single-cell RNA sequencing (scRNA-seq) data, offering valuable insights from complex transcriptome datasets. Geneformer, a pre-trained model using a Transformer Encoder architecture and human scRNA-seq datasets, has demonstrated remarkable success in human transcriptome analysis. However, given the prominence of the mouse, Mus musculus, as a primary mammalian model in biological and medical research, there is an acute need for a mouse-specific version of Geneformer. In this study, we developed a mouse-specific Geneformer (mouse-Geneformer) by constructing a large transcriptome dataset consisting of 21 million mouse scRNA-seq profiles and pre-training Geneformer on this dataset. The mouse-Geneformer effectively models the mouse transcriptome and, upon fine-tuning for downstream tasks, enhances the accuracy of cell type classification. In silico perturbation experiments using mouse-Geneformer successfully identified disease-causing genes that have been validated in in vivo experiments. These results demonstrate the feasibility of analyzing mouse data with mouse-Geneformer and highlight the robustness of the Geneformer architecture, applicable to any species with large-scale transcriptome data available. Furthermore, we found that mouse-Geneformer can analyze human transcriptome data in a cross-species manner. After the ortholog-based gene name conversion, the analysis of human scRNA-seq data using mouse-Geneformer, followed by fine-tuning with human data, achieved cell type classification accuracy comparable to that obtained using the original human Geneformer. In in silico simulation experiments using human disease models, we obtained results similar to human-Geneformer for the myocardial infarction model but only partially consistent results for the COVID-19 model, a trait unique to humans (laboratory mice are not susceptible to SARS-CoV-2). These findings suggest the potential for cross-species application of the Geneformer model while emphasizing the importance of species-specific models for capturing the full complexity of disease mechanisms. Despite the existence of the original Geneformer tailored for humans, human research could benefit from mouse-Geneformer due to its inclusion of samples that are ethically or technically inaccessible for humans, such as embryonic tissues and certain disease models. Additionally, this cross-species approach indicates potential use for non-model organisms, where obtaining large-scale single-cell transcriptome data is challenging.
