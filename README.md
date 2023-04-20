# CSE-6250 Final Project
This repository contains the replication code for paper "Statistical supervised meta-ensemble algorithm for medical record linkage" (Kha Vo, Jitendra Jonnagaddala, Siaw-Teng Liaw).
The code was developed in Python 3.9. The following libraries were used: pandas, recordlinkage, numpy, sklearn, matplotlib.
To reproduce this work you need to follow these steps:
1. Load and preprocess datasets by using febrl_dataset_preparation.ipynb (Scheme A) and ePBRN_synthetic_datasets_reproduction.ipynb (Scheme B) notebooks that are located in code folder.
As a result, datasets will be created in the folder data.
2. To train base and ensemble learners and save results use febrl_linkage.ipynb (Scheme A) and ePBRN_linkage.ipynb (Scheme B) notebooks that are located in code folder.
Thus, the results will be saved in a folder output in text and image format.
