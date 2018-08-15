swift-blast
===========

Parallel sequence alignment using BLAST, the Swift parallel scripting system, and split and merge tools from Caltech.

Example of workflow invocation:

$ swift -config swift.conf blast.swift -d=testDB -i=sequence.seq -n=64

This uses the fastasplitn and blastmerge tools from David Mathog's parallelblast package:

http://saf.bio.caltech.edu/pub/software/molbio/parallelblast_2.0.9.tar.gz

Reference:

David R. Mathog. Parallel BLAST on split databases. Bioinformatics (2003) 19(14): 1865-1866. doi:10.1093/bioinformatics/btg250.
