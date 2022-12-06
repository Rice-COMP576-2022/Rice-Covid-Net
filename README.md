# Rice-Covid-Net
## Description
**Transfer Learning Experiments**   
We ran the pre-trained models provided by Keras, trying to get some hints on building and optimizing our own network through the analysis on their performances and structures.  
[VGG-16](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/VGG16.ipynb), [VGG-19](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/VGG19.ipynb), [ResNet101](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/ResNet101.ipynb), [MobileNet](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/MobileNet.ipynb), [DenseNet121](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/DenseNet121.ipynb), [Inception V3](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/Inception%20V3.ipynb), [NasNet](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/nasnet.ipynb), [EfficientNetB0](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/CovidNet-EfficientNetB0.ipynb), [EfficientNetB7](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/CovidNet-EfficientNetB7.ipynb)

**Our Model: RiceCovidNet**    
Starting from the basic VGG-16 (The only model that converged without pretrain). RiceCovidNet has 3 iterations, finalizing in a CNN based on [Separable Convolution]() and [Residual Blocks](). Our model has state-of-the-art accuracy and speed with small model size.   
The code and results of our model RiceCovidNet are located in [this folder](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/tree/main/CovidNet).  
[V1: Based on VGG-16](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/CovidNet/CovidNet-VGG16.ipynb).  
V2: Added Separable Convolutions with filter numbers [32](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/CovidNet/CovidNet-Separable32.ipynb), [64](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/CovidNet/CovidNet-Separable64/CovidNet-Separable64.ipynb), [128](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/CovidNet/CovidNet-Separable128/CovidNet-SeparableConv128.ipynb).  
[V3: Added residual blocks](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/CovidNet/CovidNet-Res-Sep256/CovidNet-Res-Sep256.ipynb).   
[V3 network with Data Augmentation](https://github.com/Rice-COMP576-2022/Rice-Covid-Net/blob/main/CovidNet/CovidNet-Res-Sep256/CovidNet-Res-Sep256-With-data-augmentation.ipynb).  

code reference: 
https://www.kaggle.com/code/justicevil/covid19-image-classification-vgg16-val-acc-98


