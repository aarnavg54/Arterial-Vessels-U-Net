# Arterial-Vessels-U-Net

This repository contains all the code for our paper "Investigating the impact of pulmonary arterial vessel diameter on U-Net segmentation accuracy during early-stage training." It includes the U-Net architecture, statistical analysis tests, and figures.

**Abstract**

Deep learning models have significantly advanced the field of medical image segmentation. Despite this progress, **pulmonary arterial vessels** are difficult to segment due to their intricate structures and subtle features. Studies have shown that understanding how specific image characteristics influence model performance can optimize segmentation accuracy. Thus, we sought to investigate the relationship between **arterial vessel diameter** and **segmentation accuracy** during early-stage model training. We hypothesized a positive correlation between the two variables because larger vessels tend to stand out more with their highly differentiable boundaries compared to smaller ones. Here, we trained and fine-tuned a U-Net model to segment the arterial vessels from **609 histology slides** of male Wistar rats with idiopathic pulmonary arterial hypertension (**iPAH**) and chronic thromboembolic pulmonary hypertension (**CTEPH**). We evaluated its performance based on two accuracy measures: intersection over union (**IoU**) and dice similarity coefficient (**DSC**). We categorized the diameter sizes into three groups (small, medium, and large) and found statistically significant (**p < 0.05**) differences among their respective outcomes. Ultimately, we discovered a **moderate positive correlation** between diameter and segmentation performance. That is, large vessels were typically segmented with greater accuracy than small and medium ones. Our findings provide novel insight into the structural effects of arterial vessels on U-Net performance. Moreover, this approach can be altered to suit applications in various other fields to understand training dynamics.


**Dataset**

All of our data was obtained from research conducted by **Sinitca et al**. The original study can be found below: 

Sinitca, Aleksandr M., et al. “Microscopy Image Dataset for Deep Learning-Based Quantitative Assessment of Pulmonary Vascular Changes.” Scientific Data, vol. 11, 15 June 2024, https://doi.org/10.1038/s41597-024-03473-z. 


**Software**

All training and model development were completed using the following tools and libraries: 
- **Google Colab** using **Python 3.11.13** for most training and model development 
- Keras’s API within **TensorFlow 2.18.0** and **Scikit-learn 1.6.1** for the U-Net's architecture 
- **Scikit-image 0.25.2**, **cv2 4.11.0**, and **PIL 11.2.1** for image preprocessing
- **Matplotlib 3.10.0** and **Seaborn 0.13.2** for data visualizations
- **NumPy 2.02** and **Pandas 2.2.2** for numerical computations
- **Scipy 1.15.3**, **Scikit_posthocs 0.11.4**, and **Pingouin 0.5.5** for statistical analyses
 
