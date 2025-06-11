# 🧠 A Bioinformatics Exploration of Differential Gene Expression in Amyotrophic Lateral Sclerosis (ALS)

This repository contains the complete research pipeline, code, results, and thesis manuscript from my Master’s project titled “A Bioinformatics Exploration of Differential Gene Expression in Amyotrophic Lateral Sclerosis (ALS),” with a focus on identifying dysregulated pathways and genes contributing to neurodegeneration.


---

## 🧪 Abstract

Amyotrophic Lateral Sclerosis (ALS) is a progressive neurodegenerative disorder that results in the degeneration of upper and lower motor neurons. This project investigates the differential expression of genes in ALS using RNA-seq data and bioinformatics analysis tools. Our results highlight dysregulated genes and biological pathways associated with oxidative stress, inflammation, DNA damage, and synaptic function—offering insights into ALS pathology and possible therapeutic targets.

---

## 🔬 Key Methods

- 🔹 Data source: GEO datasets (RNA-seq & microarray)
- 🔹 Preprocessing: Cutadapt, FastQC for QC; alignment via HISAT2 and STAR
- 🔹 Quantification: HTSeq-count, featureCounts
- 🔹 DEG analysis: IDEP 2.0 platform using DESeq2 and edgeR
- 🔹 Functional annotation: GO and KEGG enrichment using clusterProfiler
- 🔹 Validation: RNA quality check with Nanodrop & Bioanalyzer; qPCR evidence
- 🔹 Visualization: Heatmaps, PCA, Volcano plots, Scatter plots, MA plots

---

## 📊 Key Results

- Identified DEGs: Several genes upregulated/downregulated in ALS brain tissue
- Enriched biological processes:
  - Oxidative stress response  
  - Neuroinflammation  
  - DNA damage and repair  
  - Synaptic signaling and RNA metabolism  
- Visual summaries include PCA plots, volcano plots, MA plots, and heatmaps
- Tools used: DESeq2, IDEP, clusterProfiler, R, Bioconductor

---

## 🌟 Highlights

- Used both alignment-based (STAR, HISAT2) and web-based (IDEP) pipelines
- Multi-tool validation approach: Nanodrop, qPCR, RNA integrity score
- Functional enrichment revealed inflammation & mitochondrial involvement
- Useful for biomarker identification in ALS neurodegeneration

---

## 📂 Contents

- `/data/` – Preprocessed RNA-seq and expression matrices  
- `/scripts/` – R code for DEG analysis, enrichment, plots  
- `/figures/` – Volcano plots, PCA, heatmaps, scatter plots  
- `/methods/` – Alignment logs, FastQC output, qPCR tables  
- `README.md` – 📘 Project summary  
- `ALS_DEG_Thesis_FaizaFathin.pdf` – 📄 Full MSc thesis

---

## 🔑 Keywords

- Amyotrophic Lateral Sclerosis (ALS)  
- Differential gene expression  
- RNA-seq  
- HISAT2 / STAR  
- DESeq2 / edgeR  
- IDEP 2.0  
- FastQC  
- GO and KEGG enrichment  
- qPCR validation  
- clusterProfiler  
- Neuroinflammation  
- Oxidative stress  
- TDP-43 / C9orf72  
- Motor neuron degeneration

---

## 📁 Repository Structure

- `README.md` — 📘 Project summary (you are here)  
- `ALS_DEG_Thesis_FaizaFathin.pdf` — 📄 Full thesis manuscript

---

## 📫 Contact

- 👩‍💻 Author: Faiza Fathin  
- 📧 Email: faizafathin161102@gmail.com  
- 🌐 [GitHub](https://github.com/faizafathin)

---

_“Understanding ALS through transcriptomic signatures: a systems biology approach.”_
