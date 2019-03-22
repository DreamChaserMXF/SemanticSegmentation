# Semantic Segmentation, Papers and Insights

1. FCN, Fully Convolutional Networks for Semantic Segmentation[[pdf](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Long_Fully_Convolutional_Networks_2015_CVPR_paper.pdf)][[code](https://github.com/shelhamer/fcn.berkeleyvision.org)]

>Long, Jonathan, Evan Shelhamer, and Trevor Darrell. "Fully convolutional networks for semantic segmentation." Proceedings of the IEEE conference on computer vision and pattern recognition. 2015.

![FCN](img/FCN/FCN_1_FC2FC.png)
![FCN](img/FCN/FCN_2_FusionAndUpscaling.png)
![FCN](img/FCN/FCN_3_32s_16s_8s.png)

Insight:

* Treat fully connected layer as convolutional layer, so as to accept an image in random resolution as input to the network.
* Interleave the processes of feature combination and upscaling, in order to improve spatial detail.
