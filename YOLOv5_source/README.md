# README

跟YOLO官方下载的fork文件有一些出入

- 更改了权重向量`./yolov5/weights`加入了一些新的预训练模型， `./yolov5/model`中更改了`export.py`、`detect.py`等文档，关闭了wandb，加入了中文输出的功能，所以文档路径尽量不要更改！
- Master中有三个Jupyter文本，里面有具体操作的执行方案：
  1. `train.ipynb`：主要有宏包安装，训练，测试，模型导出，检测等功能实现，修改主要参数（输入输出路径，训练权重选取，训练epoch次数等）
  2. `capture.ipynb`：cv文件读取（从摄像头等地方获取训练集），LabelImg数据标记，文件转换（XML-->txt或者其他格式转换成txt），转换成coco类型或者是VOC类型的数据集存储格式
  3. `transform.ipynb`：将图片逐帧转换回视频，图片逐帧合并成视频

项目内的空白文件夹及其说明（因为隐私和数据量比较大的原因没有上传）：

datasets、package主要存放数据集和yolo的训练模型`.pt文件`

yolov5/data/video文件是测试的mp4文件

yolov5/runs/detect&test&train：分别是训练结果、测试结果、检测结果

