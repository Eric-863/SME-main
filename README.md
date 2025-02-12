数据集
链接: https://pan.baidu.com/s/1VcednLdgcgMlBwqULB4LnQ?pwd=sfi3 提取码: sfi3
运行
1.将提供的数据集放入VOCdevkit/VOC2007中
2.在train.py中设置对应参数，默认参数已经对应数据集所需要的参数
3.运行train.py进行训练
预测
1.在predict.py里面进行设置可以进行fps测试、整个文件夹的测试和video视频检
测。
2.在deeplab.py文件里面，在如下部分修改model_path、num_classes、backbone
使其对应训练好的文件；**model_path对应logs文件夹下面的权值文件，
num_classes代表要预测的类的数量加1
3.代码中有注释，如果不理解。可以参考：https://www.bilibili.com/video/BV173411q7xF/?spm_id_from=333.999.0.0&vd_source=a519adae4676331dd322942d3c9039e8
