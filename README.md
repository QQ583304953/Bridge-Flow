An attempt to generate new bridge types from latent space of generative flow

Hongjun Zhang

Wanshi Antecedence Digital Intelligence Traffic Technology Co., Ltd, Nanjing, 210016, China

Abstract：Through examples of coordinate and probability transformation between different distributions, the basic principle of normalizing flow is introduced in a simple and concise manner. From the perspective of “the distribution of random variable function”, the essence of probability transformation is explained, and the scaling factor Jacobian determinant of probability transformation is introduced. Treating the dataset as a sample from the population, obtaining normalizing flow is essentially through sampling surveys to statistically infer the numerical features of the population, and then the loss function is established by using the maximum likelihood estimation method. This article introduces how normalizing flow cleverly solves the two major application challenges of high-dimensional matrix determinant calculation and neural network reversible transformation. Using symmetric structured image dataset of three-span beam bridge, arch bridge, cable-stayed bridge and suspension bridge, constructing and training normalizing flow based on the Glow API in the TensorFlow Probability library. The model can smoothly transform the complex distribution of the bridge dataset into a standard normal distribution, and from the obtained latent space sampling, it can generate new bridge types that are different from the training dataset.

Keywords: generative artificial intelligence; bridge-type innovation; generative flow; latent space; deep learning

从标准化流隐空间中生成新桥型的尝试

张洪俊

（万世先行数智交通科技有限公司，南京210016）

摘要：通过不同分布之间的坐标、概率转换实例，深入浅出地介绍了标准化流的基本原理。从“随机变量函数的分布”的角度，阐述概率转换的实质，引出了概率转换的缩放因子雅可比行列式。把训练集当成从总体中的抽样，得出标准化流实质上是通过抽样调查，来对总体的数字特征进行统计推断，从而利用最大似然估计法建立损失函数。介绍了标准化流是如何巧妙解决高维矩阵行列式计算、神经网络可逆变换的两大应用挑战。采用对称结构的三跨梁式桥、拱式桥、斜拉桥、悬索桥图像数据集，基于TensorFlow Probability库中的Glow API，构建和训练标准化流。模型能够顺利将桥型数据集的复杂分布变换为标准正态分布，从得到的隐空间采样，能够生成不同于训练数据集的新桥型。

关键词：生成式人工智能；桥型创新；标准化流；隐空间；深度学习

