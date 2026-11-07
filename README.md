# TS-BFS-BS_EGFR

Directory and File Naming Conventions

The filenames and directory names used in this repository follow a consistent convention to indicate the experimental condition, cell type, network prior, and analysis parameters.

Normal denotes datasets derived from EGF-stimulated MDA-MB-468 cells under the untreated control condition.

SHP2i denotes datasets derived from MDA-MB-468 cells treated with an SHP2 (PTPN11) inhibitor and subsequently stimulated with EGF.

Washout denotes datasets derived from cells subjected to the SHP2 inhibitor washout procedure described in the manuscript and subsequently stimulated with EGF.

HEK293T denotes datasets associated with the EGFR Flp-In HEK293T cell system.

HeLa denotes datasets associated with HeLa cells.

All primary analysis inputs originate from the JSON files located in the SOURCE_DATA directory. In some cases, otherwise identical JSON input files are assigned the prefixes functional, physical, or regulatory solely for convenience in organizing and generating downstream output files. These prefixes do not indicate differences in the underlying phosphoproteomic input data. Rather, they identify the STRING network prior used during the corresponding analysis.

Directory names encode the principal analysis parameters and experimental settings. The meaning of each directory can therefore be inferred from the parameter labels included in its name.

For questions regarding the datasets, directory structure, parameter settings, or analysis procedures, please contact the authors.


# Directories

#100-300-300-700

 H=100, Ks=300 Kt=300 Tau=700 (R=5 Q=3)
 -experiments\ Normal- CBL-SRC, Normal-PTPN, Normal-Random, functional, physical, regulatory 
 -functional\ HEK293T, HELA, Normal, SHP2i, Washout 
 -physical\  HEK293T, HELA, Normal, SHP2i, Washout 
 -regulatory\  HEK293T, HELA, Normal, SHP2i, Washout 
 -R&Q\Normal R=3,5,10: Q=1,3,5
 
#100-150-150-700

H=100, Ks=150 Kt=150 Tau=700 (R=5 Q=3)

#100-300-300-400

H=100, Ks=300 Kt=300 Tau=400 (R=5 Q=3)

#100-300-300-700_D=2

H=100, Ks=300 Kt=300 Tau=700 (R=5 Q=3) D=2

#100-300-300-900

H=100, Ks=300 Kt=300 Tau=900 (R=5 Q=3)

#100-600-600-700

H=100, Ks=600 Kt=600 Tau=700 (R=5 Q=3)

#100-900-900-700_D=2

H=100, Ks=900 Kt=900 Tau=700 (R=5 Q=3) D=2

#200-300-300-700

H=200, Ks=300 Kt=300 Tau=700 (R=5 Q=3)

#150-300-300-700

H=150, Ks=300 Kt=300 Tau=700 (R=5 Q=3)

#150-500-500-700

H=150, Ks=500 Kt=500 Tau=700 (R=5 Q=3)

#50-300-300-400

H=50, Ks=300 Kt=300 Tau=400 (R=5 Q=3)

#50-300-300-700

H=50, Ks=300 Kt=300 Tau=700 (R=5 Q=3)

#50-300-300-700_D=2

H=50, Ks=300 Kt=300 Tau=700 (R=5 Q=3) D=2

#50-300-300-700_R&Q

H=50, Ks=300 Kt=300 Tau=700 (R=3,5,10 Q=1,3,5)

#50-300-300-700_exp

H=50, Ks=300 Kt=300 Tau=700 (R=5 Q=3)

#50-300-300-900

H=50, Ks=300 Kt=300 Tau=900 (R=5 Q=3)

#50-900_900-700_D=2

H=50, Ks=900 Kt=900 Tau=700 (R=5 Q=3) D=2

#Additional_parameters_check

#Json_c=0.4

#Json_c=0.6

#SOURCE_DATA

#SOURCE_CODES
