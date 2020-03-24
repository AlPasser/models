中文|[英文](Readme.md)
#### 模型�述：

汽车�牌识别的网络模型

##### 注�事项：
转�模型时，请直接在仓库中下载网络模型（prototxt文件），如果需��新训练，请根�下�的原始模型网络链接地�进行�新训练。

##### 预训练模型下载地�:
https://obs-model-ascend.obs.cn-east-2.myhuaweicloud.com/car_type/car_type.caffemodel

##### 原始模型网络链接地�:
https://gist.github.com/bogger/b90eb88e31cd745525ae

##### 输入数��述:

模型�求的输入的图片宽高为 224\*224 pixels，格�是RGB。

##### 输出数��述:

对应于培训数�集的标签文件的地�是 https://github.com/bogger/caffe-multigpu/blob/multigpu/models/finetune_web_car/matlab/make_model_names_cls.mat