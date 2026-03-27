# 🧬 Oral Microbiome

This repository hosts code, analysis pipelines, and resources for **oral microbiome**, with a focus on large-scale, high-resolution studies linking the oral microbiome to human health.

---

## 🚀 Project Roadmap

Our research is organized as a series of projects aimed at systematically uncovering the role of the oral microbiome in systemic diseases.

### ** Population-scale Characterization of the Oral Microbiome and Associations with Metabolic Health**

📄 *Published in Nature Communications*

This project establishes the foundation of our research by constructing a **population-scale, multi-layer association atlas** linking the oral microbiome to host metabolic health.

---

## 🔍 Overview

We integrate **whole-metagenome oral microbiome data** with **deep metabolic phenotyping** to identify microbial signatures associated with metabolic traits across multiple physiological systems.

This repository provides code to reproduce all analyses from the paper:

> **“Population-scale Characterization of the Oral Microbiome and Associations with Metabolic Health”**

---

## 📊 At a Glance

- **Cohort:** 9,431 participants (Human Phenotype Project, HPP)  
- **Phenotyping depth:** 44 metabolic traits across:
  - Liver ultrasound  
  - Continuous glucose monitoring (CGM)  
  - DXA-based body composition  
- **Microbiome resolution:**
  - Strain-level  
  - Gene-family level  
  - Pathway level  
- **Output:** A comprehensive **oral microbiome–metabolism association atlas**

---

## 💡 Why This Work Matters

Most microbiome studies are limited by either **small cohorts** or **low-resolution profiling**.

In contrast, this work:
- Combines **population-scale data** with **whole-metagenome resolution**
- Integrates **multi-system metabolic phenotyping**
- Enables discovery of **both system-specific and cross-phenotype microbial signals**

This creates a **new reference framework** for studying the oral microbiome in human health and disease.

---

## 🧠 Key Contributions

### 1. Population-scale, high-resolution microbiome profiling  
We analyze standardized bilateral buccal-swab whole-metagenome data from **9,431 individuals**, paired with rich metabolic phenotypes.

### 2. A unified multi-layer MWAS framework  
We introduce a rigorous framework to test associations across:
- Strains  
- Gene families  
- Pathways  

Using covariate-adjusted models and **layer-specific multiple testing control**.

### 3. Translational and validated outputs  
- A **multi-system association atlas**
- Identification of **cross-phenotype microbial markers**
- Demonstration of **metabolic disease classification**
- **External validation** in an independent cohort

---

## 🔬 Key Findings

- Significant associations identified:
  - **213 strains**
  - **124,603 gene families**
  - **299 pathways**

- **Strain-level signals** are enriched for:
  → Body composition traits  

- **Functional signals (genes & pathways)** are enriched for:
  → Glucose regulation (CGM-derived phenotypes)

- Oral microbiome features improve prediction of:
  - Hypertension  
  - Pre-diabetes  
  - Obesity  
  - Fatty liver  
  - Hypercholesterolaemia  
  - Gallstones  

- Key BMI and waist-related signals **replicate directionally** in an independent cohort of **20,293 individuals**

---

## 🖼️ Visual Overview

### 1. Study design and global association landscape
<div align="center">
  <img src="./Figures/project1/fig1.png" alt="Study design and association landscape" width="88%" />
</div>

**Highlights:**
- Cohort design and sampling alignment  
- Integration of microbiome and multi-system phenotypes  
- Global association counts across all molecular layers  

---

### 2. Core strain-level associations
<div align="center">
  <img src="./Figures/project1/fig2.png" alt="Core strain associations" width="78%" />
</div>

Representative oral strains showing:
- Favorable metabolic associations  
- Adverse associations  
- Mixed phenotype effects  

---

### 3. Gene-family signatures
<div align="center">
  <img src="./Figures/project1/fig3.png" alt="Gene-family associations" width="78%" />
</div>

Key microbial gene families linked to:
- Biosynthesis  
- Replication  
- Stress response  
- Metabolic regulation  

---

### 4. Pathway-level insights
<div align="center">
  <img src="./Figures/project1/fig4.png" alt="Pathway associations" width="78%" />
</div>

Biologically interpretable pathways, including:
- Favorable biosynthetic programs  
- Adverse pathways such as:
  - Polyamine biosynthesis  
  - Ceramide-related metabolism  

---

### 5. Disease classification performance
<div align="center">
  <img src="./Figures/project1/fig5.png" alt="Disease classification" width="82%" />
</div>

Oral microbiome features improve prediction across multiple metabolic diseases, highlighting **clinical and translational potential**.

---

## 📁 Repository Structure
