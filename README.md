# 浅梦的学习笔记 公众号文章汇总
![visitors](https://visitor-badge.glitch.me/badge?page_id=shenweichen.AlgoNotes)
## 目录
-  [排序&CXR预估](#排序CXR预估)  
-  [召回匹配](#召回匹配)  
-  [用户画像&特征工程](#用户画像特征工程)  
-  [精彩讨论&知识沉淀](#精彩讨论知识沉淀)
-  [推荐搜索综合](#推荐搜索综合)  
-  [计算广告](#计算广告) 
-  [大数据](#大数据)  
-  [图算法](#图算法)  
-  [NLP&CV](#NLPCV)  
-  [求职面试](#求职面试)


<html>
    <table style="margin-left: 20px; margin-right: auto;">
        <tr>
            <td>
                公众号：<b>浅梦的学习笔记</b><br><br>
                <a href="https://github.com/shenweichen">
  <img align="center" src="./code.png" />
</a>
            </td>
            <td>
                微信：<b>deepctrbot</b><br><br>
 <a href="https://github.com/shenweichen">
  <img align="center" src="./deepctrbot.png" />
</a>
            </td>
                        <td>
<ul>
相关项目：
<li><a href="https://github.com/shenweichen/DeepCTR">DeepCTR</a></li>
<li><a href="https://github.com/shenweichen/DeepMatch">DeepMatch</a></li>
<li><a href="https://github.com/shenweichen/DeepCTR-Torch">DeepCTR-Torch</a></li>
<li><a href="https://github.com/shenweichen/GraphEmbedding">GraphEmbedding</a></li>
</ul>
            </td>
        </tr>
    </table>
</html>
  
  
## 排序&CXR预估
- [DCN-M：Google提出改进版DCN，用于大规模排序系统的特征交叉学习(附代码)](https://mp.weixin.qq.com/s/0qidwbxyfTkODTw2DIiRWw)  

- [分类模型与排序模型在推荐系统中的异同分析](https://mp.weixin.qq.com/s/pM2dDVT7gLWbAxxMU011BQ)
- [推荐系统中的排序学习](https://mp.weixin.qq.com/s/qQGFthzM5NAwk-8Wpgg_Rg) 
- [CIKM20 | 阿里MiNet：跨域点击率预估混合兴趣模型](https://mp.weixin.qq.com/s/jkGb_qkfmEOEs030ZRIJIw) 
- [KDD19 | 微软DeepGBM:使用树蒸馏提升在线预测任务下深度模型效果](https://mp.weixin.qq.com/s/NBVPlFGO12PhMTF0dUL2hw) 
- [推荐系统rank模块-Online Learning](https://mp.weixin.qq.com/s/eKoFhICd45B8hSsEWXO4Gw) 
- [IJCAI19 | 推荐系统论文DSIN：Deep Session Interest Network](https://mp.weixin.qq.com/s/kGWiRH6ntSmNTLhAG49AbQ) 
- [Life-long兴趣建模视角CTR预估模型：Search-based Interest Model](https://mp.weixin.qq.com/s/1bfgx2syzt-ol-Qw3ZO7Yg) 
- [Ctr 预估之 Calibration](https://mp.weixin.qq.com/s/pWmxVhN77W10UrHgCiffGA) 
- [AAAI20 | 阿里DMR:融合Match中协同过滤思想的深度排序模型](https://mp.weixin.qq.com/s/48yKFGtV0_Jo4ntGfNUR7w) 
- [线下auc涨，线上ctr/cpm跌的原因和解决办法
](https://mp.weixin.qq.com/s/0NnJ4a87sTwJjfcMcEFVjg) 
- [【视频讲解】DeepCTR中的xDeepFM原理和实现](https://mp.weixin.qq.com/s/t4gwYkw3yoxAwhLGeqsh7g) 
- [【视频讲解】DeepCTR中的Deep&Cross Net原理和实现
](https://mp.weixin.qq.com/s/f-cCowZAM5mQbkwFkrC8VA) 
- [【视频讲解】DeepCTR中的Wide&Deep原理和实现
](https://mp.weixin.qq.com/s/FQairytK3xqlDG2nDwEY1g) 
- [【视频讲解】DeepCTR中的DeepFM原理和实现](https://mp.weixin.qq.com/s/Xa9rxEC4IGhaAFRJ5HdPfw) 
- [常见CTR论文挑刺
](https://mp.weixin.qq.com/s/4Jbqp0z7y4G5yF4EFJMamw) 
- [万字长文梳理CTR预估模型发展过程与关系图谱
](https://mp.weixin.qq.com/s/TEi9SzeKh7YK84oO1v2wFA) 
- [Evolution of CTR prediction models
](https://mp.weixin.qq.com/s/3CP_CZp8GcDwjluOq1tEVg) 
- [AAAI19 | 谷歌SNR: 灵活参数共享的多任务学习网络
](https://mp.weixin.qq.com/s/FN4MjH9AmgfcjnZBHeRAKw) 
- [CIKM19 | 如何刻画用户的多样兴趣——阿里MIND阅读笔记](https://mp.weixin.qq.com/s/kgkw4INFbcf98gwHUAfimw) 
- [CIKM19 | Fi-GNN 通过图神经网络建模特征交互作用来进行CTR预测
](https://mp.weixin.qq.com/s/lVTteAO4zULPcJitfsD8LQ) 
- [WWW18 | TEM:结合GBDT叶节点嵌入的可解释推荐模型](https://mp.weixin.qq.com/s/SEvfWmaoJKLChRZhlbECIg) 
- [教你玩转deepctr的FLEN模型& Kaggle Avazu实验对比
](https://mp.weixin.qq.com/s/EO49-cKEPtEBTrj3GR49yw) 
- [浅谈流式模型训练体系](https://mp.weixin.qq.com/s/Me1WAMdNaTURwOoYx3djRQ) 
- [【CTR预估】FLEN: 一种时空高效的利用特征场信息缓解梯度耦合的CTR预测模型
](https://mp.weixin.qq.com/s/zChpiwv3RCILlaqEKmB8Og) 
- [【CTR预估】CTR模型如何加入稠密连续型和序列型特征？
](https://mp.weixin.qq.com/s/ECn5kCrx7WtD0wpuGF_YwQ) 
- [【CTR预估】你真的需要 pairwise LTR吗？速览搜索推荐中pointwise和pairwise方法
](https://mp.weixin.qq.com/s/EBRbZebLdLRx5R_ZwQwioA) 
- [Learning to rank基本算法小结
](https://mp.weixin.qq.com/s/KDWuTQof-ma36aC1UB_34g) 


## 召回匹配
- [Embedding 技术在民宿推荐中的应用](https://mp.weixin.qq.com/s/yCugvGJw9-6-WLZumtJ-TA) 

- [EMBEDDING 在大厂推荐场景中的工程化实践](https://mp.weixin.qq.com/s/8Mx8CznNBlJ6adlwXbcHXQ) 
- [KDD18 | 阿里新一代召回系统TDM读后感](https://mp.weixin.qq.com/s/TgmVBA3SBmCvM8Z2jkjdrw) 
- [再评Airbnb的经典Embedding论文](https://mp.weixin.qq.com/s/RF3g-6ecfpetbvEfA97YrA) 
- [推荐系统召回层做离线评估的一种姿势](https://mp.weixin.qq.com/s/ECXz_GyVVsZdDJJeVPq4gA) 
- [SIGIR20 | 一文综述Learning to Match各种方法对比](https://mp.weixin.qq.com/s/zDGPpwBdQrVOMG3lLjjXOw)
- [推荐系统主流召回方法综述](https://mp.weixin.qq.com/s/Kxf_VX8cyN4vvveEPB1mcg) 
- [一文梳理推荐系统的中 EMBEDDING 的应用实践](https://mp.weixin.qq.com/s/2JuyVJos2RrqGKcVgZRZvA) 
- [Faiss - 常见问题总结](https://mp.weixin.qq.com/s/Id1XVK86uabbXNRIuqWYLw) 
- [CIKM18 | CFGAN：基于生成对抗网络的协同过滤框架](https://mp.weixin.qq.com/s/ltkCK0cbNWZjGSHXjaH29w) 
- [从 Triplet loss 看推荐系统中文章Embedding](https://mp.weixin.qq.com/s/iJwNuaBm7TrEo2FEJPqx4w) 
- [SDM(Sequential Deep Matching Model)的复现之路](https://mp.weixin.qq.com/s/FRh5iHrd6HfZ4-pF3bRxnw) 
- [RecSys19 | 谷歌最新双塔DNN召回模型——应用于YouTube大规模视频推荐场景
](https://mp.weixin.qq.com/s/u-W3r0qgSejozdooERW9hg) 
- [向量化召回在360信息流广告的实践
](https://mp.weixin.qq.com/s/LDcULfWi3ryYvUVtrp6Q7g) 
- [DeepMatch ：用于推荐&广告的深度召回匹配算法库
](https://mp.weixin.qq.com/s/sMSMmobMJ8WLiGxhFWvp0Q) 
- [【DeepMatch教程】YoutubeDNN在MovieLen1M数据集上进行向量召回
](https://mp.weixin.qq.com/s/sMSMmobMJ8WLiGxhFWvp0Q) 
- [KDD19 | 算法调研-微信看一看Embedding
](https://mp.weixin.qq.com/s/TWq5m_E6EUEtCeL7ma6Peg) 
- [CIKM18 | Ripple Net:融合知识图谱的推荐模型
](https://mp.weixin.qq.com/s/-pzY_7lsmDzPC-REWp7zKA) 
- [跨境电商Etsy如何使用交互行为类型进行可解释推荐](https://mp.weixin.qq.com/s/D9-jm4-cwcNjGGOfCyCtZg) 
- [搜索推荐中的召回匹配模型综述(一)--传统方法
](https://mp.weixin.qq.com/s/4M1OkxeSC200qhlqequb2w) 
- [搜索推荐中的召回匹配模型综述(二)--基于表示学习的深度学习方法](https://mp.weixin.qq.com/s/qd_qSdqnxwL55_S55OW3Fg) 
- [搜索推荐中的召回匹配模型综述(三)--基于匹配函数学习的深度学习方法](https://mp.weixin.qq.com/s/dWvnqp5ZLe4rU_pWH2bnNQ) 


## 用户画像&特征工程

- [⾼维特征的哈希技巧总结](https://mp.weixin.qq.com/s/mOTfkA_BIg0tx0p1S4hT1Q) 

- [SIGIR20 | 超越用户embedding矩阵：用哈希对大型用户建模
](https://mp.weixin.qq.com/s/h0pK8b82rrerTwzDzOUW7A) 
- [浅谈电商搜索推荐中ID类特征的统一建模：Hema Embedding解读](https://mp.weixin.qq.com/s/iMU2LPDadmVMgzUifw3-XA) 
- [用户画像必会的行为偏好计算方法
](https://mp.weixin.qq.com/s/orT91nj1Xz3Lxe22--PqCw) 

## 精彩讨论&知识沉淀
- [学习交流小组精彩内容摘要 No.21](https://mp.weixin.qq.com/s/pfw1yeed7hGK-Q6nyGQx-w) 

- [学习交流小组精彩内容摘要 No.20](https://mp.weixin.qq.com/s/C4A_mmaAFnPZOky382XaSw) 
- [学习交流小组精彩内容摘要 No.19](https://mp.weixin.qq.com/s/0UUcplCtgd7AGK5JASoKZA) 
- [学习交流小组精彩内容摘要 No.18](https://mp.weixin.qq.com/s/kUGMR2ty_urF5j8vjGQ_DQ) 
- [学习交流小组精彩内容摘要 No.17](https://mp.weixin.qq.com/s/AMzOcQyURtnS5axCdYx6UQ) 
- [学习交流小组精彩内容摘要 No.16](https://mp.weixin.qq.com/s/7qsRtLs4AtmAOrBUHuxf9g)
- [学习交流小组精彩内容摘要 No.15](https://mp.weixin.qq.com/s/0McGiE9REhaEz3QoYT7-YQ)
- [学习交流小组精彩内容摘要 No.14](https://mp.weixin.qq.com/s/taxzzaYlRHmjW_pPC02vQA)
- [学习交流小组精彩内容摘要 No.13](https://mp.weixin.qq.com/s/1XZMAYPHPCGjerA1iJl9Ag)
- [学习交流小组精彩内容摘要(06.12-06.18)](https://mp.weixin.qq.com/s/minWDYM8b7Ek-Vb3FPuelw)
- [学习交流小组精彩内容摘要(06.09-06.11)](https://mp.weixin.qq.com/s/j6O8KzYWsxW-5fWbyz-hOg)
- [学习交流小组精彩内容摘要(06.05-06.08)](https://mp.weixin.qq.com/s/SNmiDDCJiskRlBqLXuV0kg)
- [学习交流小组精彩内容摘要(05.31-06.04)](https://mp.weixin.qq.com/s/jvqfxonEBlrrkobHfxZ8PA)
- [学习交流小组精彩内容摘要(05.25-05.30)](https://mp.weixin.qq.com/s/uJqY_DYEAwKI0fHA7s8pXg)
- [学习交流小组精彩内容摘要(05.21-05.24)](https://mp.weixin.qq.com/s/_pgnB7zioxxX5A_hxV52lw)
- [学习交流小组精彩内容摘要(05.18-05.20)](https://mp.weixin.qq.com/s/yaimSlvmG6kseqSLY6hcXQ)
- [学习交流小组精彩内容摘要(05.14-05.17)](https://mp.weixin.qq.com/s/dpugb2_3i4M31FWYuFcd5Q)
- [学习交流小组精彩内容摘要(05.08-05.13)](https://mp.weixin.qq.com/s/SLafxvWm5izflGJX6qe7vA)
- [学习交流小组精彩内容摘要(01.21-02.06)
](https://mp.weixin.qq.com/s/mvFv907DiICFV8tTB_9EYA)
- [学习交流小组精彩内容摘要(01.13-01.20)](https://mp.weixin.qq.com/s/WjzvyUmOissSSGITS34UZQ)
- [学习交流小组精彩内容摘要(01.04-01.12)
](https://mp.weixin.qq.com/s/m3Az_8aE9KYbYH5CcOuoyA)

## 推荐搜索综合
- [低频少样本长验证周期场景下的算法设计](https://mp.weixin.qq.com/s/dwptlx8UGNq8-WzEWRLspA) 

- [基于行列式点过程的推荐多样性提升算法](https://mp.weixin.qq.com/s/9DZvs82Da3kbfuUvpHuIdw) 
- [推荐系统评价：什么是好的推荐系统](https://mp.weixin.qq.com/s/3DCkAAsl-CO1QmYDZz454A)
- [万字长文解读电商搜索——如何让你买得又快又好](https://mp.weixin.qq.com/s/1hc7G4eBSyk-b8Dv4FsYbg) 
- [工业界推荐系统实用分析技巧](https://mp.weixin.qq.com/s/UUb7esHxhdauAdwNR8TwTQ) 
- [KDD20 | 推荐系统论文一览](https://mp.weixin.qq.com/s/OIZm5UPv7f-I66vKBgyVEw)  
- [搜索广告之自动化创意](https://mp.weixin.qq.com/s/ewb9IlqPmQgfXGEUSRNXwQ) 
- [KDD CUP 2020之Debiasing赛道方案 (Rush)](https://mp.weixin.qq.com/s/Xz505pzM4U8k0vnQjkENrg) 
- [推荐系统研究中常用的评价指标
](https://mp.weixin.qq.com/s/6TDCk0zwE8v-DLwSbk05hQ) 
- [推荐多样性重排算法之MMR
](https://mp.weixin.qq.com/s/7V4b6dPPqBdTfFjDj1gDzw) 
- [推荐系统技术演进趋势：从召回到排序再到重排
](https://mp.weixin.qq.com/s/nHzQM_le5a1POaAtwHMJbw) 
- [推荐系统的发展与简单回顾
](https://mp.weixin.qq.com/s/E11Nm8LlsbKcLIJ82NgzUg) 
- [万字长文！推荐系统岗面试经验&学习心得](https://mp.weixin.qq.com/s/zf7eRE57vsFxL_jGVdqV9g) 



## 计算广告
- [计算广告OCPC算法实践(一) 智能出价PID控制中的偏差与响应函数设计](https://mp.weixin.qq.com/s/xD4tlVXX8w-pMk_JJF-vTA) 
- [《计算广告》学习笔记](https://mp.weixin.qq.com/s/hUK0QN4UFonKJWWwZF-u-Q) 

- [OCPC 广告算法在凤凰新媒体的实践探索](https://mp.weixin.qq.com/s/bD73FrOE9teRXMD_bIh-JQ)  
- [计算广告发展历程——从CPC到oCPX](https://mp.weixin.qq.com/s/Sq9iAYi8mCqzFnXdar4aCg) 
- [百度凤巢新一代广告召回系统——“莫比乌斯”](https://mp.weixin.qq.com/s/kdkz6MOrIo9ih-d1hBBNRg) 
- [广告出价--如何使用PID控制广告投放成本](https://mp.weixin.qq.com/s/5a5RhhUmaeBjNjerdxmY3g) 
- [PID控制算法原理（抛弃公式，从本质上真正理解PID控制）](https://mp.weixin.qq.com/s/i8WryZOjMhEMp7Gno3dXcw) 
- [广告和推荐排序中消除position bias的方法](https://mp.weixin.qq.com/s/WyztaAiciTWoNl5ODFWJyA) 
- [oCPC：计算广告出价策略](https://mp.weixin.qq.com/s/LgZ3aWlXtvC41mv3ThJPAQ) 
- [广告点击率CTR修正-Wilson CTR
](https://mp.weixin.qq.com/s/vUwtVwdozsYBV0GI2wWtPg) 

## 大数据
- [实时数据流计算引擎Flink和Spark剖析](https://mp.weixin.qq.com/s/FX7wFly3CpFEpwWLBlFQeQ)  

- [Spark 的一些人生经验](https://mp.weixin.qq.com/s/rff5AAd9w85N-MFVxyNKbg) 
- [大数据kafka理论实操面试题](https://mp.weixin.qq.com/s/847kcDXE-Iq8JXjG_-Fehg) 
- [Kafka 应用实践与生态集成](https://mp.weixin.qq.com/s/YcLk_5kIoIc1ho6RB7FcpQ) 
- [Flink 中文社区年度文章合集](https://mp.weixin.qq.com/s/hVfCbiWAwgjAAMmAwNNrVA)


## 图算法 

- [一文直击Graph Embedding图表示学习的原理及应用](https://mp.weixin.qq.com/s/F9zt7eyHxTX7Gp0zpvnfcg)

- [【GraphEmbedding】DeepWalk算法原理，实现和应用
](https://mp.weixin.qq.com/s?__biz=MjM5MzY4NzE3MA==&mid=2247484661&amp;idx=1&amp;sn=360ed3d2f4bb9a0d11bbd821e7ede72e&source=41#wechat_redirect) 
- [【GraphEmbedding】LINE：算法原理，实现和应用
](https://mp.weixin.qq.com/s?__biz=MjM5MzY4NzE3MA==&mid=2247484657&amp;idx=1&amp;sn=2c16508270ebef54000d0b272a348cef&source=41#wechat_redirect) 
- [【GraphEmbedding】node2vec：算法原理，实现和应用
](https://mp.weixin.qq.com/s?__biz=MjM5MzY4NzE3MA==&mid=2247484653&amp;idx=1&amp;sn=3de60375e524f4d0ef6c84eec01e709b&source=41#wechat_redirect) 
- [【GraphEmbedding】GraRep：基于矩阵分解的图表示学习](https://mp.weixin.qq.com/s/aD-YbniflGUbgwiUthWNwg) 
- [【GraphEmbedding】SDNE算法原理，实现和应用
](https://mp.weixin.qq.com/s?__biz=MjM5MzY4NzE3MA==&mid=2247484587&amp;idx=1&amp;sn=12258faf39493f73e1c07523ff8f1145&source=41#wechat_redirect) 
- [【GraphEmbedding】Struc2Vec算法原理，实现和应用
](https://mp.weixin.qq.com/s/XcnrbLeXggXiynnzpr657w) 
- [【GNN】一文读懂图卷积GCN](https://mp.weixin.qq.com/s/dOD0-9oEwoFjvmb5igYSMQ) 
- [【GNN】GCN 算法原理，实现和应用
](https://mp.weixin.qq.com/s?__biz=MjM5MzY4NzE3MA==&mid=2247484633&amp;idx=1&amp;sn=c1b33d03e05653ab62d14a9fa9c3a108&source=41#wechat_redirect) 
- [二部图表示学习 | Graph Convolutional Matrix Completion](https://mp.weixin.qq.com/s/hICjiAyzh-Cv6226HMvHAg) 
- [node2vec随机游走优化思路和代码实现](https://mp.weixin.qq.com/s/n_EveU9G_MRwuSHW5kyWkw) 
- [【斯坦福CS224W 图与机器学习(1-2)】：图模型基本介绍
](https://mp.weixin.qq.com/s/wxvFtXeQhjPhTAlDeSMPpA) 
- [【斯坦福CS224W 图与机器学习 3】：Motifs and Structural Roles](https://mp.weixin.qq.com/s/czfwcklVtLpvONwXZADP0A)
- [KDD19 DGL教程：Recommender System with GNN
](https://mp.weixin.qq.com/s/lKLLzzQZfvGRtmCgbnptTQ)
- [社交图谱的标签传播算法](https://mp.weixin.qq.com/s/cqEpA-IAzh2Y5Yz0PTU4vA) 


## NLP&CV
- [【论文串讲】从BERT和XLNet到MPNet](https://mp.weixin.qq.com/s/Lnid-DFMI54Tw_oOi37mjA) 

- [预训练模型系列-通用预训练MASS](https://mp.weixin.qq.com/s/noNrZK8DjQHy0FrSyEWuXA) 
- [【论文串讲】从GPT和BERT到XLNet](https://mp.weixin.qq.com/s/weargDvogar3fTqSDIM7LQ)
- [Transformer 超详细解读，一图胜千言](https://mp.weixin.qq.com/s/6RPxTdDcxJ050oAp34Ofdw)
- [【经典精读】Transformer模型深度解读](https://mp.weixin.qq.com/s/Cs0UDQmeqwb3dn1ivawb3w)
- [word2vec模型深度解析
](https://mp.weixin.qq.com/s/yQLL0jkk-q7PHKieF8S0bA) 
- [NLP与推荐系统的比较、联系与未来
](https://mp.weixin.qq.com/s/47tGHoeqGWtpRjzRePjZxg) 
- [知识图谱入门系列](https://mp.weixin.qq.com/s/LTeD9I65q3FIiFymhMhGEA) 
- [知识图谱基本概念&工程落地常见问题
](https://mp.weixin.qq.com/s/AJTIkWGspauKgjB3-gdxoA) 
- [本科生晋升GM记录 & kaggle比赛进阶技巧分享
](https://mp.weixin.qq.com/s/9gdxH4M_Ud7cq81rSew--g) 
- [9102年入门GAN的补习
](https://mp.weixin.qq.com/s/zLyoNQLLLHx8Y_EuDcMwWA) 
- [快速掌握TensorFlow中张量运算的广播机制](https://mp.weixin.qq.com/s?__biz=MjM5MzY4NzE3MA==&mid=2247484662&amp;idx=1&amp;sn=cc69e90edca39539fd4cf17aeea39617&source=41#wechat_redirect) 


## 求职面试
- [你见过最差的算法工程师能差到什么程度？](https://mp.weixin.qq.com/s/Z9Sczo3jYW7nJolt696slw)  

- [我的求职经验总结](https://mp.weixin.qq.com/s/tcg2_UlP-hm29Rd5tgARLg) 
- [求职面试 | 《剑指Offer》Python题解&常考题总结
](https://mp.weixin.qq.com/s/PdlRCvf0dRlSgkh7cO0pEw) 
- [非科班如何拿到外企和国内大厂SSP Offer的？](https://mp.weixin.qq.com/s/I3mD5QbixIShti0zKKt5bw) 
- [实验小师弟的新鲜春招面经(阿里搜索，微信，微软等)](https://mp.weixin.qq.com/s/sw7G6s1cgwWiiX7nTxm_YQ) 
- [Facebook、AWS、Google、Microsoft面试小记](https://mp.weixin.qq.com/s/Aemb65Id4b_kKMziJF1XKw)
- [算法工程师当前选哪个方向好？1，CV；2，NLP；3，推荐系统？](https://mp.weixin.qq.com/s/O8HHeUL0D9-NNB8-MRPbdA)
- [番外篇——社招如何拿到心仪公司的offer](https://mp.weixin.qq.com/s/ppx_Y9Gg6FeDyRv9gqgCVw)

