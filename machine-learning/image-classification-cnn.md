---
description: image classification and convolutional neural networks
---

# Image Classification \(CNN\)

## Survey Papers / Repos

* Recent Advances in Convolutional Neural Networks [\[1512.07108\]](https://arxiv.org/abs/1512.07108)
* [weiaicunzai/awesome-image-classification](https://github.com/weiaicunzai/awesome-image-classification)

## Resources

* [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/)
* [torchvision](https://pytorch.org/docs/stable/torchvision/index.html): official pytorch toolkit for vision
* [Cadene/pretrained-models.pytorch](https://github.com/Cadene/pretrained-models.pytorch): lots of pretrained models in pytorch
* [albumentations-team/albumentations](https://github.com/albumentations-team/albumentations): lots of augmentation implementations
* [aleju/imgaug](https://github.com/aleju/imgaug): lots of augmentation implementations

## Models

### Convolutions \([\[vdumoulin/conv\_arithmetic\]](https://github.com/vdumoulin/conv_arithmetic) [\[1603.07285\]](https://arxiv.org/abs/1603.07285)\)

* Vanilla Convolution
* 1x1 Convolution [\[1312.4400\]](https://arxiv.org/abs/1312.4400)
* Transpose Convolution [\[1411.4038\]](https://arxiv.org/abs/1411.4038)
* Dilated Convolution [\[1511.07122\]](https://arxiv.org/abs/1511.07122)
* Deformable Convolution [\[1703.06211\]](https://arxiv.org/abs/1703.06211)

### Architectures

* LeNet
* AlexNet
* VGG [\[1409.1556\]](https://arxiv.org/abs/1409.1556)
* GoogLeNet \(Inception v1\) [\[1409.4842\]](https://arxiv.org/abs/1409.4842)
* Inception v2, Inception v3 [\[1512.005677\]](https://arxiv.org/abs/1512.00567)
* ResNet [\[1512.03385\]](https://arxiv.org/abs/1512.03385)
* Inception v4, Inception ResNet [\[1602.07261\]](https://arxiv.org/abs/1602.07261)
* SqueezeNet [\[1602.07360\]](https://arxiv.org/abs/1602.07360)
* WideResNet [\[1605.07146\]](https://arxiv.org/abs/1605.07146)
* DenseNet [\[1608.06993\]](https://arxiv.org/abs/1608.06993)
* ResNeXt [\[1611.05431\]](https://arxiv.org/abs/1611.05431)
* MobileNet [\[1704.04861\]](https://arxiv.org/abs/1704.04861)
* NASNet [\[1707.07012\]](https://arxiv.org/abs/1707.07012)
* SE-ResNet [\[1709.01507\]](https://arxiv.org/abs/1709.01507)
* Res2Net [\[1904.01169\]](https://arxiv.org/abs/1904.01169)
* EfficientNet [\[1905.11946\]](https://arxiv.org/abs/1905.11946)
* HRNet [\[1908.07919\]](https://arxiv.org/abs/1908.07919)

### Loss

* Cross Entropy Loss
* Focal Loss

### Augmentation

* Conventional: Random Crop, ...
* Cutout [\[1708.04552\]](https://arxiv.org/abs/1708.04552)
* AutoAugment [\[1805.09501\]](https://arxiv.org/abs/1805.09501)
* Fast AutoAugment [\[1905.00397\]](https://arxiv.org/abs/1905.00397)
* RandAugment [\[1909.13719\]](https://arxiv.org/abs/1909.13719)

## Others

### Dataset

* [MNIST](http://yann.lecun.com/exdb/mnist/)
* [Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist)
* [CIFAR](https://www.cs.toronto.edu/~kriz/cifar.html)
* [ImageNet](http://www.image-net.org/)
* [Open Images Dataset](https://storage.googleapis.com/openimages/web/index.html)

### Tricks

* Mixup [\[1710.09412\]](https://arxiv.org/abs/1710.09412)
* Pseudo Labeling
* Data Distillation [\[1712.04440\]](https://arxiv.org/abs/1712.04440)

### Task

* Vanilla Image Classification
* Few-shot Image Classification
* Zero-shot Image Classification



