中文|[英文](README_en.md)
#### 模型�述：

用于获�特���的网络模型

##### 注�事项：
转�模型时，请直接在仓库中下载网络模型（prototxt文件），如果需��新训练，请根�下�的原始模型网络链接地�进行�新训练。

##### 预训练模型下载地�:
https://obs-model-ascend.obs.cn-east-2.myhuaweicloud.com/sphereface/sphereface.caffemodel

##### 原始模型网络链接地�:
https://github.com/wy1iu/sphereface

##### 输入数��述:

大�: 96*112格�:RGB U8

##### 输出数��述:

预训练的模型在CAISA-WebFace上进行训练，在LFW上使用20层CNN架构进行测试。它将识别人脸并返回512��。