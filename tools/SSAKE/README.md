# SSAKE

The Short Sequence Assembly by K-mer search and 3' read Extension (SSAKE) is a genomics application for aggressively assembling millions of short nucleotide sequences by progressively searching for perfect 3'-most k-mers using a DNA prefix tree. SSAKE is designed to help leverage the information from short sequences reads by stringently clustering them into contigs that can be used to characterize novel sequencing targets. Authors are RenÃ© Warren, Granger Sutton, Steven Jones and Robert Holt from the Canada's Michael Smith Genome Sciences Centre. Perl/Linux.
Please note that paired reads need to be in one pseuod fasta line separated by ':'
 
  &gt;readpair:1000
  ACGATAGCTTCG:ACGCGATAGATC
