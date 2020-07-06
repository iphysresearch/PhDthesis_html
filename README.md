> **引力波探测中关于深度学习数据分析的研究**
>
> **Research on Data Analysis of Deep Learning in Gravitational Wave Detection**


## 描述

- 此文是本人博士毕业论文的 HTML 版，用于学位申请的 PDF 版可见：[Overleaf](https://www.overleaf.com/read/gthybdcykshj) 或 [GWDL_thesis_final.pdf](https://github.com/iphysresearch/PhDthesis_html/blob/master/GWDL_thesis_final.pdf)。毕业答辩用的 Slides 可见 [Slides.com](https://slides.com/iphysresearch/phd-defense)。

- 开源此论文的原因，不仅是为了方便个人查阅和总结，也希望能够促进相关领域的研究和进步，多多增进学术交流的机会。

- 该课题之初开展于相关研究的初探性阶段，由于本人才疏学浅，难免会存在理论上的疏忽和遗漏，或论述上的错误与不准确，也可能会有文献引用资料更新不及时的情况。如有不妥之处，还望明示指出! [My Email](mailto:hewang@mail.bnu.edu.cn)


## 正文目录 
* [摘要](https://iphysresearch.github.io/PhDthesis_html/Abstract/)
* [第一章 绪论](https://iphysresearch.github.io/PhDthesis_html/C1/)
    - [1.1 引言](https://iphysresearch.github.io/PhDthesis_html/C1/#11)
    - [1.2 多信使天文学](https://iphysresearch.github.io/PhDthesis_html/C1/#12)
    - [1.3 研究现状、机遇与挑战](https://iphysresearch.github.io/PhDthesis_html/C1/#13)
    - [1.4 本文研究的目标与框架](https://iphysresearch.github.io/PhDthesis_html/C1/#14)
* [第二章 引力波探测和数据分析理论](https://iphysresearch.github.io/PhDthesis_html/C2/)
    - [2.1 引言](https://iphysresearch.github.io/PhDthesis_html/C2/#21)
    - [2.2 引力波探测技术](https://iphysresearch.github.io/PhDthesis_html/C2/#22)
        * [2.2.1 引力波波源建模](https://iphysresearch.github.io/PhDthesis_html/C2/#221)
        * [2.2.2 引力波探测实验](https://iphysresearch.github.io/PhDthesis_html/C2/#222)
        * [2.2.3 引力波数据处理](https://iphysresearch.github.io/PhDthesis_html/C2/#223)
    - [2.3 信号处理与数据分析方法](https://iphysresearch.github.io/PhDthesis_html/C2/#23)
        * [2.3.1 稳态性与高斯性](https://iphysresearch.github.io/PhDthesis_html/C2/#231)
        * [2.3.2 功率谱密度](https://iphysresearch.github.io/PhDthesis_html/C2/#232)
        * [2.3.3 能谱泄露与白化](https://iphysresearch.github.io/PhDthesis_html/C2/#233)
        * [2.3.4 时域信号平移](https://iphysresearch.github.io/PhDthesis_html/C2/#234)
    - [2.4 匹配滤波技术](https://iphysresearch.github.io/PhDthesis_html/C2/#24)
        * [2.4.1 匹配滤波内积](https://iphysresearch.github.io/PhDthesis_html/C2/#241)
        * [2.4.2 稳态噪声的概率分布](https://iphysresearch.github.io/PhDthesis_html/C2/#242)
        * [2.4.3 理想探测统计量](https://iphysresearch.github.io/PhDthesis_html/C2/#243)
        * [2.4.4 振幅未知的模板匹配滤波](https://iphysresearch.github.io/PhDthesis_html/C2/#244)
        * [2.4.5 到达时间未知的模板匹配滤波](https://iphysresearch.github.io/PhDthesis_html/C2/#245)
    - [2.5 总结与结论](https://iphysresearch.github.io/PhDthesis_html/C2/#25)
* [第三章 深度学习的理论基础](https://iphysresearch.github.io/PhDthesis_html/C3/)
    - [3.1 引言](https://iphysresearch.github.io/PhDthesis_html/C3/#31)
    - [3.2 机器学习理论](https://iphysresearch.github.io/PhDthesis_html/C3/#32)
        * [3.2.1 基于梯度的优化方法](https://iphysresearch.github.io/PhDthesis_html/C3/#321)
            - [3.2.1.1 代价函数](https://iphysresearch.github.io/PhDthesis_html/C3/#3211)
            - [3.2.1.2 随机梯度下降算法](https://iphysresearch.github.io/PhDthesis_html/C3/#3212)
        * [3.2.2 模型的泛化能力，过拟合与欠拟合](https://iphysresearch.github.io/PhDthesis_html/C3/#322)
        * [3.2.3 性能度量指标：ROC 与 AUC](https://iphysresearch.github.io/PhDthesis_html/C3/#323_roc_auc)
    - [3.3 深度神经网络](https://iphysresearch.github.io/PhDthesis_html/C3/#33)
        * [3.3.1 神经元](https://iphysresearch.github.io/PhDthesis_html/C3/#331)
        * [3.3.2 全连接的神经网络](https://iphysresearch.github.io/PhDthesis_html/C3/#332)
        * [3.3.3 反向传播算法](https://iphysresearch.github.io/PhDthesis_html/C3/#333)
        * [3.3.4 Dropout 方法](https://iphysresearch.github.io/PhDthesis_html/C3/#334_dropout)
    - [3.4 卷积神经网络](https://iphysresearch.github.io/PhDthesis_html/C3/#34)
        * [3.4.1 卷积](https://iphysresearch.github.io/PhDthesis_html/C3/#341)
        * [3.4.2 非线性激活](https://iphysresearch.github.io/PhDthesis_html/C3/#342)
        * [3.4.3 池化](https://iphysresearch.github.io/PhDthesis_html/C3/#343)
        * [3.4.4 空洞卷积与感受野](https://iphysresearch.github.io/PhDthesis_html/C3/#344)
    - [3.5 总结与结论](https://iphysresearch.github.io/PhDthesis_html/C3/#35)
* [第四章 引力波探测中关于神经网络的可解释性研究](https://iphysresearch.github.io/PhDthesis_html/C4/)
    - [4.1 引言](https://iphysresearch.github.io/PhDthesis_html/C4/#41)
    - [4.2 神经网络的结构](https://iphysresearch.github.io/PhDthesis_html/C4/#42)
    - [4.3 数据集的制备和优化策略](https://iphysresearch.github.io/PhDthesis_html/C4/#43)
    - [4.4 引力波信号识别的泛化能力](https://iphysresearch.github.io/PhDthesis_html/C4/#44)
    - [4.5 引力波信号特征的可视化表示](https://iphysresearch.github.io/PhDthesis_html/C4/#45)
        * [4.5.1 正向可视化方法](https://iphysresearch.github.io/PhDthesis_html/C4/#451)
        * [4.5.2 逆向可视化方法](https://iphysresearch.github.io/PhDthesis_html/C4/#452)
    - [4.6 引力波波形特征的灵敏度分析](https://iphysresearch.github.io/PhDthesis_html/C4/#46)
    - [4.7 总结与结论](https://iphysresearch.github.io/PhDthesis_html/C4/#47)
* [第五章 卷积神经网络结构对引力波信号识别的性能研究](https://iphysresearch.github.io/PhDthesis_html/C5/)
    - [5.1 引言](https://iphysresearch.github.io/PhDthesis_html/C5/#51)
    - [5.2 引力波数据的制备和处理流程](https://iphysresearch.github.io/PhDthesis_html/C5/#52)
    - [5.3 引力波数据分析中信噪比的比较分析](https://iphysresearch.github.io/PhDthesis_html/C5/#53)
    - [5.4 卷积神经网络的超参数调优和性能比较](https://iphysresearch.github.io/PhDthesis_html/C5/#54)
    - [5.5 总结与结论](https://iphysresearch.github.io/PhDthesis_html/C5/#55)
* [第六章 匹配滤波-卷积神经网络(MF-CNN)模型的应用研究](https://iphysresearch.github.io/PhDthesis_html/C6/)
    - [6.1 引言](https://iphysresearch.github.io/PhDthesis_html/C6/#61)
    - [6.2 时域中的匹配滤波](https://iphysresearch.github.io/PhDthesis_html/C6/#62)
    - [6.3 用于匹配滤波的卷积神经单元](https://iphysresearch.github.io/PhDthesis_html/C6/#63)
    - [6.4 匹配滤波-卷积神经网络(MF-CNN)模型的构造](https://iphysresearch.github.io/PhDthesis_html/C6/#64_-mf-cnn)
    - [6.5 搜寻疑似引力波信号的策略](https://iphysresearch.github.io/PhDthesis_html/C6/#65)
    - [6.6 数据准备与模型微调](https://iphysresearch.github.io/PhDthesis_html/C6/#66)
    - [6.7 真实 LIGO 引力波数据上的搜寻结果](https://iphysresearch.github.io/PhDthesis_html/C6/#67_ligo)
        * [6.7.1 搜寻 O1 和 O2 中的引力波信号](https://iphysresearch.github.io/PhDthesis_html/C6/#671_o1_o2)
        * [6.7.2 疑似引力波信号的统计特性](https://iphysresearch.github.io/PhDthesis_html/C6/#672)
        * [6.7.3 引力波信号与 glitch 的统计分析](https://iphysresearch.github.io/PhDthesis_html/C6/#673_glitch)
    - [6.8 总结与结论](https://iphysresearch.github.io/PhDthesis_html/C6/#68)
* [第七章 总结与展望](https://iphysresearch.github.io/PhDthesis_html/C7/)
* [附录](https://iphysresearch.github.io/PhDthesis_html/Appendix/)
    - [A. 采样定理与 Nyquist 频率](https://iphysresearch.github.io/PhDthesis_html/Appendix/#a_nyquist)
    - [B. 关于功率谱密度性质的数学证明](https://iphysresearch.github.io/PhDthesis_html/Appendix/#b)
    - [C. 最大似然估计和交叉熵](https://iphysresearch.github.io/PhDthesis_html/Appendix/#c)


## 版权声明

* 该论文工作的知识产权单位属北京师范大学。详情可查阅相关学位论文授权使用声明。
* <a rel="license" href="http://creativecommons.org/licenses/by-nc/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/3.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/3.0/">Creative Commons Attribution-NonCommercial 3.0 Unported License</a>.
