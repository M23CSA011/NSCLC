# Paper Implementation

This code is based on the work described in the IEEE paper titled ["Genotype-Guided Radiomics Signatures for Recurrence Prediction of Non-Small Cell Lung Cancer"](https://ieeexplore.ieee.org/document/9450726)

## Dataset

The dataset used for this study can be obtained from the following sources:

- NSCLC Dataset: [NSCLC Dataset](https://www.kaggle.com/datasets/silvianz/mydataset/data)
- NSCLC Selected Features: [NSCLC Selected Features](https://www.kaggle.com/datasets/kushal1506/nsclc-selected-features/data)
- NSCLC Gene Data: [NSCLC Gene Data](https://www.kaggle.com/datasets/kushal1506/nsclc-gene-data/data)

## Methodology

The methodology employed in this study consists of the following steps:

1. **ROI Extraction**: Extraction of Regions of Interest (ROI) from selected patient IDs' images and segmentation masks.
2. **Radiomics Feature Extraction**: Extraction of radiomics features from the ROIs.
3. **ResNet Feature Extraction**: Extraction of features using a pre-trained ResNet model.
4. **Radiomics Feature Selection**: Selection of radiomics features using F-Test.
5. **ResNet Feature Selection**: Selection of ResNet features using the Fully Connected (FC) layer.
6. **Gene Selection**: Selection of genes using F-Test.
7. **Gene Estimation**: Estimation of gene expressions.
8. **Recurrence Prediction**: Prediction of recurrence using the selected features.

Each step in the methodology contributes to the overall goal of predicting recurrence in NSCLC patients.

