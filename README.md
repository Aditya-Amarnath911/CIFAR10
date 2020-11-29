# CIFAR10

The CIFAR-10 dataset
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

classes in CIFAR10 Dataset
Airplane, automobile,bird,cat,deer,dog,frog,horse,ship,truck

The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks.

In this notebook I have implemented by the following methods:

1)Model 1 is the basic model without data augmentation or normalization.
Implement by using basic CNN architecture
Model 1 accuracy is 74%

2)Model 2 is done by data augmentation and normalization.
Implement by using basic CNN architecture
Model 2 accuracy is 86%
