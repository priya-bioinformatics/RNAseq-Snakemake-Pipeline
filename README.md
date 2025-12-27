# RNA-seq Pipeline (FASTQ → FeatureCounts)
# Overview
A reproducible paired-end RNA-seq workflow implemented in Snakemake, starting from raw FASTQ files and ending with gene-level counts using featureCounts.
Developed and tested on Kaggle with limited computational resources

# Workflow
FASTQ download from SRA
QC: FastQC + MultiQC
Trimming: fastp
Alignment: HISAT2
Quantification: featureCounts

# Tools
FastQC · MultiQC · fastp · HISAT2 · samtools · featureCounts · Snakemake

# Data
Public RNA-seq data from NCBI SRA
Example samples: SRR1039508, SRR1039509

# How to Run
snakemake --cores 4

# Output
QC reports (HTML)
Gene count matrix (featurecounts.txt)

# Kaggle Notebook:
https://www.kaggle.com/code/priyabioinformatics/rna-seq-pipeline-from-fastq-to-gene-counts

Author: Priya Bhuiya
Bioinformatics Enthusiast | RNA-seq & Dry-Lab Data
