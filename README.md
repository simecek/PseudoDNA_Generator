# PseudoDNA_Generator

This is an early stage of a tool for generation pseudo-genomic sequences, i.e. DNA-like sequences that are hard to distinguish from DNA coming from a real genome. Currently, it generates sequences that look like intergenomic regions but it can be easily adapted to generate any class of genomic sequences (e.g. protein coding genes).

It consists of two Jupyter notebooks:

  * `Random_Genome_Seqs.ipynb`: prepares a training set for the generator (pick random sequences from intergenomic regions)
  * `PsudoDNA_Generator.ipynb`: based on a training set, generates sequences that look alike sequences from the training set 
