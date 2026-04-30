# Emphysema CT Classification with Visual–Topological Deep Learning

This repository contains the dataset and source code for a patient-level emphysema classification study using chest CT images.

## Study Overview

This study focuses on automated emphysema classification from chest CT images. The dataset contains 1108 anonymized CT images, where each image corresponds to a unique patient.

The images are categorized into four classes:

- Normal
- Panlobular emphysema
- Paraseptal emphysema
- Centroacinar emphysema

The study evaluates both four-class emphysema subtype classification and binary Normal-versus-Emphysema classification.

The proposed framework combines visual features extracted from modern vision transformer models with topological features derived from persistent homology. In particular, DINOv2 visual embeddings are fused with Betti-curve features using a cross-attention-based fusion model.

