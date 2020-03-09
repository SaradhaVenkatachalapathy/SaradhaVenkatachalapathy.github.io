---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Tech in Biotechnology(with Distinction), SASTRA University, India, 2015
* Ph.D in Mechanobiology, National University of Singapore, 2020 (expected)

Skills
======
* Staitictics: Linear algebra,Multivariate analysis,Machine Learning, Clustering,Pattern recognition, Diffusion maps and Psuedotime analysis
* Computer Vision: Segmentation, Feature generation and Particle tracking
* Computational Biology: Next Gen-Sequencing analysis of Microarray, RNA-Seq and HiC data       
* Experimental Skills: Microscopy, Tissue engineering and mechanical manipulation of cells

Selected Projects
======
**Automated feature generator for 3D images**
* Built an in-house automatic image processing pipeline for segmentation and feature generation.
* Developed novel parameters that measure morphology, textural and spatial distribution of objects.
* Integrated multi-domain features such as protein expression, RNA seq and image features for deducing functional links. 
* These algorithms reduced the processing time from 1 week to 12 hours.

**Deconvolving cell variability in cancer**
* Only a subset of cells are activated by cancer signals in engineered breast cancer tissue.
* Developed a linear classifier to predict cell shape with an accuracy of 95%.
* Established the existence of activation primed cell shapes using multimodal-multivariate analysis.
* Demonstrated a causal relationship between cell geometry and activation [MBoC,2020].

**Time series analysis of reprogramming: Trajectory inference**.
* Aligned, analyzed and visualized the transcriptome during mechanically induced de-differentiation. Performed statistical tests and pathway analysis to characterize the temporal changes in the transcription profile and infer the biological relevance [PNAS,2018]. 
* Implemented pseudotemporal ordering of single cell data to identify variable trajectories during the generation of stem cells. 

**DNA structure informs its function**
* Predicted DNA structure from integrating RNA-Seq and ChIP-Seq data and validated the robustness using experiments and HiC data [PNAS,2017].
* Identified latent immune cells based on image based DNA structures and clustering large single cell RNA-Seq dataset [bioRxiv, 2019].

**Cell shape modulates cellular response to stimuli**	
* Aligned, analyzed, visualized and interpreted differential gene expression patterns in RNA-Seq and microarray data. Also performed statistical tests and pathway analysis. 
* Demonstrated the cell shape can modulate the transcriptional response to compressive load and inflammation [PNAS, 2017][MBoC, 2018].

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
