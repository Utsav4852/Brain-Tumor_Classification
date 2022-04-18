# Brain-Tumor_Classification
Detecting and Separating Brain Tumor using, CNN and automated classification techniques using Machine Learning. Therefore, developed a system that enables detection and classification using Deep Learning algorithms.

## Dataset
Dataset is publically available at <a href='https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri'>Kaggle</a>.

## Methodology
Convolutional Neural Networks are normally evolved at a set sources value and scaled up to archive higher accuracy over distinctive length of sources are available. Normally, distinctive version turned into some model to get higher accuracy over distinctive length of data. For example, ResNet may be scaled up from ResNet-18 to ResNet-200 through increasing the quantity of layers. Likewise, EfficientnetB0 is enormously powerful compound coefficient to scaled up CNNs in a greater structural manner. Unlike traditional strategies that arbitrarily scale community dimensions, consisting of width, intensity and resolution, this model uniformly scales every
size with a hard and fast set of scaling coefficients. Powered with the aid of using this novel scaling technique, which superpass contemporary accuracy with as much as 10x higher efficiency (smaller and faster). The first step withinside the compound scaling technique is to carry out a grid search to locate the connection among unique scaling dimensions of the baseline community below a set useful resource constraint. This determines the right scaling coefficient for every of the size stated above. The effectiveness of version scaling additionally is predicated closely at the baseline network. So, to similarly enhance performance, we’ve advanced a brand new
baseline community with the aid of using appearing a neural architecture search with the usage of the AutoML MNAS framework, which optimizes each accuracy and efficiency
(FLOPS). The ensuing structure makes use of cellular inverted bottleneck convolution (MBConv), much like MobileNetV2 and MnasNet, however is barely large because of an multiplied FLOP budget. We then scale up the baseline community to acquire a own circle of relatives of models, known as EfficientNets.

![image](https://user-images.githubusercontent.com/40597501/163887968-44e0a70e-8325-4f10-b79c-3b4f1aa1ca16.png)
<h3 align='center'>EfficientNetB0 model Architecture </h3>

![image](https://user-images.githubusercontent.com/40597501/163888274-cfae03dc-5ed3-4a0b-82a6-72cb74e340e8.png)
<h3 align='center'>Flow Diagram</h3>
