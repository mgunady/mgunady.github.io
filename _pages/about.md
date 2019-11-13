---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

![Mohamed Profile Photo](https://mgunady.github.io/images/photo_hike.png)
- I'm a PhD student in the [Computer Science Department](https://www.cs.umd.edu/) at [University of Maryland](https://umd.edu/), advised by [Héctor Corrada Bravo](http://www.hcbravo.org/). [[Curriculum Vitae](https://mgunady.github.io/files/Gunady_resume.pdf)]
- My research interests lie mainly in Bioinformatics, Genomics, Machine Learning and Data Science. 
In addition to interests more generally in developing solutions in Articifial Intelligence, Data Structures and Multi-Agent Systems.
- I received my Master's Degree in [Egypt-Japan University of Science and Technology](https://ejust.edu.eg/), advised by [Walid Gomaa](https://scholar.google.com/citations?user=tZ1q2UUAAAAJ&hl=en), [Ikuo Takeuchi](https://dblp.org/pers/hd/t/Takeuchi:Ikuo), and [Amin Shoukry](https://scholar.google.com/citations?user=z10Zl1kAAAAJ&hl=en)
- I received my Bachelor's Degree in [University of Alexandria, Egypt](http://www.alexu.edu.eg/index.php/en/).


Research Statement
======
During my PhD, I got the chance to work on a variety of research projects that enabled me to strengthen my skills and broaden my background in bioinformatics, genomics, data science and machine learning.
- For instance on the area of RNAseq, I've worked for some time on developing our tool Yanagi, a graph-based approach to enable the use of ultra-fast lightweight kmer-based alignment techniques to perform fast and interpretable downstream analysis from RNAseq data in alternative splicing, transcriptome, as well as genome level. The main idea is to reduce the transcriptome into an efficient set of L-disjoint segments representing the splice graph in order to provide count statistics describing the local structure of the transcriptome and minimizing the degrees of ambiguity introduced by multi-mapped reads, hence decoupling the two tasks of alignment and quantification, which we showed to be beneficial in different downstream analyses like differential alternative splicing. One extension for that project we are currently working on is to use our framework for a better model for transcripts quantification and unannotated junction discovery in case of incomplete annotation. (Python, C++, R/Bioconductor)
- On another direction, yet related to the work introduced in yanagi, I explored the adaptation of our graph-based approach, introduced for RNAseq, into building a whole genome population reference for WGS. Through that work, we showed that we can bridge the gap between linear and graph-based alignment techniques to efficiently represent a population of alleles database of highly polymorphic genomic regions (e.g. HLA genes) without the need to build a graph-based alignment which usually are heavyweight and several folds slower than linear aligners. (Python, Shell scripts)
- Another recent project I have been working on that is more ML oriented is the use of generative adversarial networks (GANs) for imputing single-cell RNAseq data (submitted to RECOMB 2020). Recent advances on scRNAseq technologies opened the door for a rich view into the heterogeneity underlying a cell population. However single-cell data are usually noisy and very sparse due to the presence of dropout genes. In this work we proposed an approach to impute missing gene expressions in single cell data using generative adversarial networks. By learning an approximate distribution of the data, our approach, scGAIN, can impute dropouts in simulated and real single cell data. we explored how to adopt an imputation model designed originally for images in the domain of computer vision into the domain of imputing single cell data which has its own challenges making that transfer in domain not straightforward. (Python, tensorflow, R/Bioconductor)

Those projects, among other collaborations, show my background and skill set I've built through my PhD journey and I aspire to find an exciting opportunity to apply and further extend my background and skills into solving real-life problems that impact our quality of life.
