## 摘要

对于一篇议论文来说
论点(Argument)的说服力(persuasiveness)是最重要的维度之一
但是当前的自动评分系统并没有很好地研究和使用这一点
本文通过使用近期公开的一个文章语料库
设计了一个神经网络模型来预测学生文章中的论点的说服力和属性

这样, 我们可以为学生提供有用的反馈:
1. 他们的论点为什么具有(或不具有)说服力
2. 他们的论点的说服力有多强

使用的语料库同时标注了:
1. 论点
2. 论点说服力评分
3. 对论点说服力具有影响因素的属性等

## 主体

在文章的自动评分以及评分反馈方面
作者认为他的文章关注了一个重要但一直被忽略的方面:
文章中论点的说服力

作者认为, 构建这种模型的最大难处在于没有合适的语料库
因此作者构建了一个符合要求的语料库
就是满足摘要中提到的那些条件的语料库
To our knowledge, this is the ﬁrst corpus of essays that are simultaneously
 annotated with argument components, argument persuasiveness scores,
 and related attributes.
 
Argument trees: MajroClaim, Claims, Premises, Support, Attack.
Compare with a Baseline model to observe the influence of argument component

## 结论

作者构建了第一个神经网络模型来预测论点的说服力和属性
结果是非常有前景的
但是作者认为通过改进属性预测
这个模型的性能依然可以进行提升

