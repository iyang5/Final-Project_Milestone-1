---
title: "Final Project MILESTONE 1"
author: "Irene Yang"
date: "February 14, 2018"
output: 
pdf: default
html: default
bibliography: N741.bibtex
---

## Tentative Title: *Characterizing the Subgingival Microbiome of Mothers and Babies*
Student: Irene Yang  
Email: irene.yang@emory.edu

### Overview and Motivation
My primary purpose in undertaking this project is to learn how to engage microbiome data. I am motivated by a desire to incorporate the oral microbiome in a program of research focused on improving health outcomes for maternal/newborn dyads. Learning how to work with oral microbiome data is one of the training objectives for my current K01 project investigating the subgingival microbiome and inflammation in Non-Hispanic Black (NHB) Women. My K01 proposal was supported by a pilot project aimed at characterizing the subgingival microbiome of NHB pregnant women and their newborns. The data analysis for the pilot is complete. However, both the sequencing and analysis was outsourced, and I played no direct role in the analysis of the sequence data. I do, however, retain all of the raw sequences that, I propose, be used to attempt a replication of the analysis. This final project provides an ideal learning opportunity that will prepare me to analyze my K01 microbiome data.

### Background
Changes in oral health during pregnancy have been observed for many years. In fact, pregnant women are particularly susceptible to gingivitis due to the hormonal shifts that contribute to inflammation and decreased immunocompetence. Gingivitis is the most common oral disease in pregnancy with a prevlance of 50-70% [@aaccaa15]. In 1996, Offenbacher et al [-@okf96]. reported that periodontal disease carried a seven-fold increase in the risk of preterm birth. Since then several other studies have found an association with preterm birth [@gja04;@mrm14]. Although individual pathogens, like *Porphyromonas gingivalis*, *Treponema denticola*, and *Tannerella forsythia*, have been associated with periodontal infection and inflammation [@hg05], evidence implicating these organisms in pregnant women has been inconsistent. This may be due to older methodologies which targeted only specific periopathogens and were not powerful enough to identify the hundreds of other bacterial species in the oral cavity [@dci10]. Additionally, newer oral microbiome research utilizing powerful 16S rRNA sequencing in non-pregnant populations suggests that our understanding of infection/inflammation must move from a focus on individual pathogens to the ecological context of a particular microbial community, and that a state of periodontal inflammation may represent a shift in the overall ecological balance of microbial flora rather than the appearance of individual pathogens. 

There is also evidence that the maternal oral microbiome may be associated with adverse child oral health outcomes [@cgwf14]. Preliminary studies suggest that a woman's oral microbiota may be shared with her child [@pjn10]. Although the mechanism for this transmission is not known, possible transmission routes include kissing and sharing or pre-chewing food [@pzp10]. Consequences include pediatric dental decay, which while treatable, may have a systemic physiologic, psychosocial, and economic impact on children and their families.

This background serves as context describing the scientific premise for exploring the maternal child oral microbiome. No study to date has used 16S rRNA sequencing to characterize the subgingival microbiome of pregnant mothers and the oral microbiome of their newborns.

### Primary Objective
My objective is to be able to replicate the microbiome analysis output that was provided to me for my pilot study. This includes addressing the following descriptive aims:  

1. Characterize the oral microbiome in periodontal health and disease in a population of at risk African American pregnant women.  
2. Characterize the oral microbiome of the infants of these mothers.

I believe that carrying out the analysis to achieve these two aims will give me the hands-on practice I need in microbiome data workflow and analysis.

### Data
The fastq and metadata files have been loaded to my github repository. I believe these are the two main sources of data that I will need for this project.

### Data Wrangling
Data wrangling for the fastq data will involve demultiplexing and sequence quality control. I plan to use the qiime2 (forked to my repository) pipeline which provides instructions on how to demultiplex and two different plug-in options for sequence quality control.

### Exploratory Analysis
Exploratory analysis will continue as I work through the qiime2 pipeline which includes:

1. Creation of FeatureTable and FeatureData summaries
2. Alpha diversity analysis - visualized as box plots 
3. Beta diversity analysis - visualized as PCoA plots
4. Taxonomic analysis - visualized as bar plots (hopefully interactive!)
5. Differential abundance testing between sample groups - the qiime2 pipeline uses ancom analysis (analysis of composition of microbiomes) visualized with Emperor plots.

I am interested to see if the results I find through my analysis with the qiime2 pipeline will differ from those that were provided to me. I suspect they will - if only slightly - since the since the original analysis was conducted using the mothur software package. 

### The Plan

Weekly Goal   Task
------------  ------
By 2/21       Install qiime2
By 3/7        Complete demultiplexing and sequence quality control steps
By 3/14       Complete FeatureTable and FeatureData summaries
By 3/21       Complete Alpha and Beta diversity analyses
By 3/28       Milestone 2 Assignment
By 4/7        Complete Taxonomic analysis
By 4/14       Differential abundance testing between sample groups
By 4/21       Trouble shoot analyses
By 4/28       Write the manuscript and prepare presentation
By 5/2        Final Project due

# References



