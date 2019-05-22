# Identification of novel mutations MAMLD1, SLC22A6, DMWD etc. involved in leukemia through next-generation sequencing of Methylated DNA

We have performed variant analysis to find out novel mutations as potential carcinogens involved in leukemia. By analyzing eight different leukemia samples, we have got total 22 mutated genes. 

![ngs_logo](https://user-images.githubusercontent.com/28592095/56662619-c334b280-66e7-11e9-84dd-ef9fe7a135e0.png)

## Getting Started

The following instructions will guide you to reproduce the results. See the instructions below:

### Deep Varaint Implementation 
Please see the guideline in the link below for running deep variant in your google cloud platform:

1) https://codelabs.developers.google.com/codelabs/genomics-deepvariant/#0

2) https://cloud.google.com/genomics/docs/tutorials/deepvariant

### Galaxy Implementation

Please see the following workflow to reproduce this work:

1) https://usegalaxy.org/u/raktimlive/w/workflow-constructed-from-history-leukemia-variant-analysis

2) https://usegalaxy.org/u/raktimlive/w/simplefreebayes

### Reference Genome and Annotaion

Human Genome UCSC HG38 is used as a reference genome. Please see the following link:

https://usegalaxy.org/u/raktimlive/h/leukemia--ref-data

For annotating the variants please see the following link:

https://asia.ensembl.org/info/docs/tools/vep/index.html

We also used ANNOVAR for annotating the variants.

### Gene Ontology (GO) and Protein Protein Interation (PPI)

1) Gene ontology was performed using DAVID 6.7 https://david-d.ncifcrf.gov/

2) Protein Protein Interation was performed using STRING 10.5 https://version-10-5.string-db.org/cgi/input.pl?sessionId=3VWjqeV3YKrL&input_page_show_search=on

## Proposed Block Diagram


![pipeline](https://user-images.githubusercontent.com/28592095/56661195-96cb6700-66e4-11e9-845d-829ded473fff.png)




## Datasets

* [European Nucleotide Archive (ENA)](https://www.ebi.ac.uk/ena/data/view/PRJNA156619)

Also available at the following link:

* [Gene Expression Ominbus (GEO)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE33230)

| Sample ID | Sample Type |
| ------------------ | :------------------: |
| SRR408623 | LiPS_1 Cell Line (Reprogrammed)|
| SRR408624 | LiPS_1 Cell Line (Reprogrammed)|
| SRR408625 | LiPS_3 Cell Line (Reprogrammed)|
| SRR408626 | LiPS_3 Cell Line (Reprogrammed)|
| SRR408627 | hES Cell Line (Reprogrammed)|
| SRR408628 | hES Cell Line (Reprogrammed)|
| SRR408629 | K562 Cell Line (Leukemia Cell)|
| SRR408630 | K562 Cell Line (Leukemia Cell)|


## Acknowledgments

* Deep variant analysis was performed in Google Cloud Platform using https://github.com/google/deepvariant
* All other analysis was performed in https://usegalaxy.org/ and https://usegalaxy.org.au/


