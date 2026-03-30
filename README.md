# Multi-Omics Data Analytics & Practical Training 🧬

This repository showcases a comprehensive suite of bioinformatics workflows, from raw data processing on High-Performance Computing (HPC) clusters to integrated multi-omics downstream analysis. The projects demonstrate proficiency in DNA-Seq, RNA-Seq, ChIP-Seq, and Proteomics.

## 🎯 Core Competencies & Learning Objectives

### 💻 High-Performance Computing (HPC) & Bash
- **Infrastructure:** Proficient in the Linux system and HPC environments for large-scale data processing.
- **Job Management:** Experienced in job submission, node management, and executing array jobs.
- **Automation:** Developing Bash scripts for automated bioinformatics pipelines and custom functions.

### 🧬 DNA Sequencing & Variant Analytics (WES/WGS)
- **Primary Analysis:** Handling Fastq files, Quality Control (QC), and sequence alignment using Samtools.
- **Variant Discovery:** Somatic and germline variant calling, including functional annotation and interpretation of Variant Allele Frequency (VAF).
- **Practical Output:** [DNA-Seq Analysis Report](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Omics-Data-Analysis/blob/main/Genomics_and_Variant_Calling/DNA-Seq-Variant-Analysis.html).

### 📊 RNA Sequencing & Differential Expression
- **Quantification:** Gene quantification from Fastq files, raw read counting, and library normalization.
- **Statistical Analysis:** Differential Gene Expression (DGE) analysis and data interpretation using R/Bioconductor.
- **Pathway Analysis:** Performing Gene Set Over-representation Analysis (ORA) and Gene Set Enrichment Analysis (GSEA).
- **Practical Output:** [RNA-Seq Analysis Report](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Omics-Data-Analysis/blob/main/Transcriptomics_and_Epigenomics/RNA-Seq-Differential-Expression.html).

### 🕯️ Epigenomics & ChIP-Seq Analysis
- **Peak Calling:** Analyzing regulatory elements using MACS2, including PCR duplicate removal and down-sampling.
- **Annotation:** Peak annotation in relation to genes and genomic features; Motif enrichment analysis.
- **Visualization:** Mapping read distributions in regions of interest and visualizing ChIP-Seq peaks.

### 🧪 Proteomics & Signal Transduction
- **Quantitative Proteomics:** Standard proteomics analysis and enrichment analysis to study protein-level changes.
- **Kinase Activity:** Profiling kinase activity and signal transduction pathways (e.g., MAPK pathway) under therapeutic treatment.

---

## 📁 Repository Structure

### 📂 [Genomics & Variant Calling](./Genomics_and_Variant_Calling)
- **[DNA-Seq Analysis Report](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Omics-Data-Analysis/blob/main/Genomics_and_Variant_Calling/DNA-Seq-Variant-Analysis.html)**: VAF interpretation and mutation discovery.
- **[Filtered Variants](./Genomics_and_Variant_Calling/final_variants_FREQ10.txt)**: High-confidence somatic variants.
- **[Alignment QC](./Genomics_and_Variant_Calling/Samtools.pdf)**: HPC-generated QC and alignment stats.

### 📂 [Transcriptomics & Epigenomics](./Transcriptomics_and_Epigenomics)
- **[RNA-Seq Analysis Report](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Omics-Data-Analysis/blob/main/Transcriptomics_and_Epigenomics/RNA-Seq-Differential-Expression.html)**: DGE and GSEA results.
- **[ChIP-Seq Analysis Part 1](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Omics-Data-Analysis/blob/main/Transcriptomics_and_Epigenomics/ChIP-Seq-Analysis-Part1.html)**: Filtering and input preparation.
- **[ChIP-Seq Peak Annotation](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Omics-Data-Analysis/blob/main/Transcriptomics_and_Epigenomics/ChIP-Seq-Peak-Annotation-Part2.html)**: Motif analysis and distribution plots.
- **[Visualisation Report](./Transcriptomics_and_Epigenomics/ChIP-Seq-Visualisation-Report.pdf)**: Integrated epigenetic visualizations.

### 📂 [Proteomics & Theory](./Proteomics_and_Theory)
- **[Proteomics Report](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Omics-Data-Analysis/blob/main/Proteomics_and_Theory/Proteomics.html)**: Kinase activity and enrichment.
- **[Theoretical Analysis](./Proteomics_and_Theory/Omics-Theoretical-Analysis.pdf)**: Discussion on single-cell vs. bulk technologies and DNA methylation techniques.

---

## 🛠 Bioinformatic Toolset
- **Languages:** Bash/Shell, R (Bioconductor).
- **Genomics:** Samtools, BWA, VarScan2, ANNOVAR.
- **Epigenomics:** MACS2, ChIPseeker, Motif Analysis tools.
- **Proteomics:** Limma, KSEAapp.
- **Environment:** High-Performance Computing (HPC) Clusters.
