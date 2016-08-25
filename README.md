# MetaCAT -  Metagenome Cluster Analysis Tool
The Metagenome Cluster Analysis Tool (MetaCAT) is a metagenome data mining tool to analyze metagenomes prior to annotation. MetaCAT sorts genes of an annotated reference library provided by the user according to their abundance in an unannotated metagenome, taking into account similar genes based on alignment. Genes in the reference library that have overlapping “signatures” in the metagenome are not reported, so that the final list of genes reported by MetaCAT are considered to be “unrelated” with respect to the given metagenome. Upon installation MetaCAT assembles the most recent viral RefSeq database as a default reference library, however, MetaCAT can be used with any reference library as well as other taxonomic or logical groups.

For installation instructions see the accompanying README file. For more detailed instructions a user guide is provided with the source code.

