# GRASP
Repository for the "Golden Gate Assembly for Synthetic PPRs" kit

## Data
onein20.csv — proportion of edited reads for each RNA variant in each well of the plate in the assay
pvariants.tsv — metadata for each protein variant
rvatiants.tsv — metadata for each RNA variant
SS_motifs.tsv — Sequences of 31 aa S motifs (SS motifs as defined in Cheng et al. 2016) with standard fifth-last combinations (TN, NN, TD, ND) extracted from the 1KP dataset reported in Gutmann et al. 2020
composition/selaginella/*.CDS.fasta — edited sequences of Selaginella organellar coding sequences
composition/selaginella/*.targets.csv — extracted sequences of putative PPR binding sites (-4 to -15 regions of editing sites)
composition/angiosperms/*.CDS.fasta — edited sequences of angiosperm organellar coding sequences
composition/angiosperms/*_targets.csv — extracted sequences of putative PPR binding sites (-4 to -15 regions of editing sites)

## Code
Figs4_5A_6A.ipynb — Jupyter notebook in Julia to generate the plots for Figs 4, 5A, 6A
Figs6B_6C.ipynb — Jupyter notebook in Julia to generate the plots for Figs 6B, 6C
composition/selaginella/Selaginella_target_composition.ipynb — Jupyter notebook in Julia to generate the Selaginella panel for Fig 5B
composition/angiosperms/Angiosperm_target_composition.ipynb — Jupyter notebook in Julia to generate the Angiosperm panel for Fig 5B

## Figures
*.svg — generated figures in Scalable Vector Graphics (SVG) format

