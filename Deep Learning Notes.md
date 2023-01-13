# Deep Learning Notes

## [Word2Vec]()

> 

## [RNN](https://blog.csdn.net/Tink1995/article/details/104868903?spm=1001.2014.3001.5502)

> ### RNN基本特点
>
> 基本上是在全连接神经网络的隐藏层中加了一个循环操作，把<u>上一时刻的隐藏层的值传入到下一时刻的隐藏层时的权重矩阵</u>放入下一时刻的隐藏层中代入计算。
>
> 所以隐藏层的值不仅与输入值有关，还与上一时刻隐藏层的值有关。
>
> “这样，所谓的隐藏层的循环操作也就不难理解了，就是每一时刻计算一个隐藏层地值，然后再把该隐藏层地值传入到下一时刻，达到信息传递的目的。”
>
> ### RNN结构
>
> ![未命名文件 (3)](C:\Users\huawei\Downloads\未命名文件 (3).jpg)
>
> ```
> Xt是t时刻的输入，是一个[x0,x1,x2…xn]的向量
> U是输入层到隐藏层的权重矩阵
> St是t时刻的隐藏层的值
> W是上一时刻的隐藏层的值传入到下一时刻的隐藏层时的权重矩阵
> V是隐藏层到输出层的权重矩阵
> Ot是t时刻RNN网络的输出
> ```
>
> 隐藏层值：St=f(U⋅Xt+W⋅St−1+b)
>
> 输出层值：Ot=g(V⋅St)
>
> **注意：在同一层隐藏层中，不同时刻的W，V，U均是相等地，这也就是RNN的参数共享。**
>
> ![公式解释](https://img-blog.csdnimg.cn/2020031421491483.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1RpbmsxOTk1,size_16,color_FFFFFF,t_70)
>
> 

## [LSTM and GRU](https://blog.csdn.net/Tink1995/article/details/104881633?spm=1001.2014.3001.5502)

> 

## [CNN and TextCNN](https://blog.csdn.net/Tink1995/article/details/104528624?spm=1001.2014.3001.5502)

> 

## [BERT](https://blog.csdn.net/Tink1995/article/details/105190260?spm=1001.2014.3001.5502)

> 

## [Attention](https://blog.csdn.net/Tink1995/article/details/105012972?spm=1001.2014.3001.5502)

> [A Detailed explanation](https://zhuanlan.zhihu.com/p/48508221)
>
> 

## [Transformer](https://blog.csdn.net/Tink1995/article/details/105080033)

> 

## [BART]()(By Facebook)

> 

## [PEGASUS](https://zhuanlan.zhihu.com/p/214195504)(By Google)

> 

## [Activation functions](https://zhuanlan.zhihu.com/p/364620596)

> ### Sigmoid
>
> 
>
> ### Tanh
>
> 
>
> ### ReLU
>
> 
>
> ### Leaky ReLU
>
> 
>
> ### Parametric ReLU
>
> 
>
> ### ELU
>
> 
>
> ### SeLU
>
> 
>
> ### Softmax
>
> 
>
> ### Swish
>
> 
>
> ### Maxout
>
> 
>
> ### Softplus
>
> 