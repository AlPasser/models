中文|[英文](README_en.md)
#### 模型�述：

图�分类推�模型

##### 注�事项：
转�模型时，请直接在仓库中下载网络模型（prototxt文件），如果需��新训练，请根�下�的原始模型网络链接地�进行�新训练。

##### 预训练模型下载地�:
https://obs-model-ascend.obs.cn-east-2.myhuaweicloud.com/dpn98/dpn98.caffemodel

##### 原始模型网络链接地�:
https://github.com/soeaver/caffe-model/blob/master/cls/dpn/deploy_dpn98.prototxt

##### 输入数��述:

模型�求的输入的图片宽高为 224\*224 �素，填充为256*224�素，YUV420SP_U8。

##### 输出数��述:

对预处��的模型进行图�识别训练，其结果符�ImageNet的1000个标签。