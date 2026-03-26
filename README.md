# Multi-Omics Data Analytics & Practical Training 🧬

This repository contains a comprehensive suite of bioinformatics analyses, demonstrating proficiency in handling large-scale NGS data and proteomics. The workflows integrate High-Performance Computing (HPC), R/Bioconductor, and shell scripting to derive biological insights.

## 🎯 Key Learning Objectives & Skills
- **HPC & Bash:** Job submission, node management, and automated pipeline development in Linux/Unix environments.
- **Genomics:** Variant calling (WES/WGS), alignment QC with Samtools, and functional annotation.
- **Transcriptomics:** RNA-Seq workflows, Differential Gene Expression (DGE), and Gene Set Enrichment Analysis (GSEA).
- **Epigenomics:** ChIP-Seq analysis, including peak calling (MACS2), peak annotation, and visualization.
- **Proteomics:** Phosphoproteomics analysis using Limma and kinase activity profiling (KSEA).

---

## 📁 Repository Structure

### 📂 [Genomics & Variant Calling](./Genomics_and_Variant_Calling)
*Focus: DNA-Seq processing and somatic mutation discovery.*
- **[DNA-Seq Analysis Report](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Omics-Data-Analysis/blob/main/Genomics_and_Variant_Calling/DNA-Seq-Variant-Analysis.html)**: Interactive report on variant allele frequencies (VAF).
- **[Filtered Variants](./Genomics_and_Variant_Calling/final_variants_FREQ10.txt)**: Curated list of high-confidence mutations (FREQ > 10%).
- **[Alignment QC](./Genomics_and_Variant_Calling/Samtools.pdf)**: Flagstat reports generated via HPC Samtools.

### 📂 [Transcriptomics & Epigenomics](./Transcriptomics_and_Epigenomics)
*Focus: Gene expression and Chromatin Immunoprecipitation (ChIP) analysis.*
- **[RNA-Seq Analysis Report](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Omics-Data-Analysis/blob/main/Transcriptomics_and_Epigenomics/RNA-Seq-Differential-Expression.html)**: Differential expression and pathway analysis.
- **[ChIP-Seq Analysis Part 1](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Omics-Data-Analysis/blob/main/Transcriptomics_and_Epigenomics/ChIP-Seq-Analysis-Part1.html)**: Initial filtering and data preparation for ChIP-Seq.
- **[ChIP-Seq Peak Annotation](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Omics-Data-Analysis/blob/main/Transcriptomics_and_Epigenomics/ChIP-Seq-Peak-Annotation.html)**: Peak calling and genomic feature distribution.
- **[Visualisation Report](./Transcriptomics_and_Epigenomics/ChIP-Seq-Visualisation-Report.pdf)**: Distance to TSS distribution and peak count frequency plots.

### 📂 [Proteomics & Theoretical Foundations](./Proteomics_and_Theory)
*Focus: Signal transduction and bioinformatic strategies.*
- **[Proteomics Report](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Omics-Data-Analysis/blob/main/Proteomics_and_Theory/Proteomics.html)**: MAPK pathway inhibition and kinase activity under drug treatment.
- **[Theoretical Analysis](./Proteomics_and_Theory/Omics-Theoretical-Analysis.pdf)**: Expert discussion on single-cell vs. bulk RNA-seq and epigenetic mechanisms.

---

## 🛠 Bioinformatic Toolset
- **Core Tools:** Samtools, MACS2, VarScan2, ANNOVAR, ChIPseeker.
- **Statistical Frameworks:** R (Bioconductor), Limma, KSEAapp.
- **Environment:** High-Performance Computing (HPC) Clusters (Linux/Bash).

---
*Note: HTML reports are rendered using GitHub HTML Preview for interactive viewing.*
