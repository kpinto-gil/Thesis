# Thesis
Development and validation of pharmacoinformatic similarity-based tools for safety assessment of chemicals 
**Annex_Thesis_Tables.xlsx: This file contains 7 tables described below.

-- S1 Table. Cross-validation statistics of AE models. Detailed cross-validation statistics including other AEs not satisfying quality requirements as well as models built under non-conformal framework.
-- S2 Table. PLS AE scores. Higher PLS scores correspond to AEs more related to DILI outcome.
-- S3 Table. Real AEs and DILI correlation matrix. Correlation between adverse effects and DILI outcome. Compounds present in both SIDER and DILI labeled datasets.
S4 Table. Predicted AEs and DILI correlation matrix. Correlation between predicted adverse effects and DILI outcome. Compounds do not present in SIDER.
-- S5 Table. QSAR DILI models performance. Includes quality statistics for DILI QSAR models built using the DILI databases considered in this work. The external validation for a given model is calculated by the prediction of DILI in remaining datasets.
-- S6 Table. Inconsistent DILI labelling. Includes compounds with different assigned DILI outcome in DILIrank and mulliner datasets.
-- S7 Table. Model documentation. Includes detailed information on the models built in this work.

**Training and Validations Sets.xlsx: This file contains the training and validation sets used in this thesis.
**build_AEs_models.ipynb: for building the Adverse Effects Models
**predict_DILI.ipynb: for Running AEs models and make predictions with the optimization consensus rule.
**Metamodels.ipynb: For building the expert models and make predictions.

