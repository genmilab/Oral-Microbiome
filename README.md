# Oral-Microbiome

Microbiome Project in Our Team

## Project Roadmap

This repository documents our oral microbiome research roadmap.

### Project 1 - Population-scale Characterization of the Oral Microbiome and Associations with Metabolic Health

> Our **first project** focuses on building a population-scale, multi-layer map connecting the oral microbiome to host metabolic health.

Code to reproduce the analyses in **“Population-scale Characterization of the Oral Microbiome and Associations with Metabolic Health”**.

#### Project 1 at a glance
- **Cohort scale:** 9,431 participants from the Human Phenotype Project (HPP)
- **Multi-system phenotyping:** 44 metabolic phenotypes spanning **liver ultrasound**, **continuous glucose monitoring (CGM)**, and **DXA-based body composition**
- **Multi-layer oral microbiome profiling:** strain, gene family, and pathway levels
- **Main output:** a population-scale oral-microbiome-to-metabolism association atlas

#### Why this project matters
This first project establishes the foundation of our oral microbiome research line. Instead of studying a single disease or using only low-resolution profiling, we analyze oral whole-metagenome data together with deep metabolic phenotyping to identify system-specific and cross-phenotype microbial signals.

#### Our Contributions
1. **Population-scale, high-resolution metagenomics with deep metabolic phenotyping**  
   We profile standardized bilateral buccal-swab whole-metagenome data in 9,431 HPP adults, paired with 44 metabolic measures spanning liver ultrasound, CGM, and DXA.

2. **A unified, rigorous multi-layer MWAS framework**  
   We systematically test associations across strain, gene-family, and pathway layers using covariate-adjusted regression and layer-wise multiple-testing control.

3. **Actionable outputs with translational and external support**  
   We deliver a multi-system oral-metabolic association atlas, prioritize cross-phenotype markers, demonstrate proof-of-concept metabolic disease classification, and validate key signals in an independent cohort.

#### Key findings
- We identified significant associations for **213 strains**, **124,603 gene families**, and **299 pathways**.
- Strain-level signals were especially enriched for **body composition** phenotypes.
- Functional signals at the gene-family and pathway levels were especially enriched for **CGM-derived glucose phenotypes**.
- Phenotype-selected oral features improved classification performance across **six metabolic diseases**.
- Key BMI and waist-circumference signals showed directional replication in an independent cohort of **20,293** participants.

---

## Visual Overview

### 1. Study design and association landscape
<div align="center">
  <img src="./project1_overview.png" alt="Project 1 overview" width="88%" />
</div>

**What this figure shows**
- Study design linking oral metagenomes with liver, glucose, and body-composition phenotypes
- Participant coverage and aligned sampling windows
- Global counts of significant associations across strain, gene family, and pathway layers

### 2. Core oral strains associated with metabolic phenotypes
<div align="center">
  <img src="./project1_core_strains.png" alt="Core strain signals" width="78%" />
</div>

This heatmap highlights representative oral strains with **favorable**, **adverse**, or **mixed** metabolic profiles across liver, CGM, and body-composition traits.

### 3. Core gene-family markers
<div align="center">
  <img src="./project1_core_genes.png" alt="Core gene-family signals" width="78%" />
</div>

This panel summarizes the most informative microbial **gene families**, including signals linked to biosynthesis, replication, stress response, and metabolic regulation.

### 4. Core pathway markers
<div align="center">
  <img src="./project1_core_pathways.png" alt="Core pathway signals" width="78%" />
</div>

This pathway view highlights biologically interpretable functions, including favorable biosynthetic programs and adverse pathways such as **polyamine biosynthesis** and **ceramide-related metabolism**.

### 5. Disease classification potential
<div align="center">
  <img src="./project1_classification.png" alt="Disease classification results" width="82%" />
</div>

Phenotype-selected oral features improved predictive performance for **hypertension**, **pre-diabetes**, **obesity**, **fatty liver**, **hypercholesterolaemia**, and **cholelithiasis/gallstones**, showing the translational potential of oral microbiome markers.

---
