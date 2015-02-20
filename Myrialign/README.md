# Myrialign

Software to align short reads produced by a short read genome sequencer to a reference genome. Alignments can contain any number of SNPs, insertions and deletions, up to a user specified cutoff. Myrialign can use a Cell Broadband Engine processor to accelerate alignments if available, for example on a PlayStation 3 running GNU/Linux.
Myrialign performs brute force alignment using a variant on the "bitap" algorithm that aligns several thousand reads to a reference in parallel. It uses bit-parallelism, multiple processors, and Cell SPUs if available.
Unlike other reference genome alignment software, heuristics and hashtable lookups are not used. Myrialign will find alignments with any number of errors up to a user specified cutoff. The emphasis is on doing a 100% accurate search as fast as is possible.
