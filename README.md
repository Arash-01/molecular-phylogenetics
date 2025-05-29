# molecular-phylogenetics
Phylogenetic Analysis of SARS-CoV-2 Spike Gene Variants

Overview:
This project performs a phylogenetic analysis of the spike gene from SARS-CoV-2 and a related virus. The goal is to investigate evolutionary relationships among different variants such as Wuhan, Alpha, Delta, and Omicron, with bat coronavirus used as outgroup.

Workflow:

Sequence Download:
Spike gene sequences were retrieved from NCBI.

Sequence Alignment:
FASTA sequences were aligned using AliView to identify homologous regions.

Model Selection:
The best evolutionary model was determined using jModelTest.

Phylogenetic Tree Construction:
The phylogenetic tree was inferred using Bayesian analysis in MrBayes.

Tree Visualization and Analysis:
The resulting tree was visualized and analyzed in FigTree.



This analysis is based on a workshop I attended, which guided the workflow and tools used.
