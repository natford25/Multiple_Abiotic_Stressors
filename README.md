# Multiple Abiotic Stressors 
Repository of code for "Concurrent abiotic stressors reorganize plant-microbiome systems across traits, communities, and exudates"

## Citation 
! insert DOI link here when available ! 

## Abstract 
Concurrent environmental stressors can generate biological responses that are difficult to predict from individual stressors alone. We used a full-factorial wheat experiment combining drought, microplastic, antibiotic, and herbicide exposure to determine how multiple stressors reorganize plant-soil microbial systems. A multiplicative null model revealed predominantly antagonistic interactions for biomass, whereas root architectural traits exhibited both synergistic and antagonistic responses. A complementary distance-based approach showed that rhizosphere microbiota and root exudate profiles generally diverged further from control conditions as stressor number increased, although responses depended strongly on stressor identity. Microplastic and antibiotic exposure disproportionately shaped microbiota composition and higher-order treatment outcomes. Stressors also extensively reorganized microbe-metabolite association networks, despite no detectable changes in bacterial alpha diversity. Together, these results show that multi-stressor effects are response-dependent and multidimensional, with plant traits, microbial communities, root chemistry, and their associations capturing distinct components of plant-microbe responses under concurrent environmental stress. 

## Raw data 
Raw 16S rRNA amplicon sequencing data are available on NCBI SRA under BioProject ID PRJNA1509610. 
Raw metabolomics data are available as a MassIVE dataset under accession number MSV000102871. 

## Phenotypic processing and analysis 
* Main analysis of biomass and root architectural traits conducted in [MSE1_Univariate_Multiplicative](Univariate_Analysis/MSE1_Univariate_Multiplicative.Rmd)

## Bacterial processing and analysis 
* Bacterial sequences were trimmed in [MSE1_dada2_cutadapt](Multivariate_Analyses/MSE1_dada2_cutadapt.Rmd)
* Bacterial sequences were processed and filtered in [MSE1_dada2_processing](Multivariate_Analyses/MSE1_dada2_processing.Rmd)
* Taxonomy was assigned to bacterial sequences and rarefaction was performed in [MSE1_16SProcessing](Multivariate_Analyses/MSE1_16SProcessing.Rmd)
* Main rhizosphere bacterial community analysis conducted in [MSE1_16S_multiplicative](Multivariate_Analyses/MSE1_16S_multiplicative.Rmd)

## Metabolomics processing and analysis 
* Data wrangling and initial analysis of metabolomics data was conducted in [MSE1_Exudates](Multivariate_Analyses/MSE1_Exudates.Rmd). Main analysis performed in conjunction with main analysis of bacterial community ([MSE1_16S_multiplicative](Multivariate_Analyses/MSE1_16S_multiplicative.Rmd))
* Quantification of total organic carbon in exudates performed in [MSE1_TOC](Univariate_Analysis/MSE1_TOC.Rmd)

## Supplementary information 
* Confirmation of drought effects conducted in [MSE1_Drought](Univariate_Analysis/MSE1_Drought.Rmd)
  
