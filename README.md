# Reconstruction-of-passion-fruit-tree-branches
## Overview
In this study, our ultimate goal is to develop a branch reconstruction algorithm for applications such as fruit harvesting, tree pruning, and growth monitoring in fruit trees. The golden passion fruit tree images used in this study were captured in September 2021 from an orchard located in Liutang Town, Guilin City, Guangxi Province, China. An Intel RealSense D455 depth camera was used to capture images with a resolution of 1280×720 pixels. In Figure 1(a), the distance between the camera and branches was approximately 0.3 to 0.5 m. To achieve diversity of samples, these images were captured at three different time points: 09:00, 14:00, and 16:00. In total, 133 images were captured.

![fig1](/images/FIGURE1.png)


## Dataset annotation and augmentation
In the orchard environment, the growth posture of passion fruit branches is random, to better identify and reconstruct the branches, in this study, we adopted the labeling method proposed by Yang et al. [19] to represent randomly growing branches with regular-shaped quadrilaterals, which effectively reduces the complexity of detecting the original branches. Figure 2 shows the effect of image annotation. To better represent a branch, the aspect ratio of the quadrilateral was set in the range of 2 to 4, and a smaller quadrilateral mark was used for branches with a larger curvature.

Data augmentation on the original dataset can increase the diversity and robustness of the experimental dataset. Considering the actual interference factors of the natural environment, several processes were used in the augmentation including adding noise, adding blur, mirror flip, rotating, adjust image brightness, etc.. By performing the augmentation described above, a dataset containing 1742 images was created and used to train and test the Mask R-CNN model.
![fig2](/images/FIGURE2.png)

## Downloads
The passion-fruit-tree-branches dataset and annotations can be downloaded through Baidu Cloud:

    Link: https://  
    password：

## License
The dataset is available to download for commercial/research purposes under a Creative Commons Attribution-ShareAlike 4.0 International License. The copyright remains with the original owners of the images.


## Citation
    
