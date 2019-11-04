# Thesis
## Development and Validation of Pharmacoinformatic Similarity-based Tools for Safety Assessment of Chemicals 

### thesis_environment.yml:
Thesis Conda environment to be installed for running the Jupyter notebooks. To install the Jupyter notebooks first install the Conda environment follow the instructions written in Flame github (https://github.com/phi-grib/flame). When you are going to create the conda environment with all the dependencies and extra packages (numpy, RDKit...), instead of using the flame environment.yml provided, replace the flame environment.yml with the one we provided (thesis_environment.yml), which assures us to use all the versions of the programs we used. Nevertheless, if you want to use the last versions released of whole programs, just install flame as it is and then install the other ones.


### Training and Validations Sets.xlsx: 
This file contains the training and validation sets used in this thesis.

## Similarity RA part:

### Unsuperviserd_RA.ipynb:
Jupyter notebook for running Unsupervised Read Across with different similarity metrics

### Superviserd_RA.ipynb:
Jupyter notebook for running Supervised Read Across with different similarity metrics

### Radial_Plots.ipynb:
Jupyter notebook for creating radial plots with similarity predictions

## QSAR models part:

### Annex_Thesis_Tables.xlsx: This file contains 7 tables described below.

- S1 Table. Cross-validation statistics of AE models. Detailed cross-validation statistics including other AEs not satisfying quality requirements as well as models built under non-conformal framework.

- S2 Table. PLS AE scores. Higher PLS scores correspond to AEs more related to DILI outcome.

- S3 Table. Real AEs and DILI correlation matrix. Correlation between adverse effects and DILI outcome. Compounds present in both SIDER and DILI labeled datasets.

- S4 Table. Predicted AEs and DILI correlation matrix. Correlation between predicted adverse effects and DILI outcome. Compounds do not present in SIDER.

- S5 Table. QSAR DILI models performance. Includes quality statistics for DILI QSAR models built using the DILI databases considered in this work. The external validation for a given model is calculated by the prediction of DILI in remaining datasets.

- S6 Table. Inconsistent DILI labelling. Includes compounds with different assigned DILI outcome in DILIrank and mulliner datasets.

- S7 Table. Model documentation. Includes detailed information on the models built in this work.

### build_AEs_models.ipynb: 
Jupyter notebook for building the Adverse Effects Models

### predict_DILI.ipynb: 
Jupyter notebook for Running AEs models and make predictions with the optimization consensus rule.

### Metamodels.ipynb:
Jupyter notebook For building the expert models and make predictions.

