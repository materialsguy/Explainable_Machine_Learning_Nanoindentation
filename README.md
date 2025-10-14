# XAI-Nanoindentation
Codes to the publication "Explainable machine learning and feature engineering applied to nanoindentation data"  (https://doi.org/10.1016/j.matdes.2025.113897)  published in Materials and Design and Dataset "The High-Speed Steel S390 Microclean™ Nanoindentation Dataset" (https://doi.org/10.5281/zenodo.15639081).

The repository is structured as follows:

├── Results/

│   ├── /cross-validation/

│     └── *.pkl The pickled Results of the Cross Validation Workflow shown in the folder Supervised Machine Learning Pipelines

│     └── *.ipynb Codes to plot the Results

│   ├── /models/

│     └── *.pkl The pickled best supervised Machine Learning Model and its corresponding SHAP explainer

│   ├── /plots/

│     └── *.ipynb The codes to generate SHAP plots and other analyses in the paper.

├── Supervised Machine Learning Pipelines/
  └── *.ipynb Cross Validation Pipelines.

├── k-means/
  └── *.ipynb Notebooks showing the application of the k-means clustering













