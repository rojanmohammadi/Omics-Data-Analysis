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
- **[DNA-Seq Analysis Report](./Genomics_and_Variant_Calling/DNA-Seq-Variant-Analysis.html)**: Interactive report on variant allele frequencies (VAF).
- **[Filtered Variants](./Genomics_and_Variant_Calling/final_variants_FREQ10.txt)**: Curated list of high-confidence mutations (FREQ > 10%).
- **[Alignment QC](./Genomics_and_Variant_Calling/Samtools.pdf)**: Flagstat reports generated via HPC Samtools.

### 📂 [Transcriptomics & Epigenomics](./Transcriptomics_and_Epigenomics)
*Focus: Gene expression and Chromatin Immunoprecipitation (ChIP) analysis.*
- **[RNA-Seq Analysis](./Transcriptomics_and_Epigenomics/RNA-Seq-Differential-Expression.html)**: Differential expression and pathway analysis.
- **[ChIP-Seq Peak Annotation](./Transcriptomics_and_Epigenomics/ChIP-Seq-Peak-Annotation.html)**: Peak calling and genomic feature distribution.
- **[Visualisation Report](./Transcriptomics_and_Epigenomics/ChIP-Seq-Visualisation-Report.pdf)**: Distance to TSS distribution and peak count frequency plots.

### 📂 [Proteomics & Theoretical Foundations](./Proteomics_and_Theory)
*Focus: Signal transduction and bioinformatic strategies.*
- **[Proteomics Report](./Proteomics_and_Theory/Proteomics.html)**: MAPK pathway inhibition and kinase activity under drug treatment.
- **[Theoretical Analysis](./Proteomics_and_Theory/Omics-Theoretical-Analysis.pdf)**: Expert discussion on single-cell vs. bulk RNA-seq and epigenetic mechanisms.

---

## 🛠 Bioinformatic Toolset
- **Core Tools:** Samtools, MACS2, VarScan2, ANNOVAR, ChIPseeker.
- **Statistical Frameworks:** R (Bioconductor), Limma, KSEAapp.
- **Infrastructure:** Linux/Bash, HPC Cluster (SLURM/SGE).

---
*Note: To view interactive HTML reports, please use [GitHub HTML Preview](https://htmlpreview.github.io/).*
