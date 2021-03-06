---
title: Session 4 (6th May 2020)
date: "2020-05-06T16:00:00Z"
layout: post
draft: false
path: "/posts/session-4"
category: "Session Schedule"
tags:
  - "Bioinformatics software and protocols"
  - "Microbial ecology and evolution"
description: "With talks from Leonardo de Oliveira Martins, Inês Mendes and Rebecca Ansorge"
---

# Schedule 

Time: 16:00 6 May 2020 (UTC) 

Zoom link: Coming soon.

Discord link: https://discord.gg/WmuRbD

* 15:00 **From phylogenetics to phylogenomics: between bacterial strains and the tree of life**  
  Leonardo de Oliveira Martins  (Quadram Institute Bioscience)  
* 15:30 **DEN-IM: dengue virus genotyping from amplicon and shotgun metagenomic sequencing**  
  Inês Mendes (Instituto de Medicina Molecular)
* 16:00 **Same same but different: Functional diversity despite identical 16S rRNA sequences**  
  Rebecca Ansorge (Quadram Institute Bioscience)   
* 16:20 **Virtual coffee break**

## From phylogenetics to phylogenomics: between bacterial strains and the tree of life
With the amount and velocity of genomic data currently available, it became clear that no single gene, or even carefully selected gene sets, can provide a single evolutionary tree with confidence. We can therefore appreciate that apparently conflicting phylogenetic signals are not noise, but in fact reflect real biological phenomena ―  like duplications, lateral transfer, or ancestral polymorphisms. Phylogenomic models explicitly recognise this variation in evolutionary histories across the genome, allowing us to make most use of sequenced genomes. In this talk we will have an overview of popular models, as well as of emerging methodologies that can handle whole genomes from hundreds or thousands of samples.  We will also discuss favourite approaches in different fields, where the genomic sets may resemble closer a “tall” (fewer information from many samples) or a “wide” (fewer samples, with more information) data category.

https://leomrtns.github.io

## DEN-IM: dengue virus genotyping from amplicon and shotgun metagenomic sequencing
Dengue virus (DENV) represents a public health threat and economic burden in affected countries. The availability of genomic data is key to understanding viral evolution and dynamics, supporting improved control strategies. Currently, the use of high-throughput sequencing (HTS) technologies, which can be applied both directly to patient samples (shotgun metagenomics) and to PCR-amplified viral sequences (amplicon sequencing), is potentially the most informative approach to monitor viral dissemination and genetic diversity by providing, in a single methodological step, identification and characterization of the whole viral genome at the nucleotide level. Despite many advantages, these technologies require bioinformatics expertise and appropriate infrastructure for the analysis and interpretation of the resulting data. In addition, the many software solutions available can hamper the reproducibility and comparison of results. Here we present DEN-IM, a one-stop, user-friendly, containerized and reproducible workflow for the analysis of DENV short-read sequencing data from both amplicon and shotgun metagenomics approaches. It is able to infer the DENV coding sequence (CDS), identify the serotype and genotype, and generate a phylogenetic tree. It can easily be run on any UNIX-like system, from local machines to high-performance computing clusters, performing a comprehensive analysis without the requirement for extensive bioinformatics expertise. Using DEN-IM, we successfully analysed two types of DENV datasets. The first comprised 25 shotgun metagenomic sequencing samples from patients with variable serotypes and genotypes, including an in vitro spiked sample containing the four known serotypes. The second consisted of 106 paired-end and 76 single-end amplicon sequences of DENV 3 genotype III and DENV 1 genotype I, respectively, where DEN-IM allowed detection of the intra-genotype diversity. The DEN-IM workflow, parameters and execution configuration files, and documentation are freely available at https://github.com/B-UMMI/DEN-IM).

### About the speaker
Inês Mendes is currently a PhD student at Instituto de Medicina Molecular and University Medical Center Groningen. 
Her formal education started, in 2011, in Cellular and Molecular Biology, in Faculdade de Ciências e Tecnologia - Universidade Nova de Lisboa, followed by a Master degree in 2014 in Bioinformatics and Computational Biology in Faculdade de Ciências - Universidade de Lisboa. Inês joined the Instituto de Medicina Molecular, at the Mário Ramirez Lab as a master student in 2015 where she used a variety of open source tools, and developed her own scripts, in Python, for the analysis of Streptococcus dysgalactiae genomes recovered from different sources (both human and animal). Since then, she remained a member of the MRamirez Lab as a Bioinformatician where I developed and maintain in house tools and scripts and perform various analysis using a variety of open source tools.

In 2018 Inês began a PhD in Bioinformatics, in collaboration with University Medical Center Groningen, focused on metagenomics, validation and reproducibility, specially relevant when analyzing clinical data. Her work is supervised by Dr. João André Carriço and Prof. Dr. Mário Ramirez, from University of Lisbon, and Prof. Dr. John W A Rossen, from University of Groningen.

## Same same but different: Functional diversity despite identical 16S rRNA sequences
The 16S rRNA sequence is commonly considered a gold standard to determine the diversity in microbial communities. But how much diversity do we miss when we stop there? We investigated a low-diversity symbiosis between deep-sea bivalves and their bacterial symbionts using their metagenomic information. Despite identical 16S sequences we found as many as 16 intracellular symbiont strains to co-exist in single host individuals. We used nucleotide polymorphism and read coverage information to tease apart strain-level differences within symbiont populations. This approach revealed extensive differences in the gene content of these strains, that are otherwise unaccessible from the MAGs. 