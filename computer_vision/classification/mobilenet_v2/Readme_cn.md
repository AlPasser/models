中文|[英文](Readme.md)
##### 注�事项：
转�模型时，请直接在仓库中下载网络模型（prototxt文件），如果需��新训练，请根�下�的原始模型网络链接地�进行�新训练。

#### 模型�述：

图�分类推�模型

##### 预训练模型下载地�:
https://obs-model-ascend.obs.cn-east-2.myhuaweicloud.com/mobilenet_v2/mobilenet_v2.caffemodel

##### 原始模型网络链接地�:
https://github.com/shicai/MobileNet-Caffe

##### 输入数��述:

输入图�的大�应该调整为224*224�素，填充为256*224�素，YUV420SP_U8。

##### 输出数��述:

对预处��的模型进行图�识别训练，其结果符�lmageNet的1000个标签。