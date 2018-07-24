# 第八章
## data目录介绍
1. `data_temp`是用于临时存放原始验证码的，等待灰度化和分配给训练和测试
2. `test_data`是测试数据，其中包括测试图像和测试图像的列表
3. `train_data`是训练数据，其中包括训练图像和训练图像的列表
4. `label_dict.txt`是标签字典

## models目录介绍
1. 该目录是存放训练好的模型

## `code`目录介绍
1. 该目录是存放代码的文件夹，具体如下

## 代码介绍
1. `CreateDataList.py`是生成图像列表并放对应的文件夹中的程序
2. `decoder.py`是预测时寻找最优路径的程序
3. `Image2GRAY.py`是把`data_temp`中图像转成灰度图，并分配到`test_data`和`train_data`的程序
4. `infer.py`是预测程序
5. `network_conf.py`是神经网络程序
6. `reader.py`是读取图像成reader的程序
7. `train.py`是训练程序
8. `utils.py`是一些方便操作的工具类程序



## 测试环境
1. Python 2.7
2. PaddlePaddle 0.10.0 (GPU版本)