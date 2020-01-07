中文|[英文](README_en.md)
#### 模型描述：

汽车品牌识别的网络模型

##### 注意事项：
转换模型时，请直接在仓库中下载网络模型（prototxt文件），如果需要重新训练，请根据下面的原始模型网络链接地址进行重新训练。

##### 预训练模型下载地址:
https://obs-model-ascend.obs.cn-east-2.myhuaweicloud.com/car_type/car_type.caffemodel

##### 原始模型网络链接地址:
https://gist.github.com/bogger/b90eb88e31cd745525ae

##### 输入数据描述:

模型要求的输入的图片宽高为 224\*224 pixels，格式是RGB。

##### 输出数据描述:

对应于培训数据集的标签文件的地址是 https://github.com/bogger/caffe-multigpu/blob/multigpu/models/finetune_web_car/matlab/make_model_names_cls.mat