# Simple-SSD-Pytorch

This repo contains code for training SSD from scratch and performing Inference. 

Entire SSD code is inside a single notebook . This notebook is build for Education and understanding purpose.

## Dataset

We are using pascal voc 2007 dataset

### Table of Content

1. Import statements
2. Download the PASCAl VOC 2007 Dataset
3. Transformations

   1. Horizontal Flip

   2. Resize

   3. Photometric Distortion
4. Dataset
5. Visualization of Augmentation and Original
6. Utility Function
    	1. Cordinate conversion (Encoding-Decoding)
    	2. Jacard Overlap(IoU)
    	3. Average Meter (Calculating running average)
    	4. Save Checkpoint
    	5. Decimate

7. Model Architecture
8. VGG Base
9. AuxiliaryConvolutions
10. Prediction Convolution
11. SSD 300
12. MultiBox Loss Function
13. Training
     	1. Learning Parameters
     	2. DataLoader
     	3. Train method
     	4. Validate method
     	5. Actual training
14. Detection
15. Inference



## Result

Model is currently in training mode once training is done results will be updated