# MCRL -  Metagenome Clustering by Reference Library
MCRL is a metagenome data mining tool to help analyze metagenomes. The input to MCRL is an assembled metagenome that does not need to be annotated, and a reference library containing annotated genes, such as a RefSeq database. MCRL then applies an iterative filtering algorithm to the genes in the reference library such that of all genes in the reference library MCRL will report only the genes that have significant hits in the metagenome and whose “signatures” in the metagenome do not overlap. Genes reported by MCRL are sorted according to the number of significant BLAST hits each gene received in the metagenome. When a reference library of viral genes is used for example, then MCRL will report the prevalent viral genes in a given metagenome. Upon installation MCRL assembles the most recent RefSeq database for viruses as a default reference library, however, MCRL can be used with any reference library as well as other taxonomic or logical groups. 

For installation instructions see the accompanying README file. For more detailed instructions, a user guide is provided with the source code.


References:
Tadmor A. D., Mahmoudabadi G., Foley H. B., Phillips R., Ubiquitous Commensal Phage Markers in Humans, 2019 (submitted)

Tadmor A. D., Ottesen E. A., Leadbetter J. R., Phillips R., Probing individual environmental bacteria for viruses by using microfluidic digital PCR. Science 333, 58-62

