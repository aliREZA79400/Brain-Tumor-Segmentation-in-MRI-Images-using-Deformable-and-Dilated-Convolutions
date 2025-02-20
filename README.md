# Brain Tumor Segmentation in MRI Images using Deformable and Dilated Convolutions

## Overview
[Implementation of this article](https://www.researchgate.net/publication/379717582_Brain_Tumor_Segmentation_in_MRI_Images_using_Deformable_and_Dilated_Convolutions)
This project focuses on rerunning a deep learning-based solution for segmenting brain tumors in MRI images. The approach leverages deformable convolutions and dilated convolutions to improve the model's ability to detect and segment tumors accurately.

## Features
- **Deformable Convolutions**: Allow the network to adaptively adjust the sampling locations, making it more robust to geometric transformations.
- **Dilated Convolutions**: Increase the receptive field of the network, enabling better capture of contextual information.
- **Segmentation**: The model is trained to produce pixel-wise segmentation masks for brain tumors.
- **MRI Images**: The project is designed to work with standard MRI image formats.

## Dataset 
https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation

## Installation
To set up the project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/aliREZA79400/Brain-Tumor-Segmentation-in-MRI-Images-using-Deformable-and-Dilated-Convolutions.git
   
   pip install -r requirements.txt
