# UNet

[UNET](https://arxiv.org/abs/1505.04597) was developed by Olaf Ronneberger, Philipp Fischer, and Thomas Brox for medical image segmentation.
The original paper presents the following architecture 

![UNet](images/unet.png)

## References

- [Understanding Semantic Segmentation with UNET](https://towardsdatascience.com/understanding-semantic-segmentation-with-unet-6be4f42d4b47)
- [U-Net For Segmenting Seismic Images With Keras](https://www.depends-on-the-definition.com/unet-keras-segmenting-images/)
- [Up-sampling with Transposed Convolution](https://towardsdatascience.com/up-sampling-with-transposed-convolution-9ae4f2df52d0)

## Todo

1. Current implementation is based on original UNet paper and accepts BW images only.
   Input layer needs to be of shape (572, 572, 3) to accept RGB images.
   Output image is BW so the transition from RGB to BW needs to happen somewhere inside the network.
2. Loss function needs to be implemented. Also other metrics might be handy.
3. Score method for the UNet class needs to be implemented.
4. Prediction method for the UNet class needs to be implemented.
