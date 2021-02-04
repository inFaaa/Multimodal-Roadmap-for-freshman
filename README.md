# Multimodal-Roadmap-for-freshman

- [Multimodal-Roadmap-for-freshman](#multimodal-roadmap-for-freshman)
  * [工具箱](#---)
      - [领域可以follow人的工作](#----follow----)
      - [公众号](#---)
      - [相关顶会](#----)
      - [常用网站&工具](#-------)
      - [代码训练](#----)
  * [入门pipeline](#--pipeline)
      - [Step 1:深度学习基础(2 months)](#step-1--------2-months-)
      - [Step 2: Week 1(2 months)](#step-2--week-1-2-months-)
      - [Week 2](#week-2)
      - [Week 3](#week-3)
      - [Week 4](#week-4)
      - [Week 5](#week-5)
      - [Week 6](#week-6)
      - [Week 7](#week-7)
      - [Week 8](#week-8)
      - [Week 9](#week-9)
      - [Step 3:Idea(2 months)](#step-3-idea-2-months-)
  * [科研素质培养](#------)
      - [追新论文&热点的渠道](#----------)
      - [问题思考训练（评估问题的价值）](#---------------)
      - [神经网络模型绘画](#--------)
      - [可视化](#---)
      - [组会PPT&学术汇报制作经验](#--ppt---------)
      - [Rebuttal](#rebuttal)
      - [靠谱的多模态任务codebase](#--------codebase)
      - [提高GPU资源的使用率（多卡/单卡）](#--gpu-------------)
      - [多模态热点方向（按年度）](#------------)
- [Multimodal-Roadmap-for-freshman](#multimodal-roadmap-for-freshman-1)
  * [工具箱](#----1)
      - [领域可以follow人的工作](#----follow-----1)
      - [公众号](#----1)
      - [相关顶会](#-----1)
      - [常用网站&工具](#--------1)
      - [代码训练](#-----1)
  * [入门pipeline](#--pipeline-1)
      - [Step 1:深度学习基础(2 months)](#step-1--------2-months--1)
      - [Step 2: Week 1(2 months)](#step-2--week-1-2-months--1)
      - [Week 2](#week-2-1)
      - [Week 3](#week-3-1)
      - [Week 4](#week-4-1)
      - [Week 5](#week-5-1)
      - [Week 6](#week-6-1)
      - [Week 7](#week-7-1)
      - [Week 8](#week-8-1)
      - [Week 9](#week-9-1)
      - [Step 3:Idea(2 months)](#step-3-idea-2-months--1)
  * [科研素质培养](#-------1)
      - [追新论文&热点的渠道](#-----------1)
      - [问题思考训练（评估问题的价值）](#----------------1)
      - [神经网络模型绘画](#---------1)
      - [可视化](#----1)
      - [组会PPT&学术汇报制作经验](#--ppt----------1)
      - [Rebuttal](#rebuttal-1)
      - [靠谱的多模态任务codebase](#--------codebase-1)
      - [提高GPU资源的使用率（多卡/单卡）](#--gpu--------------1)
      - [多模态热点方向（按年度）](#-------------1)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


*本项目用于Multimodal领域新手的学习路线，包括该领域的经典论文，项目及课程。旨在希望学习者在一定的时间内达到对这个领域有较为深刻的认知，能够自己进行的独立研究。*



 做研究的主要pipeline分为：

1.先收集研究领域最近2-3年文献进行阅读&复现靠谱好用的codebase 

2.通过阅读把自己想做的问题定义好,这个时候思考要有深度

3.根据问题去设计模块，先在该任务上达到SOTA性能（这是个漫长的过程，要不断尝试idea）

4.如果能跑到好的性能，说明是可以发表的工作，这时候要和人讨论，设计实验过程（如何论证你的问题），补充中间结果，这个阶段可以尝试写Intro+related work 

5.跑各种消融结果+可视化中间结果+参数分析，尝试刷更高性能，写论文改论文。

6.一定要在会议截至之前2周把论文写出来，基本太赶的论文最后都是被拒的。



## 工具箱

#### 领域可以follow人的工作

偏CV：吴琦老师，何晓冬老师，张含望老师，马林老师，Jiasen Lu

偏NLP：段楠老师，Christopher D. Manning，何晓冬老师，Paul Pu Liang



#### 公众号

- 机器之心

- Paperweekly

- 极市平台

- AI科技评论

- 新智元

- 专知

- Arxiv每日学术速递

- 量子位

- CVer

  

#### 相关顶会

CVPR，ICCV，ECCV，NIPS，ICLR，ACL，EMNLP

重要程度：oral论文（带code）> poster论文（带code）> oral论文（无code）>  poster（无code）> workshop

适当阅读science，nature，pami和ijcv的文章，扩大视野



**顶会时间线:**(具体时间看官方日期锁定)

上半年：ACL->ICML->ICCV->NeurIPS->MM->EMNLP

下半年：AAAI->ICLR->CVPR



**ICML (CCF-A)**: International Conference on Machine Learning

  截稿日期：约每年1月份下旬

  审稿周期：约3个半月 (即5月上旬出结果)



**NeurIPS (CCF-A)**: Conference on Neural Information Processing Systems

  截稿日期：约每年5月份下旬

  审稿周期：约3个半月 (即9月上旬出结果)



**ICLR (无评级)**: International Conference on Learning Representations

  截稿日期：约每年9月份下旬

  审稿周期：约2个月 (即11月下旬出结果)



**NAACL (CCF-C)**: Annual Conference of the *North American Chapter* of the Association for Computational Linguistics

  截稿日期：约每年12月份

  审稿周期：约2个半月 (即2月下旬出结果)



**ACL (CCF-A)**: Annual Meeting of the Association for Computational Linguistics

  截稿日期：约每年3月份上旬

  审稿周期：约2个半月 (即5月中旬出结果)



**EMNLP (CCF-B)**: Conference on Empirical Methods in Natural Language Processing

  截稿日期：约每年5月份下旬

  审稿周期：约3个月 (即8月下旬出结果)



**CVPR (CCF-A)**: Conference on Computer Vision and Pattern Recognition

  截稿日期：约每年11月份中旬

  审稿周期：约3个半月 (即2月下旬出结果)



**ICCV (CCF-A)**: International Conference on Computer Vision 

  截稿日期：每两年开一次(奇数年)，举办年约每年3月份中旬

  审稿周期：约4个半月 (即7月下旬出结果)



**ECCV (CCF-B)**: European Conference on Computer Vision 

  截稿日期：每两年开一次(偶数年)，约每年3月份下旬

  审稿周期：约3个半月 (即7月上旬出结果)



**ACMMM(CCF-A)**: ACM International Conference on Multimedia

截稿日期：每年4月上旬

审稿周期: 约3个月(即7月下旬出结果)



#### 常用网站&工具

- [Multimodal论文](https://github.com/pliang279/awesome-multimodal-ml)

- [Image Captioning论文](https://github.com/zhjohnchan/awesome-image-captioning#2019)

- [Visual Grounding论文](https://github.com/qy-feng/awesome-visual-grounding)

- [一文纵览 Vision-and-Language 领域最新研究与进展](https://www.leiphone.com/news/201905/nJPT0qyibjtM09wE.html)

- [从 Vision 到 Language 再到 Action，万字漫谈三年跨域信息融合研究](https://mp.weixin.qq.com/s?__biz=MzA5ODEzMjIyMA==&mid=2247496394&idx=1&sn=22197341f2a5104b70ec9a6acee3d360&source=41#wechat_redirect)

- [Arxiv](http://www.arxiv-sanity.com/top)

- [Paper with code](https://paperswithcode.com/)

- [Google blog](https://ai.googleblog.com/)

- [AIdeadline](https://aideadlin.es/?sub=)

- [Overleaf](https://www.overleaf.com/project)

- Latex

- [张士峰学长分享](https://www.shenlanxueyuan.com/open/course/59)

- [CVPR Rebuttal](https://zhuanlan.zhihu.com/p/156994751)

- [画图：PPT，画神经网络图](https://www.zhihu.com/collection/361301272)

- [PPT制作（用于组会汇报）](https://zhuanlan.zhihu.com/p/148896017)

- [Grammerly](https://www.grammarly.com/)

- [Linggle](https://linggle.com/)

- [提高科研论文写作效率的小工具](https://zhuanlan.zhihu.com/p/34838403)

- [写公式神器](https://mathpix.com/):可截图自动转化成word&latex

- [下载数据集软件:Internet Download Manager](http://www.internetdownloadmanager.com):主要针对google drive,可断点下载

- ML-visuals：用于PPT制作（里面有别人画好的东西）https://github.com/dair-ai/ml-visuals

- 服务器-电脑传输数据：Windows: Winscp, MAC: Transmit

  

#### 代码训练

- [调参](https://www.zhihu.com/question/41631631/answer/1129785528)
- Numpy
- Pandas
- [新手教程](https://www.zhihu.com/question/55720139/answer/147148105)
- [Pytorch常用代码段](https://zhuanlan.zhihu.com/p/104019160)





## 入门pipeline

​	Step1：精读20篇+实现，然后把深度学习基础过一遍

​	Step2：领域新的东西泛读+精读过一遍然后做一些别人的idea（帮忙跑实验or洗数据or对方向进行调研 如果能在企业研究岗最好）

​	Step3:   开始想一些独立的idea去面向会议进行投稿研究，到投出第一篇为止就算度过freshman阶段。



5-20篇论文代表基本理解了相关主题，或许对于进一步理解技术实现足够了。[吴恩达读论文的方法]

50-100篇论文，你将会对这一领域有一个非常好的的理解。

**关注点**

1、Describe what the authors of the paper aim to accomplish, or perhaps did achieve.这篇论文作者的目标是什么，或者也许已经实现了什么。

2、If a new approach/technique/method was introduced in a paper, what are the key elements of the newly proposed approach?如果文中引入了一种新方法/技术，那么这一新提出的方法/技术的关键要素是什么？

3、What content within the paper is useful to you?论文中，有哪些内容对你有用。

4、What other references do you want to follow?你还想关注哪些参考资料/文献？



#### Step 1:深度学习基础(2 months)

- 《[动手学深度学习](http://zh.d2l.ai/)》
- 《[机器学习&深度学习](https://www.bilibili.com/video/BV1JE411g7XF?from=search&seid=4869695877227580366)》
- 西瓜书《机器学习》
- 花书《深度学习》
- 《统计机器学习》
- 《The book of why》探讨因果
- 林轩田-《机器学习基石》
- 斯坦福CS231n 视觉部分
- 斯坦福CS224n transform/generation部分
- [Tutorial on Multimodal Machine Learning](https://www.cs.cmu.edu/~morency/MMML-Tutorial-ACL2017.pdf)

#### Step 2: Week 1(2 months) 

需要对论文进行单步调试，搞懂模型。

	《Attention is all you need》
	
	《[Multimodal intelligence: Representation learning, information fusion, and applications](javascript:void(0))》综述

#### Week 2

	《Self-critical Sequence Training for Image Captioning》
	
	《Bottom-Up and Top-Down Attention for Image Captioning and Visual Question Answering》

#### Week 3

	《SCA-CNN-Spatial and Channel-wise Attention in Convolutional Networks》
	
	《Show, Attend and Tell--Neural Image CaptionGeneration with Visual Attention》
	
	[BLEU、Meteor、ROUGE、CIDEr 和 SPICE](https://www.jianshu.com/p/60deff0f64e1)

#### Week 4

	《Show, Control and Tell--A Framework for Generating Controllable and Grounded Captions》
	
	《[Spice: Semantic propositional image caption evaluation](https://link.springer.com/chapter/10.1007/978-3-319-46454-1_24)》
	
	《Knowing When to Look: Adaptive Attention via A Visual Sentinel for Image Captioning》

#### Week 5

	《[Unsupervised Image Captioning](https://arxiv.org/abs/1811.10787)》
	
	《[Conceptual Captions: A Cleaned, Hypernymed, Image Alt-text Dataset For Automatic Image Captioning](http://www.aclweb.org/anthology/P18-1238)》
	
	《Show and Tell: A Neural Image Caption Generator》

#### Week 6

	《BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding》
	
	《Corpus-Guided Sentence Generation of Natural Images》
	
	《Hierarchical Question-Image Co-Attention for Visual Question Answering》

#### Week 7

	《Baby Talk: Understanding and Generating Simple Image Descriptions》
	
	《Long-term Recurrent Convolutional Networks for Visual Recognition and Description》
	
	《[Auto-Encoding Scene Graphs for Image Captioning](http://openaccess.thecvf.com/content_CVPR_2019/html/Yang_Auto-Encoding_Scene_Graphs_for_Image_Captioning_CVPR_2019_paper.html)》

#### Week 8

	《Aligning Visual Regions and Textual Concepts for Semantic-Grounded Image Representations》
	
	《[Attention on Attention for Image Captioning](https://arxiv.org/abs/1908.06954)》
	
	《VL-BERT: Pre-training of Generic Visual-Linguistic Representations》

#### Week 9

	泛读当年CVPR所有论文(尤其是oral），可以思考其他领域和multimodal的关联，对整个AI发展有个趋势的认知。然后做一份阅读报告作为第一阶段的总结。



#### Step 3:Idea(2 months)

推荐的实习公司（2021版本）：腾讯AI lab，华为诺亚方舟，MSRA，商汤，京东AI，旷视，达摩院

不那么偏研究的地方：各大公司的工程岗，字节头条，阿里，微软



## 科研素质培养

2020年年会总结8点：

1. 每两周详细读一篇文章&代码，学习从现有方法到新方法的改进思路
2. 课余时间学点数学基础知识&看不懂数学多的论文的时候找看得懂的人交流
3. 多写代码，多尝试做模块代码迁移而非调参
4. 做一个任务的时候要找到靠谱的codebase，以及确保这个领域有比较靠谱的前人工作（针对现阶段的能力）
5. 多写论文，尝试脱离谷歌翻译写paper
6. 坚持自己方向的一贯性，把思维集中在一个领域
7. 多做中间结果（可视化，辅助实验），而不是最终结果
8. 把问题定义更加清晰，提高自己思想深度



- 每天早上刷刷arxiv：第一时间看到各个领域最新的文章，获取最新的科研进展。
- 论文分类整理：按照会议或方向，分类整理论文，方便高效查找论文。
- 保证每日科研效率：确保大块的连续的科研时间，如早上或晚上，无人打扰。



#### 追新论文&热点的渠道

一手消息：会议

二手消息：Arxiv

三手消息：知乎，公众号



#### 问题思考训练（评估问题的价值）

- [视觉的目的是什么？](https://www.bilibili.com/video/BV14V411B7av?t=1)

- 怎么去评估一篇论文能否被顶会接受？[做研究与写论文by fenglinliu]

- Reviewer Slides for CVPR 21 

  

#### 神经网络模型绘画



#### 可视化



#### 组会PPT&学术汇报制作经验

- 首先安利下自己的北大风格的Beamer主题：https://github.com/inFaaa/PKU-Beamer-Theme



#### Rebuttal

​			

#### 靠谱的多模态任务codebase

#### 提高GPU资源的使用率（多卡/单卡）



#### 多模态热点方向（按年度）

2020年： Unsupervised/semi-supervised+multimocal

 可控制的image caption/visual grounding

 visual reasoning（Scene graph+VQA)

 visual grounding+传统CV/NLP任务

视觉语言预训练模型



2021年：切忌只是对Transformer的魔改已经很难中论文了

因果+Multimodal

Symbolicism+multimodal

New image Caption

