### [官方网站(需翻墙)](https://www.tensorflow.org/)

### 1 Prerequisites
* tensorflow-gpu需要[CUDA Compute Capability 3.0或更高](https://developer.nvidia.com/cuda-gpus)
的[Nvidia公司GPU](https://www.jd.com/)
* tensorflow-gpu在Windows7上回出现奇怪的显卡卸载问题，
目前仅能在[Windows10](https://www.microsoft.com/zh-cn/software-download/windows10)上成功使用
* tensorflow-gpu在Windows上需要[Python3.5/Python3.6](https://www.python.org/downloads/)
* tensorflow1.3需要[CUDA® Toolkit 8.0](http://docs.nvidia.com/cuda/cuda-installation-guide-microsoft-windows/),
在文档中有[下载地址](https://developer.nvidia.com/cuda-downloads)
* tensorflow1.3需要[Cudnn6.0](https://developer.nvidia.com/cudnn)

### 2 Installation
#### 2.1 检查你电脑上的显卡，Windows版本，Python版本
#### 2.2 安装CUDA® Toolkit,注意要安装其中所带的显卡驱动
#### 2.3 安装Cudnn，要将其中的dll文件路径(比如```C:\cuda\bin```)加入环境变量
#### 2.4 安装Tensorflow-gpu

      pip install --upgrade tensorflow-gpu