# Transfer_Learning
Build a customized classifier on top of a pretrained models such as Resnet or MobileNet

### Introduction
[OpenImages dataset](https://storage.googleapis.com/openimages/web/index.html) is a huge dataset with more than roughly 20000 category for Image Classification.
What if you are not interested in all categories, and you just want to train/evaluate your model in your desired classes. You need to use the transfer learning to do so. You use a pretrained model such as Resnet etc. as your backbone and build your own customized classifier in the last layer.

### Download your desired class
If you need to train your model on your desired class, there is a way to just download your desired classes from OpenImages.
You can use this [repositary - OIDv4 ToolKit](https://github.com/EscVM/OIDv4_ToolKit) to download your desired classes.

