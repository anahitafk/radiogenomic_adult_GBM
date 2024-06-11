# Radiogenomics Predictive Models in Adult GBMs

This repository includes the models for prediction of mutations in key driver genes and pathways, described in our paper titled "The Radiogenomic and Spatiogenomic Landscapes of Glioblastoma, and their Relationship to Oncogenic Drivers", by Anahita Fathi Kazerooni, Hamed Akbari, Xiaoju Hu, Vikas Bommineni, Dimitris Grigoriadis, Erik Toorens, Chiharu Sako, Elizabeth Mamourian, Dominique Ballinger, Robyn Sussman, Ashish Singh, Ioannis I. Verginadis, Nadia Dahmane, Constantinos Koumenis, Zev A. Binder, Stephen J. Bagley, Suyash Mohan, Artemis Hatzigeorgiou, Donald M. O’Rourke, Tapan Ganguly, Subhajyoti De, Spyridon Bakas, MacLean P. Nasrallah, Christos Davatzikos. DOI: https://doi.org/10.1101/2022.12.15.517767


## Requirements

- CaPTk v 1.8.1

## Steps to extract features:
1. Conventional MRI Pre-processing and skull-stripping: https://cbica.github.io/CaPTk/preprocessing_brats.html
2. Tumor segmentation: https://cbica.github.io/CaPTk/seg_DL.html
3. DSC-MRI processing: https://cbica.github.io/CaPTk/Perfusion_Derivatives.html
4. DTI processing: https://cbica.github.io/CaPTk/Diffusion_Derivatives.html
5. Perfusion PCA Feature Extractor: https://cbica.github.io/CaPTk/PCA_Extraction.html
6. Radiomic Feature Extraction: https://cbica.github.io/CaPTk/ht_FeatureExtraction.html


## Contact Information:
Anahita Fathi Kazerooni, PhD
The Children's Hospital of Philadelphia & University of Pennsylvania
Email: anahitaf@upenn.edu | fathikazea@chop.edu
