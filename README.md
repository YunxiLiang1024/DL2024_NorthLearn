# DL2024_NorthLearn
## Introduction
To achieve this, this project first implemented the neural style transfer in paper “A Neural Algorithm of Artistic Style” (Gatys et al., 2016) by  leveraging Convolutional Neural Networks to create a model that transfers visual styles to images. While traditional neural style transfer methods often apply a single style globally to an image, we created a model that allows for the fusion and transfer of multiple artistic styles. Also, a face recognition algorithm was added to achieve the goal of localized multi-style transfer to human faces specifically. We adapted the source code which is in PyTorch into TensorFlow. 
The project achieved the following goals:
1. Implement the basic neural style transfer method in Gatys et al. (2016)
2. Implemented multi-style transfer and partial face transfer separately
3. Combined multi-style transfer and partial face transfer 
4. Performed ablation experiments by comparing model performance with different content layers

## Dataset
Style images and human face images are obtained from Kaggle: “Art Images: Drawing/Painting/Sculptures/Engravings” (link: https://www.kaggle.com/datasets/thedownhill/art-images-drawings-painting-sculpture-engraving) and “Human Faces" (link: https://www.kaggle.com/datasets/thedownhill/art-images-drawings-painting-sculpture-engraving)

## Loss
Training curves for single and multi style transfer loss:
<img width="596" alt="image" src="https://github.com/YunxiLiang1024/DL2024_NorthLearn/assets/119365293/563059e7-1897-489d-93d5-5a33c3b72e56">

