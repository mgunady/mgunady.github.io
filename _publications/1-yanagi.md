---
title: "Yanagi: Fast and interpretable segment-based alternative splicing and gene expression analysis"
collection: publications
permalink: /publication/Yanagi
excerpt: ''
date: 2019-08-13
venue: 'BMC Bioinformatics'
paperurl: 'https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-2947-6'
citation: 'Gunady, M.K., Mount, S.M. & Corrada Bravo, H. Yanagi: Fast and interpretable segment-based alternative splicing and gene expression analysis. BMC Bioinformatics 20, 421 (2019) doi:10.1186/s12859-019-2947-6'
---

- Background

Ultra-fast pseudo-alignment approaches are the tool of choice in transcript-level RNA sequencing (RNA-seq) analyses. Unfortunately, these methods couple the tasks of pseudo-alignment and transcript quantification. This coupling precludes the direct usage of pseudo-alignment to other expression analyses, including alternative splicing or differential gene expression analysis, without including a non-essential transcript quantification step.

- Results

In this paper, we introduce a transcriptome segmentation approach to decouple these two tasks. We propose an efficient algorithm to generate maximal disjoint segments given a transcriptome reference library on which ultra-fast pseudo-alignment can be used to produce per-sample segment counts. We show how to apply these maximally unambiguous count statistics in two specific expression analyses – alternative splicing and gene differential expression – without the need of a transcript quantification step. Our experiments based on simulated and experimental data showed that the use of segment counts, like other methods that rely on local coverage statistics, provides an advantage over approaches that rely on transcript quantification in detecting and correctly estimating local splicing in the case of incomplete transcript annotations.

- Conclusions

The transcriptome segmentation approach implemented in Yanagi exploits the computational and space efficiency of pseudo-alignment approaches. It significantly expands their applicability and interpretability in a variety of RNA-seq analyses by providing the means to model and capture local coverage variation in these analyses.