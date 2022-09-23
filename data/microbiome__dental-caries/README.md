# microbiome__dental-caries
The `microbiome__dental-caries` dataset contains the  oral microbiome (16S rRNA OTUs) from supragingival plaque samples of Australian children (twin-study) with and without dental caries.

* `X.tsv.gz`  - (473 samples, 481 features) compositional data with counts for each OTU in each sample. 


* `Y.tsv.gz` - (473 samples, 7 fields) contains metadata for samples including subject identifier, sex, age, zygosity, and phenotype. 

* `taxonomy.tsv.gz` - (155 features, 2 fields) contains taxonomy and confidence information for OTUs.

* `phylogeny.nwk` - Phylogenetic tree with 481 OTUs.

* `sequences.fasta.gz` - Centroid sequences for 481 OTUs.

**Source:**

Gomez A+, **Espinoza JL+**, Harkins DM, Leong P, Saffery R, Bockmann M, Torralba M, Kuelbs C, Kodukula R, Inman J, Hughes T, Craig JM, Highlander SK, Jones MB, Dupont CL, Nelson KE. Host Genetic Control of the Oral Microbiome in Health and Disease. Cell Host Microbe. 2017 Sep 13;22(3):269-278.e3. [doi: 10.1016/j.chom.2017.08.013](https://doi.org/10.1016/j.chom.2017.08.013). PubMed PMID: 28910633; PubMed Central PMCID: PMC5733791. [PDF](https://github.com/jolespin/publications/blob/master/PDFs/Gomez-Espinoza_2017__CellHostMicrobe.pdf)