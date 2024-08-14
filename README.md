This repository contains scripts and instructions for a metatranscriptomic data analysis pipeline, focusing on breast cancer datasets. The pipeline includes quality control, trimming, alignment, and taxonomic profiling of RNA-seq data. It also includes R scripts for data visualization, particularly focusing on species and phylum-level clades and alpha diversity indices.

**Table of Contents**
Overview
Requirements
Directory Structure
Pipeline Steps
1. Quality Control with FastQC
2. Trimming with Trimmomatic
3. Alignment with STAR
4. Renaming and Moving Unmapped Reads
5. Taxonomic Profiling with MetaPhlAn
Data Visualization
Species-Level Clade Abundance
Phylum-Level Clade Abundance
Alpha Diversity Indices
License

**Overview**
This pipeline automates the analysis of metatranscriptomic data from raw RNA-seq FASTQ files to taxonomic profiling and data visualization. It leverages tools like FastQC, Trimmomatic, STAR, and MetaPhlAn, along with R for visualizing results.

**Requirements**
FastQC: For quality control of raw sequence data.
Trimmomatic: For trimming adapters and low-quality reads.
STAR: For aligning reads to the human genome.
MetaPhlAn: For profiling the taxonomic composition.
R: For data visualization.
Conda: For managing the MetaPhlAn environment.

**Installation**
Ensure you have the following installed on your system:
FastQC
Trimmomatic
STAR
Conda (for managing MetaPhlAn environment)
R with necessary libraries (ggplot2, dplyr, tidyr, vegan)
