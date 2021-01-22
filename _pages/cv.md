---
layout: archive
title: " "
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}<br/>
PDF version is also available [here](https://SaradhaVenkatachalapathy.github.io/files/Saradha_CV.pdf)

## EDUCATION
* B.Tech in Biotechnology(with Distinction), SASTRA University, India, 2015
* Ph.D in Mechanobiology, National University of Singapore, Singapore (2021 Expected)

## WORK EXPERIENCE
* Visiting Researcher, Paul Scherrer Institute & ETH Z ̈urich
* Consultant, Computer Vision, [Qritive](https://www.qritive.com/)
* Research Assistant, NUS  

## SKILLS
* Statistics: Linear algebra,Multivariate analysis,Machine Learning, Clustering,Pattern recognition, Diffusion maps and Psuedotime analysis
* Computer Vision: Segmentation, Feature generation and Particle tracking
* Computational Biology: Next Gen-Sequencing analysis of Microarray, RNA-Seq including single cell RNA-Seq and HiC data       
* Experimental Skills: Microscopy, Tissue engineering and mechanical manipulation of cells

## SELECTED RESEARCH PROJECTS

**Automated feature generator for 3D images**
* Built an automatic image processing pipelines for segmentation and feature generation that reduced the processing time by 60%.
* Engineered features for morphology, textural and spatial distribution of objects in images.
* Integrated multi-domain features such as protein expression, RNA seq and image features to enable deduction of functional links.

**Digital pathology platform for grading breast cancer stages at single cell resolution**
 * Performed instance segmentation of singe nuclei from patient tissue biopsies using U-Net based CNN and extracted geometric and textural features of nuclei.
 * Built machine learning models to diagnose breast cancer stages at single cell resolution from patient breast tissue biopsies with 80\% accuracy.
 * Developed a single cell tumorigenesis score that varies with tumor progression.

**Deconvolving cell variability in cancer**
* Developed a 3D in-vitro tissue model to study cancer progression amenable to high resolution imaging. 
* Implemented a classifier to predict cell shape with an accuracy of 95\% and used the latent feature vectors along with regression models to show that cell shape is coupled to its function. 
* Demonstrated a causal relationship between cell shape and activation by cancer cells using  multimodal-multivariate analysis.
* Established the use of the 3D tissue model to assay the treatment efficacy of radiotherapy.

**Trajectory inference to accelerate reprogramming of skin cells to stem cells**.
* Developed a novel technique to reprogram skin cells to stem cells with high efficiency.
* Performed statistical tests and pathway analysis on RNA seq data to characterize the temporal changes in the transcription profile during reprogramming. 
* Modeled trajectories of reprogramming cells using clustering and diffusion models of single cell image features.
* Identified sources of low efficiency in large noisy image data which were experimentally validated to accelerate stem cell generation.

## CONFERENCE: TALKS AND POSTERS
<ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

## AWARDS AND HONOURS
* Dean’s Merit list of the top 2-10% in the University (2014-2015)
* Inspirational Mentorship Award, NUS High School(2017)  
* Best Oral Presentation Award, International Conference on Genomes and AI (2019)
