---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

![Mohamed Profile Photo](https://mgunady.github.io/mgunady/images/photo_hike.jpg)
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

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
