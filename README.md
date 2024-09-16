# Oxytocin receptor controls distinct components of pair bonding and development in prairie voles

## Publication [link TBD]
## Abstract:
Across species, including humans, enduring attachment between individuals is one of the most profound and intriguing forms of social relationships. Signaling via the oxytocin receptor influences attachment behaviors in multiple species, including pair bonding in socially monogamous prairie voles. Pair bonding comprises distinct behavior modules: preference for a bonded partner, and rejection of novel potential mates. How oxytocin signaling regulates specific components of social attachment and the neural mechanisms mediating these behaviors remains unknown. Oxtr facilitates affiliative behaviors by influencing reciprocal interactions between novel partners and suppressing promiscuity towards novel potential mates following pair bonding. Oxtr function sex-specifically regulates coordinated patterns of gene expression in regions implicated in attachment behaviors and regulates the expression of oxytocin and other genes in the paraventricular nucleus of the hypothalamus, a principal source of oxytocin. Thus, Oxtr regulates genetically separable components of pair bonding behaviors and coordinates development of the neural substrates of attachment. 

## This repository contains:
  1. Pre-processing information (multiqc_report.html)
  2. Input data from star (input_data/trim_star2.7.3a_merged_counts*)
  3. Input data from picard (input_data/merged_qc.txt)
  4. Gene lists used for enrichment analyses (input_data/gsea/)
      - NOTE: The GSE132730_subset_cca_to_velo.rds object is too large to host. You will need to download that from [GEO here](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE132730)
  5. /results contains all figures, DEX lists, and GO lists created by the DEX_analysis.Rmd script.
