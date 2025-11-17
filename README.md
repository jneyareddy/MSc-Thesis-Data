# MSc-Bioinformatics-Thesis-Data
This repository contains data from my MSc thesis in Bioinformatics and Computational Biology:
“Improving the genome annotations of non-_Saccharomyces_ yeast and microalgal species.”

The study focuses on generating high-quality genome annotations for:

_Torulaspora delbrueckii_ LO544

_Lachancea thermotolerans_ IWBT Y1240

_Chlorella sorokiniana_

These species, with wine-related origins, play important roles in wine fermentation and winery wastewater biotechnology. Despite the availability of genomic data, recent annotation data for these strains is lacking, limiting the exploitation of other omics datasets and their biotechnological potential. This work aimed to address that gap by producing improved genome annotations. The bioinformatics pipeline in this study assembles transcriptomes, evaluates sequencing data quality, and performs structural and functional annotation using MAKER and eggNOG-mapper. It also validates the improved annotations via differential gene expression and functional enrichment analyses to assess biological relevance.

All datasets are also available on Zenodo:  
[Download annotation data] https://doi.org/10.5281/zenodo.17623355

**Contents**

**Structural Annotations (MAKER):**

Final consensus GFF3 files

Evidence alignments

Combined evidence + annotation files

BUSCO scores and genome annotation statistics

**Functional Annotations (eggNOG-mapper):**

XLSX reports with predicted protein names, PFAM domains, GO terms, KEGG pathways and modules, and COG functional categories

**Validation Analysis (only tested on the _Torulaspora delbrueckii_ strain):**

Differential gene expression (DESeq2 results)

DEG visualizations

GO and KEGG enrichment graphs

**Significance**

These resources provide a foundation for future experimental and bioinformatics research aimed at leveraging the biotechnological applications of non-_Saccharomyces_ yeasts and microalgal species.
