# [Do CNNs Encode Augmentations?](https://arxiv.org/pdf/2003.08773.pdf)
By Dr. Eddie Yan and Dr. Yanping Huang

#### This is an unofficial tensorflow implementation of the above paper by [Sourav Sharan](https://github.com/SouravSharan) and me. 
###### The code implementation can found in the form of a jupyter notebook.

## Absract

Data augmentations are important ingredients in the recipe for training robust neural networks, especially in computer vision. A fundamental question is whether neural network features encode data augmentation transformations. To answer this question, we introduce a systematic approach to investigate which layers of neural networks are the most predictive of augmentation transformations. Our approach uses features in pre-trained vision models with minimal additional processing to predict common properties transformed by augmentation (scale, aspect ratio, hue, saturation, contrast, and brightness). Surprisingly, neural network features not only predict data augmentation trans- formations, but they predict many transformations with high accuracy. After validating that neural networks encode features corresponding to augmentation transformations, we show that these features are encoded in the early layers of modern CNNs, though the augmentation signal fades in deeper layers.

In case of any required changes, feel free to open a pull request or contact us over mail at:
banerjee.rohan98@gmail.com or
souravthesharan@gmail.com.

