中文|[英文](Readme.md)
#### 模型�述：

图�分类推�模型

##### 注�事项：
转�模型时，请直接在仓库中下载网络模型（prototxt文件），如果需��新训练，请根�下�的原始模型网络链接地�进行�新训练。

##### 预训练模型下载地�:
https://obs-model-ascend.obs.cn-east-2.myhuaweicloud.com/inception_v3/inception_v3.caffemodel

##### 原始模型网络链接地�:
https://drive.google.com/open?id=0B9mkjlmP0d7zTEJmNEh6c0RfYzg

##### 输入数��述:

输入图�应该调整为299*299�素，填充为384*304�素，YUV420SP_U8。

##### 输出数��述:

对预训练�的模型进行图�识别训练，其结果应加入2，然�按照1000个标签的synset.txt输入：https://drive.google.com/open?id=0B9mkjlmP0d7zTEJmNEh6c0RfYzg.