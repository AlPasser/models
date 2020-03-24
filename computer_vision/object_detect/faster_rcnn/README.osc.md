中文|[英文](README_en.md)

该模型文件在开�模型的基础上对奇异值分解进行了优化，�少了全连通层的�数，大大��了模型的尺寸。具体用法请�考以下脚本。
https://github.com/rbgirshick/py-faster-rcnn/blob/781a917b378dbfdedb45b6a56189a31982da1b43/tools/compress_net.py

#### 模型�述：

用于对象检测的网络模型

##### 注�事项：
转�模型时，请直接在仓库中下载网络模型（prototxt文件），如果需��新训练，请根�下�的原始模型网络链接地�进行�新训练。

##### 预训练模型下载地�:
https://obs-model-ascend.obs.cn-east-2.myhuaweicloud.com/fast_rcnn/faster_rcnn.caffemodel

##### 原始模型网络链接地�:
https://github.com/rbgirshick/py-faster-rcnn/blob/781a917b378dbfdedb45b6a56189a31982da1b43/models/pascal_voc/VGG16/faster_rcnn_end2end/test.prototxt

##### 输入数��述:

输入图�应该调整为800\*600�素

##### 输出数��述:

训练�的模型被训练�检测Pascal voc数�集。它�以识别20类对象和1个背景。

##### 自定义�作符:
为了�少�期处�的难度，我们�供了一个�为“detection out�的自定义层，它�以帮助我们过滤边界框。在转�模型之�，请将以下层定义添加到prototxt文件的末尾层{name: "detection out" type: "FSRDetectionOutput" bottom: "cls prob" bottom: "bbox pred" bottom: "rois" top: "out box num" top: "detection out"