# helhat
1----将keras-yolo3/VOCdevkit/VOC2008/JPEGImage和/Annotations路径下标注好的图片和标注框文件分别存好
2----运行VOC2008下的test.py
3----运行voc_annotation.py文件自动生成标注信息文件2008_train.txt
4----检查/model_data/classes.txt文件存放类的信息
5----确认好上述，修改train.py文件参数值，开始训练
6----最后执行yolo_detect.py程序开始识别（python3 yolo_detect.py --input 视频路径）
