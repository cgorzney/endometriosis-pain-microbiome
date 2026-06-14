# Endometriosis Pain Microbiome Analysis
Repository containing analysis code, processed microbiome data, and de-identified metadata supporting the manuscript on endometriosis, pain severity, within the the vaginal and rectal microbiome.

# Repository Structure
**data/**

Contains de-identified data required to reproduce analyses. 
- Phylo_public.rds should be used for all analyses except sensitivity analyses. 
- Phylo_public_original_labels.rds should be used for sensitivity analyses only. 

**scripts/**

Contains R Markdown and R scripts used to generate all analyses, figures, and statistical results presented in the manuscript. 

# Reproducibility
The provided scripts were developed in R. Users may need to modify local file paths depending on where repository files are stored on their systems. All required de-identified data files are inluded in the data directory.

Analyses were performed using the package versions specified within the scripts. Users are encouraged to review package requirements before reproducing analyses. 

# Data Availability
De-identified metadata, processed microbiome data, and analysis scripts are publicly available in this repository.

# Repository Contributions
**- Cameron A Gorzney (CAG):** Repository development and maintenance, data curation, analytical code development, statistical analyses, figure generation, and reproducibility documentation.
**- Raunak Vijayakar (RV):** Analytical code development, statistical analyses, figure generation, and reproducibility documentation
**- Stephen Johnson (SJ):** Analytical code development and statistical analyses
**- Michelle Bland (MB):** Code modifications for sample relabeling and figure preparation. 
