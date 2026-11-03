# Genki Balls Tank Experiment

## Background

This project examined how bacterial communities in tank water and sediment respond to the addition of genki balls (effective microorganism, or EM, mudballs), using 16S rRNA amplicon sequencing in a controlled tank experiment.

## Files and Directories

* genkiballs_tank_study.Rmd
    * Code to reproduce the analyses and figures for the tank experiment
* metadata
    * Tank_Experiment_Overview_Brief_on.docx: overview of the experimental design
    * Tank_Experiment_Sample_list.csv: list of all samples
    * Tank_Sediment_Metadata.csv: metadata for sediment samples
    * Tank_Water_Metadata.csv: metadata for water samples
* qiime2
    * asvtable_export
        * ASV table exported from QIIME 2 (feature-table.biom and genki_asvtable.tsv), used as the main input for the Rmd
    * taxonomy_export
        * taxonomy assignments for each ASV (taxonomy.tsv)

## Data availability

Raw sequence reads are available from NCBI SRA under BioProject PRJNA1399513