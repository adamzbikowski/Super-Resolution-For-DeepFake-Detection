# A Comparison of Different Super-Resolution Models for Improving the Performance of Vision Transformers for Deepfake Image Detection
In this work, we explore the efficacy of three deep learning models for single image super-resolution (SR): a Super-Resolution Convolutional Neural Network (SRCNN), a diffusion-based model (SR3), and a Super-Resolution Generative Adversarial Network (SRGAN).
We aim to assess how these SR techniques affect the accuracy of deepfake detection, comparing their performance against Bicubic Interpolation, a conventional upscaling method.
The classification is done using a state-of-the-art Vision Transformer (ViT).
While our results confirm prior findings on SR performance, we also observe preliminary evidence suggesting that SR techniques could potentially enhance deepfake detection accuracy relative to Bicubic Interpolation.

## Data
1. For SR-model pre-training, the celebahq dataset was used: https://www.kaggle.com/datasets/badasstechie/celebahq-resized-256x256
2. For the deepfake classification task, the DFGC dataset was used. https://github.com/bomb2peng/DFGC_starterkit/tree/master/DFGC-21%20dataset

## Model weights
Due to the models being too large, weights cannot be directly uploaded to GitHub.
Instead, the three SR-models have been uploaded to this google drive folder: (https://drive.google.com/drive/folders/12iiyDnxiGSIrLoggm6vohqQI2b-K0KB_?usp=sharing)
