# Accurate Detection of Convergent Mutations in Large Protein Alignments with ConDor


### Marie MOREL, Anna ZHUKOVA, Frédéric LEMOINE and Olivier GASCUEL

This repository contains data and files used in the article describing ConDor. ConDor is a workflow developed to detect convergent evolution in amino acid alignments. 

Other resources:
1. ConDor is also available as a web service ([https://condor.pasteur.cloud](https://condor.pasteur.cloud)).
2. The code of the ConDor workflow can be found in the [condor](https://github.com/evolbioinfo/condor) repository.

## Content of the repository
* data folder: data described in the Materials and Methods section, including sequence alignments and phylogenetic trees.  
* results folder: csv files corresponding to the outputs provided by ConDor, as well as the results from FADE and PCOC.
    * __Note__: For Rhodopsin data, amino-acid positions presented in results files `results/rhodopsin` have a -12 offset compared to numbering presented in the manuscript.
* src folder: scripts used to analyze the data and obtain tables and figures as in the ConDor Paper. You can also find the commands used to run the various tools (FADE, PCOC, JPHMM...).
* The document [MutationsValidationsReferences](MutationsValidationsReference.md) summarizes the information on convergence mutations (potential or validated) that we use to compare ConDor, FADE, and PCOC. 
