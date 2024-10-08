# What is KAN?

## Kolmogorov-Arnold Networks
##### New class of neural networks aimed to be more less prone to overfitting and more interpretable than multi-layer perceptrons

##### In this experiment we see if KAN can truly outperform MLP in segmentation tasks. I conduct the following experiments:
- Train U-KAN (using KAN) and U-Net (using MLP) architectures on Brats2023 Brain MRI segmentation dataset
- Evaluate U-KAN and U-Net dice similarity performance 
- Evaluate U-KAN and U-Nets sensitivity to sample size and number of epochs
- Evaluate U-KAN and U-Net computational load

<img src='framework-1.jpg' style="height:256px,width:512px">


## Citation
This work is based on the following paper:
```
@article{li2024ukan,
  title={U-KAN Makes Strong Backbone for Medical Image Segmentation and Generation},
  author={Li, Chenxin and Liu, Xinyu and Li, Wuyang and Wang, Cheng and Liu, Hengyu and Yuan, Yixuan},
  journal={arXiv preprint arXiv:2406.02918},
  year={2024}
}
```
