# facetracking
facetracking experiment
用SiameseNet做人脸跟踪的实验
FacedataCurate是训练数据集和测试数据集处理脚本
Facetrack_with_HR_or_mtcnn_detect是训练和测试代码：
主要包含：1.将特征提取层改为VGG16的卷积层，层数2到4层实验，GPU内存限制没有实验5层。训练中有参数修改。
         2.实现多个人脸跟踪。
         3.结合HR(Finding tiny faces)和MTCNN进行人脸检测
