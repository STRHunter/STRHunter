# STRHunter
A fast and memory efficient STR identification tool
One of the major challenges with Bioinformatics software is that the size and complexity of datasets 
increasingly demand elegant computing speed with highest level of accuracy. To overcome the problem of 
computational complexity, a plethora of algorithms has been appeared that can provide a ‘good enough’ or 
an 'approximate' solution to many biological problems. However, in some instances like identification 
of Short Tandem Repeat(STR) loci, where an 'approximate' solution may not be sufficient enough to portray 
results in population genetics, phylogenetics and forensics, which require accurate detection of STR loci 
to calculate intra- and inter-species interactions. The current work presents an efficient and exhaustive 
algorithm called STRHunter, which is 100\% accurate in identification of STR loci from DNA sequence of 
any length. Series of experiments, both on simulated and real datasets, show that it is several time 
faster than existing algorithms and requires lesser computation memory. To identify more biologically 
pertinent STRs, we also developed several filters which allow users to view required subset of STRs in 
an easy-to-use manner. Thus, STRHunter, coupled with the filter options, accuracy and speed of computation 
can play an important role for in-silico identification of STR loci in long DNA sequences. 
******************************************************************************************
Here we present an efficient algorithm, called STRHunter, based on k-mer decomposition approach to identify all STR loci present in a given DNA sequence, efficiently and accurately. STRHunter is several time faster than currently existing methods while being 100\% accurate, comprehensive and memory-efficient. Unlike most other methods, our algorithm does not miss overlapping repeats, and repeats that end in the middle of the motif. In addition, STRHunter can also detects flanking DNA of user specified length in both the 5' and 3' sides of STR loci.
