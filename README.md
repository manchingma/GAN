# GAN

从信息论入门对抗生成网络GAN：
https://zhuanlan.zhihu.com/p/41993080

使用方法：
1. 下载MNIST数据集：http://yann.lecun.com/exdb/mnist/
2. 创建MNIST_data文件夹，并放入解压后的数据
3. 运行脚本

<b>Basic GAN</b>  
python gan_example.py  
GAN结构如下图，3层全连接NN网络（不是CNN）

<img src="https://raw.githubusercontent.com/bai-shang/GAN/master/gan-network.png" height="200">
  
  
  
  
  
<b>Conditional GAN</b>  
python conditional_gan_example.py  
CGAN结构如下图
<img src="https://raw.githubusercontent.com/bai-shang/GAN/master/cgan-network.png" height="200">
