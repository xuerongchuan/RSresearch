# RSresearch
2019/2/13
推荐系统中使用tag作为辅助数据
### 标签数据处理
**方法：** 采用预训练好的word2vec数据
[下载链接](https://code.google.com/archive/p/word2vec/)  <br>

大小1.5G， 还是蛮大的

**参考资料：**
https://zhuanlan.zhihu.com/p/39784226 <br>
http://www.52nlp.cn/tag/gensim

### 交叉领域相关 
https://zhuanlan.zhihu.com/p/52824004 
知乎上介绍的文章: -   **EMCDR**
> 本文提出了一种跨域推荐的嵌入式映射框架，称为EMCDR。提出的EMCDR框架从两个方面区别于现有的跨域推荐模型。首先，在每个域中利用隐因子模型来进行Embedding学习，以此来学习每个域中实体的特定特征。第二，在域间利用Mapping技术来补充不同域的数据稀疏。其中涉及的Mapping技术主要是线性映射和多层感知机映射（MLP），值得注意的是，由于MLP可以捕捉非线性因素以及出色的拟合能力，性能要由于线性映射。

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwMjk5MTAxNDcsLTgyNzIzNzA2N119
-->