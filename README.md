# 🧬 Paired Tumor vs. Normal RNA-Seq Analysis

## 🎯 Project Goal
Identify differentially expressed genes (DEGs) by comparing publicly available RNA-Seq data from [Colorectal Cancer] tumor tissues against patient-matched adjacent normal tissues.

## 💾 Data Acquisition
* **Database:** NCBI Sequence Read Archive
* **Sample Selection:** [5] Tumor and [5] Matched Normal samples were selected. SRA Accessions are listed in `sample_accessions.txt`.

## 🛠️ Methodology & Tools
The analysis was performed using the following steps:
1.  **Quality Control:** FastQC
2.  **Alignment:** BWA
3.  **Quantification:** featureCounts or Salmon
4.  **Differential Expression:** DESeq2 (in R)

## 📦 Results
[To be filled in later with plots and key findings.]
