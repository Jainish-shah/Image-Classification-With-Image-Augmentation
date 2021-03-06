# Image-Classification-With-Image-Augmentation

Cause for using image augmentation is that CNN is used to recognize images in particular and for smaller dataset CNN starts memorizing the images, which leads to `overfitting`.To avoid overfitting of the model, some of the techniques that can be applied are Image augmentation, dropout and check using validation dataset.

**Image Augmentation** is used to create new training images by applying number of random image transformation to images in the original training set. Some of the image augmentation techniques that can be applied are:
- Flipping the image horizontally
- Rotating the image
- Applying Zoom

Second, most used method is dropout to avoid Image augmentation. **Dropout** consist of randomly training off some neurons during training, which force the other neurons to slack and to take a more active part in training. 

And finally to check that the model is working good or not, by applying the model on Validation dataset (as validation dataset consist of images that are not used for tuning weights and biases of training set).

So the goal is that at training time, your model will never see the exact same picture twice. This exposes the model to more aspects of the data, allowing it to generalize better.
[Colab](https://colab.research.google.com/drive/10rKJTxyFW694_hJjSnCmRB2aneXcG3V3?usp=sharing)
