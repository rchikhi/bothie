## README

A collection of 4 small datasets of reads with various identities to the Sars-Cov-2 genome.

* `NC_045512.fasta`: the Wuhan Sars-Cov-2 genome
* `outlier/`: those reads shouldn't map to NC_045512 at all
* `93p/`: 93% identity in protein-space within the RdRP protein, but overall 60-70% nucleotide identity. too low for both mapping and k-mer methods
* `95p/`: 95% identity, can fit some k-mers but not all, and can be mapped
* `99p/`: 99% identity, can be found with k-mers and mapping alike
