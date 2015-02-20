# Seq2HLA

seq2HLA is a computational tool to determine Human Leukocyte Antigen (HLA) directly from existing and future short RNA-Seq reads. 
It takes standard RNA-Seq sequence reads in fastq format as input, uses a bowtie index comprising known HLA alleles and outputs the most likely HLA class I and class II types, a p-value for each call, and the expression of each class.
