# AI_uses.md

This file contains a consolidated list of the main prompts and tasks performed with AI during the project.  
It summarizes—but does not reproduce verbatim—the extensive full conversation.

## Major Prompts

### 1. GWAS and PRS Workflow Development
- Identifying required summary statistics (EUR and AFR).
- Harmonizing and preprocessing GWAS-SSF files.
- Checking file integrity, shape, and data types.
- Preparing input for clumping (PLINK C+T workflow).
- Running PRS generation across ancestries (EUR→EUR, EUR→AFR, AFR→AFR, AFR→EUR).

### 2. 1000 Genomes Reference Panel Processing
- Downloading and organizing PLINK-formatted Phase 3 genotype files.
- Filtering individuals by ancestry panel.
- Quality control and verification of BIM/FAM/BED structure.

### 3. HPC + Colab Hybrid Workflow
- Installing tools on Colab (pandas, seaborn, etc.).
- Running heavy computation on HPC and lightweight tasks on Colab.
- Recording job commands, QC outputs, and troubleshooting failures.

### 4. Data Exploration and Visualization
- KDE plots and interpretation.
- Scatterplots and correlation matrices for PRS comparisons.
- Understanding variance collapse and KDE warnings.
- Cross-ancestry distribution shift analysis.





