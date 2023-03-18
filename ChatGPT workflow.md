### ChatGPT workflow

- RNA sequencing (RNA-seq) is a technique used to measure gene expresssion by sequencing RNA molecules.
- The output of RNA-seq is typically a set of short reads in a .FASTQ file format.
- To analyze RNA-seq data, the reads are typically aligned to a reference genome or transcriptome using an aligner such as bwa or STAR.
- The output of the alignment is typically a set of aligned reads in a .BAM file format.
- To analyze the gene expression from RNA-seq data, the aligned reads can be quantified using tools such as featureCounts or HTSeq, which count the number of reads that overlap with each gene or transcript in the reference genome.
- The output of the quantification is typically a matrix of counts, where each row corresponds to a gene or transcript, and each column corresponds to a sample or cell.
- The count matrix can be further processed using tools such as DESeq2 or limma-voom to identify differentially expressed genes between different conditions or groups.
- Finally, we discussed how to convert a .BAM file containing aligned reads to a .loom file format, which can be used with tools such as scvelo for further analysis of single-cell RNA-seq data.