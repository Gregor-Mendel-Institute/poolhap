# PoolHap

Computational tool for inferring haplotype frequencies from pooled samples

## Background
With the advance of next-generation sequencing (NGS) technologies, increasingly ambitious applications are becoming feasible. A particularly powerful one is the sequencing of polymorphic, pooled samples. The pool can be naturally occurring, as in the case of multiple pathogen strains in a blood sample, multiple type of cells in a cancerous tissue sample, or multiple isoforms of mRNA in a cell. In these cases, it difficult or impossible to partition the subtypes experimentally before sequencing, and those subtype frequencies must hence be inferred. In addition, investigators may occasionally want to artificially pool the sample of a large number of individuals for reasons of cost-efficiency, e.g., when carrying out genetic mapping using bulked segregant analysis. Here is the wiki page of PoolHap for a computational tool for inferring haplotype frequencies from pooled samples. It is for myself and potential collaborators. Hopefully this method could facilitate greater biological insight into heterogeneous samples that are difficult or impossible to isolate experimentally. 

PoolHap is composed of two main parts: 

* The first part is to infer the haplotype frequencies based on known haplotypes. This is the case for our field experiments, RNA-Seq experiments. We have a paper in press: PoolHap paper: haplotype-known part
* The second part is to infer the frequencies with unknown haplotypes. We use MCMC sampling strategy to "guess" the optimal haplotype configurations. This part is still not mature enough for publication. 

The User Manual can be found here and the actual programm can be found here.
