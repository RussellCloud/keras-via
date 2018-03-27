## Visualizing Convolutional Neural Networks in Python

### 卷积神经网络可视化方法

随着计算能力的提升，神经网络在很多地方出色的表现。但在工程应用领域，却有一个问题一直困扰着大家，神经网络到底是怎么工作的？尽管神经网络为数据挖掘人员省去了大量的特征构造时间，但在某些要求可靠性的领域，可解释性不强，却一直在制约深度学习的应用。



为了提高神经网络的可解释性，研究人员从很多角度做了探索。其中一方面，就是利用目标的梯度，突出重要像素，从而可视化神经网络的决策过程。



### Conv filter visualization

<img src="https://raw.githubusercontent.com/raghakot/keras-vis/master/images/conv_vis/cover.jpg?raw=true"/>

*Convolutional filters learn 'template matching' filters that maximize the output when a similar template 
pattern is found in the input image. Visualize those templates via Activation Maximization.*



### Dense layer visualization

<img src="https://raw.githubusercontent.com/raghakot/keras-vis/master/images/dense_vis/cover.png?raw=true"/>

*How can we assess whether a network is over/under fitting or generalizing well?*



### Attention Maps

<img src="https://raw.githubusercontent.com/raghakot/keras-vis/master/images/attention_vis/cover.png?raw=true"/>

*How can we assess whether a network is attending to correct parts of the image in order to generate a decision?*



## 使用方法

### 本地的使用方法

#### 依赖
```
keras
keras-vis
```

#### 操作过程
```
git clone https://github.com/RussellCloud/keras-via.git
cd keras-via
jupyter notebook
```



### RussellCloud 云服务

**省去繁杂的配置过程；随开随停**
#### Step 1 
搞定一个平台账号，[点我](http://russellcloud.com/welcome)，创建名为`keras-via`的`keras`项目。

```
pip install -U russell-cli
```

#### Step 2
克隆复现

```
git clone https://github.com/RussellCloud/keras-via.git
cd keras-via

russell login
russell init --name keras-via
russell run --mode jupyter --gpu
```





参考资料

- [raghakot/keras-vis](https://github.com/raghakot/keras-vis)

