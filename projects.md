---
layout: default
permalink: /projects/
---
# Projects & Samples

## Analysis of _Mycobacterium tuberculosis_ using bioinformatics tools
<a href="/assets/pdf/BIN3890_S2_2023_Kamila.pdf" target="_blank" rel="noopener">View Poster</a>
- Utilized Linux commands to execute data pre-processing (FastQC, Trimmomatic) and genome assembly (SPAdes, ABySS, SOAPdenovo2).
- Executed genome annotation (RAST, Prokka), identifying 16S rRNA sequences and core genes for functional analysis.
- Leveraged BLAST and R for phylogenetic tree construction, determining evolutionary relationships with other Mycobacterium species.
- Performed in silico DNA-DNA hybridization (ANI, GGDC) to confirm species-level identification.
<br><br>
<img src="https://img.shields.io/badge/Bash-white?logo=gnubash">
<img src="https://img.shields.io/badge/Python-white?logo=Python">
<img src="https://img.shields.io/badge/RStudio-white?logo=R&logoColor=blue">

## Comparative Genomic Analysis of Pathogenic and Non-Pathogenic _Mycobacterium_ Species
- Conducted comparative genomic analysis on _M. tuberculosis_ CCDC5180, _M. abscessus_ ATCC19977 (pathogens), and _M. vanbaalenii_ PYR1 (non-pathogen) to assess functional gene distribution across 27 subsystem features.
- Used R for data wrangling and visualization to reveal lower gene counts for “Virulence, Disease and Defense,” “Stress Response,” and “Cell Wall and Capsule” in the non-pathogenic strain.
<br><br>
<img src="/assets/img/Fig1.png">
<img src="https://img.shields.io/badge/RStudio-white?logo=R&logoColor=blue">
<img src="https://img.shields.io/badge/ggplot2-blue?logo=R">
<img src="https://img.shields.io/badge/tidyverse-blue?logo=R">
<img src="https://img.shields.io/badge/reshape2-blue?logo=R">

## Species and Subspecies Delineation Using ANI and DDH in _Mycobacterium_ Strains
- Conducted pairwise comparisons of _Mycobacterium immunogenum_ and _Mycobacterium abscessus_ genomes using Average Nucleotide Identity (ANI) and DNA-DNA Hybridization (DDH) metrics to assess taxonomic relatedness.
- Confirmed that M. immunogenum strains share ANI ≥95% and DDH ≥70%, supporting species-level classification, while CD116 strain’s DDH <80% indicated it forms a distinct subspecies.
<br><br>
<img src="/assets/img/Fig2.png">
<img src="https://img.shields.io/badge/RStudio-white?logo=R&logoColor=blue">
<img src="https://img.shields.io/badge/ggplot2-blue?logo=R">
<img src="https://img.shields.io/badge/tidyverse-blue?logo=R">

## Bioinformatics Analysis of Differential Gene Expression
- Applied DESeq2 (R/Bioconductor) to analyze RNA-seq data, identifying 296 differentially expressed genes (DEGs) between Plasmodium SBP (lab-adapted) and MT (mosquito-transmitted) strains, and revealing 133 SBP-upregulated (e.g., PCHAS_1100300) and 163 MT-upregulated genes linked to transmission.
- Used tidyverse (ggplot2, dplyr) to visualize DEGs through a volcano plot and matrix plot.
<br><br>
<img src="/assets/img/Fig3.png">
<img src="/assets/img/Fig4.png">
<img src="https://img.shields.io/badge/RStudio-white?logo=R&logoColor=blue">
<img src="https://img.shields.io/badge/BioConductor-blue?logo=R">
<img src="https://img.shields.io/badge/tidyverse-blue?logo=R">

[back](./)
