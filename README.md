# Explainable Machine Learning Nanoindentation
Codes to the publication "Explainable machine learning and feature engineering applied to nanoindentation data"  (https://doi.org/10.1016/j.matdes.2025.113897)  published in Materials and Design and Dataset "The High-Speed Steel S390 Microclean™ Nanoindentation Dataset" (https://doi.org/10.5281/zenodo.15639081).

If the code helps you, please cite it using its Zenodo version. Please also consider citing the original publication (https://doi.org/10.1016/j.matdes.2025.113897).

[![DOI](https://zenodo.org/badge/1076176861.svg)](https://doi.org/10.5281/zenodo.17357010)



![Graphical_Abstract](./Graphical_Abstract.jpg)


The repository is structured as follows:

Explainable_Machine_Learning_Nanoindentation/

│

├── Results/

│   ├── cross-validation/

│   │   ├── *.pkl         ➜ **Pickled results from the cross-validation workflow**

│   │   └── *.ipynb       ➜ **Jupyter notebooks for plotting and analyzing Cross-Validation results**

│   │ 

│   ├── models/

│   │   ├── *.pkl         ➜ **Trained Machine Learning models and corresponding SHAP explainers (*https://shap.readthedocs.io/en/latest/*)**

│   │

│   ├── plots/

│   │   └── *.ipynb       ➜ **Notebooks generating SHAP and other explanatory plots**

│

├── Supervised Machine Learning Pipelines/

│   └── *.ipynb           ➜ **Cross-validation and model training pipelines**

│

├── *k*-means/

│    └── *.ipynb          ➜ **Clustering analysis using *k*-means**

C.O.W. T. gratefully acknowledges the financial support under the scope of the UFO program (SPM - PN 3022) by the Austrian State of Styria (Land Steiermark - Abteilung 12 Wirtschaft, Tourismus, Wissenschaft und Forschung). 

![Graphical_Abstract](./Logo.jpg)
    













