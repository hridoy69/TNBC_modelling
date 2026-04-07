# TNBC_modelling
An Explainable Machine Learning Framework for Identifying Potential Inhibitors in Triple-Negative Breast Cancer

# About
This study presents an interpretable machine learning driven virtual screening-based framework to identify potential inhibitor against TNBC from the medicinal plants of Northeast India. A curated dataset of 4414 bioactive compounds targeting eight TNBC cell lines was obtained from ChEMBL, and molecular features were generated using RDKit descriptors and different molecular fingerprints. Sixteen ML models were developed using four boosting algorithms i.e. Adaboost, CatBoost, XGBoost and Explainable Boosting Machine. 

Among all these models, CatBoost and XGBoost with MACCS keys demonstrated the best performance in terms of F1 scores up to 0.88 during 10-fold cross-validation and hold-out test set evaluation. A total of 1313 phytochemicals associated with medicinal plants of Northeast India were screened through these models, of which 75 were predicted active across all the eight TNBC cell lines. 

# Molecular modelling
These 75 compounds were subjected to ADMET and virtual screening against four TNBC targets – VTCN1, FABP7, PARP1 and GABRP resulting into five lead compounds: Javanicins U, Horhammericine, Clauslactone A, Clauslactone B and Spartioidine. Molecular dynamics simulation over 100 ns demonstrated that PARP1 and FABP7 complexes showed stable binding (RMSD: 0.1-0.3 nm), supported by favourable hydrogen bonding and compactness profiles. SASA and RMSF analyses suggested ligand-induced conformational effects, particularly in FABP7. Binding free energy calculations using MM/PBSA further confirmed strong and stable interactions of these ligands, especially with PARP1 and FABP7 (ΔG_bind up to −115.63 kJ/mol).
