中文|[英文](Readme.md)
#### 模型�述：

用于标记�部特�点的网络模型

##### 注�事项：
转�模型时，请直接在仓库中下载网络模型（prototxt文件），如果需��新训练，请根�下�的原始模型网络链接地�进行�新训练。

##### 预训练模型下载地�:
https://obs-model-ascend.obs.cn-east-2.myhuaweicloud.com/vanillacnn/vanillacnn.caffemodel

##### 原始模型网络链接地�:
https://github.com/ishay2b/VanillaCNN/tree/master/ZOO/vanilla_deploy.prototxt

##### 输入数��述:

输入图�应该调整为40*40�素

##### 输出数��述:

对预处��的模型进行训练，对人脸上的关键点进行检测。它将识别5个�标点(左眼，�眼，鼻�，左嘴角，�嘴角)。

##### 自定义�作符:
�包括

##### 输出数��述:
- Atlas 200