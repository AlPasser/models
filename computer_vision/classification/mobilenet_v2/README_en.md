EN|[CN](README.osc.md)
##### Notice:
When converting the model, you can directly use the network model in the warehouse. If you need to retrain, you can refer to the network model link of the original model in readme

#### Model Description

Image classification inference model

##### Pre-trained Model Link:

https://obs-model-ascend.obs.cn-east-2.myhuaweicloud.com/mobilenet_v2/mobilenet_v2.caffemodel

##### Original Model Network Link:
https://github.com/shicai/MobileNet-Caffe

##### Input Data Description:

The input image should be resized to 224*224 pixels, and padding to 256*224 pixels, YUV420SP_U8.

##### Out Data Description:

The pre-trained model is trained for image recognition, and its results follow 1000 lables of ImageNet.

