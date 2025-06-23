## Papers and preprints
### Challenges in using neural networks for recognizing anthropogenic objects with varying contours
**Authors**: Saidov A., Zhukov D.

**Status**: Under review at "Geodesy and Cartography"

**Abstract**: The study analyzes the effectiveness of semantic segmentation and instance segmentation methods for
identifying anthropogenic objects with varying degrees of boundary variability in aerospace imagery. Neural
network models such as U-Net, PSPNet, DeepLabv3+, SegFormer, Twins-PCPVT, ConvNeXt, YOLOv7,
YOLOv8, YOLOv9, and YOLOv11 are utilized.
The research involves annotating remote sensing data to determine the degree of boundary variability, conducting
experiments with neural networks, and developing an algorithm to compare the performance of networks
belonging to different segmentation types.
The results demonstrate that semantic segmentation models are more effective for detecting large-area objects with
pronounced boundary variability, while instance segmentation models achieve high recognition accuracy for
objects with minimal boundary variability

**Keywords**: semantic segmentation, instance segmentation, aerospace imagery, deep learning, metrics, dataset 

**Language**: ru

**Date**: 04.2025

**Journal**: preprint

**Link**: [PDF](Saidov_preprint_2025_segmentations.pdf)  

----
### Training a YOLOv8 on a limited dataset for recognizing anthropogenic objects with distinct textures in satellite imagery
**Authors**: Zhukov D., Saidov A., et al.

**Status**: Under review

**Abstract**: The article describes the successful experience of training a neural network YOLOv8 on a limited amount 
of training data. The problem being solved was the possibility of identifying warehouses with unique geometric 
characteristics of shipping containers on high-resolution color three-channel satellite images. A total of 109 images 
with 1017 labels were used to train the neural network. Optimal hyper parameters for learning were selected by 
organizing an interactive process based on a genetic algorithm. The problem of erroneous recognition of false targets 
was solved by adding unlabeled images to the original dataset. As a result of the work carried out, а neural network 
model with an AP index of 0,86 was formed.

**Keywords**: instance segmentation, satellite imagery, limited training data, dataset, anthropogenic object, hyperparameter optimization, false positive reduction 

**Language**: ru

**Date**: 06.2025

**Journal**: preprint

**Link**: [PDF](Zhukov_Saidov_preprint_limited_dataset_texture.pdf)  
