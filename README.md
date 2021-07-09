# Image-Classification-With-Image-Augmentation

Cause for using image augmentation is that CNN is used to recognize images in particular and for smaller dataset CNN starts memorizing the images, which leads to `overfitting`.To avoid overfitting of the model, some of the techniques that one can apply are Image augmentation, dropout and check using validation dataset.

Image Augmentation is used to create new training images by applying number of random image transformation to images in the original training set. Some of the image augmentation techniques that can be applied are:
- Flipping the image horizontally
- Rotating the image
- Applying Zoom

So the goal is that at training time, your model will never see the exact same picture twice. This exposes the model to more aspects of the data, allowing it to generalize better.
[Colab](https://colab.research.google.com/drive/10rKJTxyFW694_hJjSnCmRB2aneXcG3V3?usp=sharing)
