---
Title: 引力波探测中关于深度学习数据分析的研究
Summary: Research on Data Analysis of Deep Learning in Gravitational Wave Detection
Authors: He Wang
Date:    June 2, 2020
blank-value:
some_url: https://example.com
---

</br>

---


## 题目

>引力波探测中关于深度学习数据分析的研究
>Research on Data Analysis of Deep Learning in Gravitational Wave Detection


## 描述

- 此文是本人博士毕业论文的 HTML 版，用于学位申请的 PDF 版可见：[Overleaf](https://www.overleaf.com/read/gthybdcykshj) 或 [Github](https://github.com/iphysresearch/GWDL_thesis)。毕业答辩用的 Slides 可见 [Slides.com](https://slides.com/iphysresearch/phd-defense)。

- 开源此论文的原因，不仅是为了方便个人查阅和总结，也希望能够促进相关领域的研究和进步，多多增进学术交流的机会。

- 该课题之初开展于相关研究的初探性阶段，由于本人才疏学浅，难免会存在理论上的疏忽和遗漏，或论述上的错误与不准确，也可能会有文献引用资料更新不及时的情况。如有不妥之处，还望明示指出! [My Email](mailto:hewang@mail.bnu.edu.cn)


## 正文目录 

* [摘要](Abstract.md)
* [第一章 绪论](C1.md)
    - [1.1 引言](C1.md#11)
    - [1.2 多信使天文学](C1.md#12)
    - [1.3 研究现状、机遇与挑战](C1.md#13)
    - [1.4 本文研究的目标与框架](C1.md#14)
* [第二章 引力波探测和数据分析理论](C2.md)
    - [2.1 引言](C2.md#21)
    - [2.2 引力波探测技术](C2.md#22)
        * [2.2.1 引力波波源建模](C2.md#221)
        * [2.2.2 引力波探测实验](C2.md#222)
        * [2.2.3 引力波数据处理](C2.md#223)
    - [2.3 信号处理与数据分析方法](C2.md#23)
        * [2.3.1 稳态性与高斯性](C2.md#231)
        * [2.3.2 功率谱密度](C2.md#232)
        * [2.3.3 能谱泄露与白化](C2.md#233)
        * [2.3.4 时域信号平移](C2.md#234)
    - [2.4 匹配滤波技术](C2.md#24)
        * [2.4.1 匹配滤波内积](C2.md#241)
        * [2.4.2 稳态噪声的概率分布](C2.md#242)
        * [2.4.3 理想探测统计量](C2.md#243)
        * [2.4.4 振幅未知的模板匹配滤波](C2.md#244)
        * [2.4.5 到达时间未知的模板匹配滤波](C2.md#245)
    - [2.5 总结与结论](C2.md#25)
* [第三章 深度学习的理论基础](C3.md)
    - [3.1 引言](C3.md#31)
    - [3.2 机器学习理论](C3.md#32)
        * [3.2.1 基于梯度的优化方法](C3.md#321)
            - [3.2.1.1 代价函数](C3.md#3211)
            - [3.2.1.2 随机梯度下降算法](C3.md#3212)
        * [3.2.2 模型的泛化能力，过拟合与欠拟合](C3.md#322)
        * [3.2.3 性能度量指标：ROC 与 AUC](C3.md#323_roc_auc)
    - [3.3 深度神经网络](C3.md#33)
        * [3.3.1 神经元](C3.md#331)
        * [3.3.2 全连接的神经网络](C3.md#332)
        * [3.3.3 反向传播算法](C3.md#333)
        * [3.3.4 Dropout 方法](C3.md#334_dropout)
    - [3.4 卷积神经网络](C3.md#34)
        * [3.4.1 卷积](C3.md#341)
        * [3.4.2 非线性激活](C3.md#342)
        * [3.4.3 池化](C3.md#343)
        * [3.4.4 空洞卷积与感受野](C3.md#344)
    - [3.5 总结与结论](C3.md#35)
* [第四章 引力波探测中关于神经网络的可解释性研究](C4.md)
    - [4.1 引言](C4.md#41)
    - [4.2 神经网络的结构](C4.md#42)
    - [4.3 数据集的制备和优化策略](C4.md#43)
    - [4.4 引力波信号识别的泛化能力](C4.md#44)
    - [4.5 引力波信号特征的可视化表示](C4.md#45)
        * [4.5.1 正向可视化方法](C4.md#451)
        * [4.5.2 逆向可视化方法](C4.md#452)
    - [4.6 引力波波形特征的灵敏度分析](C4.md#46)
    - [4.7 总结与结论](C4.md#47)
* [第五章 卷积神经网络结构对引力波信号识别的性能研究](C5.md)
    - [5.1 引言](C5.md#51)
    - [5.2 引力波数据的制备和处理流程](C5.md#52)
    - [5.3 引力波数据分析中信噪比的比较分析](C5.md#53)
    - [5.4 卷积神经网络的超参数调优和性能比较](C5.md#54)
    - [5.5 总结与结论](C5.md#55)
* [第六章 匹配滤波-卷积神经网络(MF-CNN)模型的应用研究](C6.md)
    - [6.1 引言](C6.md#61)
    - [6.2 时域中的匹配滤波](C6.md#62)
    - [6.3 用于匹配滤波的卷积神经单元](C6.md#63)
    - [6.4 匹配滤波-卷积神经网络(MF-CNN)模型的构造](C6.md#64_-mf-cnn)
    - [6.5 搜寻疑似引力波信号的策略](C6.md#65)
    - [6.6 数据准备与模型微调](C6.md#66)
    - [6.7 真实 LIGO 引力波数据上的搜寻结果](C6.md#67_ligo)
        * [6.7.1 搜寻 O1 和 O2 中的引力波信号](C6.md#671_o1_o2)
        * [6.7.2 疑似引力波信号的统计特性](C6.md#672)
        * [6.7.3 引力波信号与 glitch 的统计分析](C6.md#673_glitch)
    - [6.8 总结与结论](C6.md#68)
* [第七章 总结与展望](C7.md)
* [附录](Appendix.md)
    - [A. 采样定理与 Nyquist 频率](Appendix.md#a_nyquist)
    - [B. 关于功率谱密度性质的数学证明](Appendix.md#b)
    - [C. 最大似然估计和交叉熵](Appendix.md#c)


## 版权声明

* 该论文工作的知识产权单位属北京师范大学。详情可查阅相关学位论文授权使用声明。
* <a rel="license" href="http://creativecommons.org/licenses/by-nc/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/3.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/3.0/">Creative Commons Attribution-NonCommercial 3.0 Unported License</a>.

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=4f78b5&w=300&t=tt&d=KeeYB3un76pJkqHgl23yaieKpPYpHjZUYkLr8F-rJvE&co=ffffff&ct=808080&cmo=3acc3a&cmn=ff5353'></script>