# Computational challenges in medical genomics

The topics covered in the seminar are related to recent computational challenges that arise from the fields of genomics and biomedicine, including but not limited to genomic variant interpretation, genomic sequence analysis, compressive genomics tasks, single-cell approaches, privacy considerations, statistical frameworks, etc. 
Both recently published works contributing novel ideas to the areas mentioned above as well as seminal contributions from the past are amongst the list of selected papers.
## [On the complexity of sequence-to-graph alignment](https://www.liebertpub.com/doi/abs/10.1089/cmb.2019.0066?journalCode=cmb)

[Slides](https://github.com/MirkoDeVita98/ETH_Seminars/blob/main/On_the_comp_of_seq_to_graph_alignment.pdf)

The Sequence-to-Graph alignment problem has several applications in genomics, pangenomics, and transcriptomics. 
In particular, aligning sequences to graphs has the potential to increase the number of aligned reads for several tasks such as Variant Calling, Genome Assembly and RNA-Seq data analysis.

The authors show that aligning sequences to a graph is a NP-complete problem for any constant alphabet size when changes are allowed in the graph. They also present an efficient polynomial algorithm when changes are only allowed in the sequence. 
Even if the algorithm is still unpractical for high throughput DNA sequencing, future work will try to solve this issue.
