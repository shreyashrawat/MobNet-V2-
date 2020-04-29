# MobNet-V2-
Multi-class image classification 

This repository compares multi-class image classification problem between a created custom model and a pretrained MobNet V2 model.

# Custom Model

The model consisted of 3 CNN layers and various different hyper parameter tuning was tried. The best accuracy, the model could get to was 72% on train set and 62% on test set. You can get the train accuracy of upto 90% by changing the optimizer to Adam but the test accuracy falttens at 55% which is a clear sign of overfitting. Many methods were tried to reduce overfitting like data augmentation and l2 regularizers but there were only successful upto a certain limit.

# MobNet V2

The Google trained MobNet V2 network was trained on 1.4 Million images and numerous classes which provided the base for capturing the features of the images. The top layer was customly created and the accuracy turned out to be 92% on train and 90% on test which outweighed the custom model.

