## 基于流形学习的多项式逼近算法（PAML）
 流形学习可以应用在很多领域，人脸识别、音频检测、行为追踪等。流形学习有线性核非线性之分，
 但大多数流形学习是非线性的，且不提供对未知数据点的直接映射，对于新来的高维数据点out of sample,只能合并到原来的数据集中，重新应用流形算法去学习，进行了重复计算，非常耗时，我们希望利用传统流形学习方法得出一个从高维到低维的关系f,用多项式逼近f(为方便计算，只用到二阶多项式)。这样对于新来的点，我们只需要用y = f(x) 即可求得。

