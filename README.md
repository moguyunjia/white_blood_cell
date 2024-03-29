# WBC-AMNet: Automatic classification of WBC images using deep feature fusion network based on focalized attention mechanism
Ziyi Wang,Jiewen Xiao,Jingwen Li,Hongjun Li ,Luman Wang 
## Abstract
The recognition and classification of White Blood Cell (WBC) play a remarkable role in blood-related diseases (i.e., leukemia, infections) diagnosis. For the highly similar morphology of different WBC subtypes, it is too confused to classify the WBC effectively and accurately for visual observation of blood cell smears. This paper proposes a Deep Convolutional Neural Network (DCNN) with feature fusion strategies, named WBC-AMNet, for automatically classifying WBC subtypes based on focalized attention mechanism. To obtain more localized attention of CNN, the fusion features of the first and the last convolutional layer are extracted by focalized attention mechanism combining Squeeze-and-Excitation (SE) and Gather-Excite (GE) modules. The new method performs successfully in classifying monocytes, neutrophils, lymphocytes, and eosinophils on the complex background with an overall accuracy of 95.66%, better than that of general CNNs. The multi-classification accuracy of WBC-AMNet with the background segmentation is over 98% in all cases. In addition, Gradient-weighted Class Activation Mapping (Grad-CAM) is employed to visualize the attention heatmaps of different feature maps.
## Data avaliable 
https://github.com/wzy0730/minimal-dataset
## DOI
https://doi.org/10.1371/journal.pone.0261848
