# EuroCity2Yolo
## Convert EuroCity Person annotated format data to YOLO format data. 
## 将EuroCity Person标注格式的数据转换成YOLO格式的数据

之前入坑目标检测，需要使用夜间图像，申请到的EuroCity Person数据集又不是Yolo格式。
其实本可以直接转换，但当时不知道数据标注的格式和其他一堆乱七八糟的东西（实际上数据集官网的说明文档里有详细说明，在某个犄角旮旯的地方有个不起眼的文档...），start from scratch太费时费事了，索性就直接发挥google大法。恰好发现有ecp格式到coco格式的，还有coco到yolo的，直接运行不大行，稍作debug后成功解决

### 1.ecp2coco.py
将ecp标签格式转化为coco格式

### 2.coco2yolo.py
将coco标签格式转化为yolo格式

