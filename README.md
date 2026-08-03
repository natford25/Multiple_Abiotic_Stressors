# Multiple Abiotic Stressors 
Repository of code for "Concurrent abiotic stressors reorganize plant-microbiome systems across traits, communities, and exudates"

## Citation 
! insert DOI link here when available ! 

## Abstract 
Concurrent environmental stressors are increasingly common and interact in non-additive, context-dependent ways. We quantified the combined effects of simultaneous stressors on plant traits, plant-associated microbiota, and root chemistry. We applied four stressors (microplastic, drought, antibiotic, and herbicide) in a full-factorial wheat experiment. In addition to a multiplicative null model for univariate responses, we used a distance-based approach to quantify how stressor combinations shifted multivariate responses. Antagonistic interactions dominated biomass responses, whereas root traits were more variable. Multivariate analyses revealed pronounced restructuring of root-associated microbiota and exudate chemistry, with microplastic and antibiotic emerging as dominant drivers of community and metabolite composition. These stressors reorganized plant-microbiome assemblages largely independently of host traits, revealing a decoupling of microbial and chemical responses from plant trait outcomes. These results reveal that multi-stressor outcomes are trait-dependent, fundamentally multidimensional, and provide an analytical framework for resolving how complex biological systems reorganize under concurrent stress. 

## Phenotypic processing and analysis 
* Main analysis conducted in <name of r file + link>

## Bacterial processing and analysis 
* Bacterial sequences were trimmed in [MSE1_dada2_cutadapt_f](MSE1_dada2_cutadapt_f)
* Bacterial sequences were processed and filtered in [MSE1_dada2_processing_f](MSE1_dada2_processing_f)
* Taxonomy was assigned to bacterial sequences and rarefaction was performed in [MSE1_16S_Processing_f](MSE1_16S_Processing_f)
* Main analysis conducted in [MSE1_16S_Multiplicative_f](MSE1_16S_Multiplicative_f)

## Metabolomics processing and analysis 
* Data wrangling was conducted in [MSE1_Exudates_f](MSE1_Exudates_f)
* Quantification of total organic carbon in exudates performed in [MSE1_TOC](MSE1_TOC)

## Supplementary/Other information 
* Confirmation of drought effects conducted in [MSE1_Drought](MSE1_Drought)
  
