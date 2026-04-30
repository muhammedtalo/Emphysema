# Emphysema CT Classification with Visual–Topological Deep Learning

This repository contains the dataset and source code for a patient-level emphysema classification study using chest CT images.

The study evaluates automated emphysema classification using modern vision transformer models and topological deep learning features. The main framework combines DINOv2-based visual embeddings with persistent-homology-derived Betti-curve features using a cross-attention fusion model.

The CT images are located in the [Dataset](Dataset) folder.

## Running Order of Notebooks

1. [Segmentation.ipynb](Segmentation.ipynb): This notebook performs lung-focused preprocessing, masking, and cropping of CT images.

2. [Topo_extractor.ipynb](Topo_extractor.ipynb): This notebook extracts topological features from CT images using persistent homology and Betti curves.

3. [Four_class_classification.ipynb](Four_class_classification.ipynb): This notebook performs four-class emphysema classification.

4. [Binary_classification.ipynb](Binary_classification.ipynb): This notebook performs binary classification by merging all emphysema subtypes into a single emphysema class.


