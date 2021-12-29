# Algorithm-test-index
该项目是用来进行目标检测测试用的 输出为目标检测模型的各种指标
## 测试的主文件为/faster_rcnn/validation.py
## 首先修改本文件中的模型权重路径和数据集路径
### 训练好的权重文件
parser.add_argument('--weights', default="")
### 数据集的根目录(VOCdevkit)   
parser.add_argument('--data-path', default="")
## 所需要的文件
预训练权重文件和数据集文件以及pycocotools包
链接：https://pan.baidu.com/s/1qP0daST_PZJGoydpYML9WQ 
提取码：ojdc
## 执行环境使用anaconda
* 安装pytorch1.8
```commandline
conda install pytorch==1.8.0 torchvision==0.9.0 torchaudio==0.8.0 cudatoolkit=10.2 -c pytorch
```
* 安装pycocotools(windows)
```commandline
pip install pycocotools_windows-2.0.0.2-cp38-cp38-win_amd64.whl
```
* 安装pycocotools(ubuntu)
```commandline
pip insatll pycocotools
```
* 安装requirements.txt指定的依赖包
```commandline
pip install -r requirements.txt
```