Background. Transcriptomes are one of the first sources of high-throughput genomic data that have benefitted from  the introduction of Next-Gen Sequencing. However, the interpretation of the large numbers of short reads and a quantitative estimation of gene expression presents a challenge, particularly in the absence of a reference genome. As sequencing technology becomes more accessible transcriptome sequencing will extend to multiple organisms for which genome sequence is unavailable.
Results. Here we propose a computational workflow for the reconstruction of expressed gene transcripts, functional annotation and a quantitative estimation of transcript abundance that does not require a reference genome sequence and can be tolerant to low coverage. Instead of mapping reads to a reference genome or completely unsupervised clustering of reads we assemble the unknown transcriptome using nearest homologs from a public database as seeds. The workflow includes pre-existing free software and new programs for clustering reads and estimation of read count per gene cluster. Our algorithms are implemented in C and designed for parallel computation using a high-performance computer. We have applied our transcriptome analysis in a case study of an MiSeq project on the total RNA of the peri-rhopalial tissue of jellyfish Cyanea capillata. The analysis revealed over 5000 transcripts with different levels of expression for which a reasonable guess can be made about the function and evolutionary relationship to proteins in better studied model organisms.
Conclusion. The method we developed was effective in analysis of jellyfish transcriptome and may be applicable in other studies of gene expression in species lacking reference genome sequence. The software is available free of charge on the Open Source basis.