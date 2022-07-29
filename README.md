# Improved-VFNet<br />
这是一种基于改进VFNet的高精度目标检测算法<br />
## 消融实验 
| Backbone      |Neck       |    mAP     |    AP50     |    AP75     |    AP_S     |    AP_M     |    AP_L     |    推理结果     |
|     :---      |  :---     |   :---     |   :---     |   :---     |   :---     |   :---     |   :---     |   :---     |
| ResNet50      | FPN       |    41.6    |     59.8    |    45.0    |     23.9    |     44.6    |    51.4    |     [VFNet](https://github.com/hyz-xmaster/VarifocalNet)      |
| ResNet50        | FPN_DCN   |     41.8    |     59.9    |     45.4    |     24.7    |     44.8    |     50.8    |    [百度云链接](https://pan.baidu.com/s/1TdoY_lqLc7IkkCBFwYyOMQ)     |
|  RLA50        | FPN       |     42.9    |     61.0    |     46.5    |     24.7    |     45.8    |     53.6    |     [百度云链接](https://pan.baidu.com/s/1EJdOuZDOeuyq0DO-_7zWzQ)     |
| RLA50         | FPN_DCN   |     43.1    |     61.1    |     46.7    |     25.2    |     46.0    |     53.1    |     [百度云链接](https://pan.baidu.com/s/1IytKC84RJSECNGGeORS5EA)      |
>单尺度，单批次训练。 提取码均为: 6666

[COCO test-dev 官方评估服务器](https://competitions.codalab.org/competitions/20794#participate)
