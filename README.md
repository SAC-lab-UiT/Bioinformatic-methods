## Bioinformatic methods

Bioinfomatic analysis will be performed by Stem Cell Aging and Cancer Research Group. Raw data will be processed on the computing cluster Saga (UNINETT Sigma2 AS). For RNA-sequencing analysis, reads will be mapped using STAR 1 and counted using HTSeq-Counts 2. Differential gene expression will be performed using DESeq2 3. For ChIP-seq analysis, reads will be mapped using BWA 4. Peak calling will be executed by MACS 5 and annotated using ChIPseeker 6. An overlap analysis will be performed by comparing significant peaks to differentially expressed genes. Further downstream data exploration include motif enrichment (MEME suite 7), gene set enrichment (clusterProfiler 8) and pathway analyis (ReactomePA 9). 


# References
1	Dobin, A. et al. STAR: ultrafast universal RNA-seq aligner. Bioinformatics 29, 15-21, doi:10.1093/bioinformatics/bts635 (2013).

2	Anders, S., Pyl, P. T. & Huber, W. HTSeq--a Python framework to work with high-throughput sequencing data. Bioinformatics 31, 166-169, doi:10.1093/bioinformatics/btu638 (2015).

3	Love, M. I., Huber, W. & Anders, S. Moderated estimation of fold change and dispersion for RNA-seq data with DESeq2. Genome Biol 15, 550, doi:10.1186/s13059-014-0550-8 (2014).

4	Li, H. & Durbin, R. Fast and accurate short read alignment with Burrows-Wheeler transform. Bioinformatics 25, 1754-1760, doi:10.1093/bioinformatics/btp324 (2009).

5	Zhang, Y. et al. Model-based analysis of ChIP-Seq (MACS). Genome Biol 9, R137, doi:10.1186/gb-2008-9-9-r137 (2008).

6	Yu, G., Wang, L. G. & He, Q. Y. ChIPseeker: an R/Bioconductor package for ChIP peak annotation, comparison and visualization. Bioinformatics 31, 2382-2383, doi:10.1093/bioinformatics/btv145 (2015).

7	Bailey, T. L. et al. MEME SUITE: tools for motif discovery and searching. Nucleic Acids Res 37, W202-208, doi:10.1093/nar/gkp335 (2009).

8	Yu, G., Wang, L. G., Han, Y. & He, Q. Y. clusterProfiler: an R package for comparing biological themes among gene clusters. OMICS 16, 284-287, doi:10.1089/omi.2011.0118 (2012).

9	Yu, G. & He, Q. Y. ReactomePA: an R/Bioconductor package for reactome pathway analysis and visualization. Mol Biosyst 12, 477-479, doi:10.1039/c5mb00663e (2016).


