# Arterial-Vessels-U-Net

This repository contains all the code for our paper "Investigating the impact of pulmonary arterial vessel diameter on U-Net segmentation accuracy during early-stage training." This includes the U-Net architecture, statistical analysis tests, and figures.

**Dataset**

All of our data was obtained from research conducted by Sinitca et al. The original study can be found below: 

Sinitca, Aleksandr M., et al. “Microscopy Image Dataset for Deep Learning-Based Quantitative Assessment of Pulmonary Vascular Changes.” Scientific Data, vol. 11, 15 June 2024, https://doi.org/10.1038/s41597-024-03473-z. 


**Software**

All training and model development were completed using the following tools and libraries: 
- Google Colab using Python 3.11.13 for most training and model development 
- Keras’s API within TensorFlow 2.18.0 for the U-Net's architecture 
- scikit-image, OpenCV2, and PIL for image preprocessing
- Matplotlib 3.10.0 and Seaborn 0.13.2 for data visualizations
- NumPy and scikit-learn for numerical computations
- scipy, statsmodels, and pingouin for statistical analyses
 
