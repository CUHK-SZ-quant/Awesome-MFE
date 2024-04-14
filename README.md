# Awesome-MFE

港中深美国 top MFE 项目申请指南

不定期更新，点击右上角 star 获取更新信息

## 选校安排

基于 [Quantnet Ranking](https://quantnet.com/mfe-programs-rankings/)、录取者的背景、录取者的最终选择、项目近几年的去向，以及若干 top MFE 项目校友的综合评价，以下是个人美国 top MFE 项目的排名：

- Tier 0: Baruch MFE, Princeton MFin
- Tier 1: UCB MFE, CMU MSCF, Stanford MS\&E
- Tier 1.5: Columbia MFE, NYU Finmath, MIT MFin
- Tier 2: Columbia MAFN, Cornell MFE
- Tier 3: UChicago FM, NYU MFE, UCLA MFE, GaTech QCF

英国、新加坡、欧洲、香港等的一些热门项目：

- UK: Oxford MCF, LSE Finmath, IC RMFE
- Singapore: NUS MFE, NUS MQF, NTU MFE
- Europe: ETH MQF
- HK: HKU MFin, HKUST Finmath, CUHK RMDA

### 申请定位

1. 可以参考各大 MFE 项目公布的录取学生的 resume book:

- [Columbia MAFN](resume_book/Columbia-MAFN/Columbia-finmath-2018.pdf)
- [NYU Courant FinMath](resume_book/NYU-Courant)
- [Princeton MFin](resume_book/Princeton)
- [UCB MFE](resume_book/UCB)

2. Quantnet tracker: https://quantnet.com/tracker - 全球的MFE application information.

## 修课计划

总而言之，建议上的课程：

- 数学：微积分\*2，线代，最优化，离散数学，概率论，常微分，偏微分，数值分析，随机微分等
- 统计：概率统计\*2，随机过程，时间序列，计量，回归分析，机器学习，深度学习等
- CS：Python，C++，数据结构，数据库等
- 金融经济：财务管理，微经，宏经，投资组合管理，期权期货，固定收益等

Credit to Songhao (MIT MFin)，仅供参考：

<img src="./imgs/course.jpg" width="650">

一些有用的资料链接：

- [申研课程背景提升：UCB MFE Checklist](https://mfe.haas.berkeley.edu/admissions/prerequisites)
- [量化水平提升：QTIA 修课建议](https://mp.weixin.qq.com/s/QLJxe6mqB6g_tmdvmpFJyA)

## TOEFL & GRE

**GRE 经验分享帖**

- [Bradley Yang: GRE 162+170+4.5](https://www.zhihu.com/question/499380225/answer/2722956671)
- [Ben Li: GRE 166+170+3.5](https://zhuanlan.zhihu.com/p/448738149)
- [Eric Lan: GRE 164+170+3.5](https://zhuanlan.zhihu.com/p/386356094)

## MFE 面试准备

以下列出部分 2024 fall 的 MFE 项目的面试内容（往后可能会调整）：

- Princeton MFin：Quant Assessment + 两轮真人面试（行为+技术）
- Baruch MFE：Quant Assessment + 两轮真人技术面
- UCB MFE：Kira 抽题录制（较固定） + 一轮真人技术面
- CMU MSCF：提前给题目三次录制机会 + 一轮真人行为面
- MIT MFin：录制两个 video，一个自行上传一个随机 Kira + 一轮 Quant Assessment (水) + 一轮真人行为面
- Columbia MFE：填完网申后跳出 Kira 面，三个行为面试题，一次准备+录制的机会
- Cornell MFE：填完网申后海发 Kira 面，五个行为面题，一次机会，无准备时间
- UChicago FM：三个 video 问题，时长要求不同，自行录制上传
- NYU Finmath：一个 5min 的长 video 录制上传
- NYU MFE：挑选一个指定问题并录制上传 video，无其他面试

### 行为面试

#### **机器面试**

面试形式常为：1. 录制 video 上传，2. Kira 机器面试。录制比较简单基础，Kira 面试类似 TOEFL 的 Speaking 部分，绝大多数考察基础的口语表达能力，只要不是讲的太差都不会有太大问题。总体的一些注意事项：

1. 注意着装，看镜头，不要读稿
2. 注意光线，环境安静，如果有后期空间可以自行调节亮度
3. 容易紧张或卡壳可以降低语速，并搭配手势

#### **真人面试**

真人行为面包括 CMU，MIT，GaTech 等，其内容风格和占比权重各异：
- CMU MSCF：淘汰型面试，大规模发面试，但是只选择少部分人录取。面试题目固定，在整个评核中占比不高
- MIT MFin：真人行为面占据绝对比重，面试官评核方式主观不可控，面试淘汰率超过 75%

此处重点介绍 MIT MFin 的面试准备 tip，部分内容 credit to Eddie (MIT MFin)：

1. 面试最重要的是展现你的energy，你需要足够自信
2. 注意房间的回音、收音、光线问题，本人就直接被面试官指出耳机有电流声（麻
3. 开场时面试官会习惯性的开一些small talk，不要过于紧张，让自己看起来自然一点
4. 对方大概率并不理解你简历里面的terminology，学会把专业性的东西用简单的语言表达
5. 描述一个project时，内容具体外，使用总分总的逻辑表达，并和soft skills挂钩
6. 注意面试的flow，适当的增添对话引导。能够逗笑面试官是一件很加分的事情



### 技术面试

以 Baruch MFE 和 UCB MFE 的技术面中考察的内容的难度和频率，对课程进行主观的分类，星越多表示技术面中越常见/重要：

- 微积分 ⭐⭐⭐⭐⭐：求导，隐函数求导，一元和多元积分，多元积分换元
- 线性代数 ⭐⭐⭐⭐⭐：特征值，trace，正定矩阵
- 概率 ⭐⭐⭐⭐⭐：期望，MGF，正态分布
- 期权 ⭐⭐⭐⭐⭐：BS 公式，Dividend 影响，Greeks，Convexity
- ODE ⭐⭐⭐⭐⭐: 一元二次齐次 ODE
- 编程 ⭐⭐⭐⭐：Python，Pandas，C++
- 回归分析 ⭐⭐⭐⭐：OLS回归，模型假设，异方差性
- Brain Teaser ⭐⭐⭐⭐：参考绿皮书和黄皮书，通常和概率一起考察
- PDE ⭐⭐⭐：如果没学过一般不会问
- 数值分析 ⭐⭐⭐：往年主要问 Newton method
- 机器学习 ⭐⭐⭐：有机器学习背景可能被问
- 时间序列 ⭐⭐⭐：学过这门课可能被问，如 ARMA 公式和原理
- Economics ⭐⭐：遇到过问对美国市场的了解的，道指和标普

- Live coding

**我们认为技术面考察的真正内容**：

* Reactions to one problem
  * Thinking patterns
  * Thinking perspectives
* Understanding of basic concept
* Communication ability
  * Make sure you fully understand the question. If not, ask immediately.
  * It’s ok to tell them you don’t know and ask for hint.
  * But make sure your thinking is a bit faster than the interviewees.
  * Tell them all your thinkings or even guesses about this problem and they will guide you.

* 记得写follow-up thank-you letter
 
#### UCB MFE

1. **校友面试**：UCB MFE的技术面试整体比较简单。面试官会根据你的背景寻找比较匹配的校友。比如如果你的ML经验比较多，就会偏向找机器学习工程师的校友面试你；如果你的背景是纯金融，那么他们也会找毕业后没做quant的校友，比如去KKR的校友面试你。
2. **面经和题目**：整体而言网上面经的参考价值不大，不同背景的问题从衍生品到机器学习到甚至fama-french factor model都可能问到。可以预料的是一些基础的线代、积分、衍生品的题目，只要都复习到了问题就不大，但是也有例外情况，比如本人就被考了一道算法题，并且给了三次hint都没有答出来…… 大概是从一堆0,1矩阵中寻找最大固定尺寸的子矩阵使得包含最多的1的方法，使用recursion求解。不过最后面试还是过了，因此不用太过担心这些比较偏门的题目。
3. **面试口音**：UCB很多的面试官是印度人，这就导致整体对话可能会进行的比较艰难，因此需要提前做好心理准备。本人当时就到了甚至需要在聊天框打出来说的是什么的地步了……

#### Baruch MFE

1. **QBA**：

  * No cutting edge
  * Only a tool for them to know you better
  * 时间：45分钟；形式：填空题；zoom中统一考试；[考点范围](https://mfe.baruch.cuny.edu/wp-content/uploads/2022/10/QBA-Review-Topics.pdf)
  * Open book, Open internet, Chatgpt is not allowed; 考完即出成绩
  * 考前会有专门说明会
  * 切记勿外传qba题目，一旦被发现直接拒

2. **第一轮**：

  * 第一轮不同的面试官的风格比较大。
  * 

 第一轮不同的面试官的题目差距比较大。如果是Andrew，偏向问一些课程内的东西，比如时间序列、ODE等等；然而如果是Rados，就比较难受。本人的一轮是Rados面试，就是baruch著名黄皮书的编著人之一的俄罗斯人。面试一开始直接发了个PDF，里面8个题，涉及线代、option arbitrage、回归分析、二项分布等等，20分钟时间，能做的越多越好。很多时候不用算出具体结果，对方觉得你的思路对就move on了，题目整体还是比较简单的，我当时做了7/8，对方比较满意就直接让我过了。


- **Round 2**：著名的Dan Stefanica的压力面。综合我查到的各种面经，我的面试体验，以及朋友的面试体验，有如下几点建议：
  1. **建议尽早投递**。我是r4面的，题目明显比其他r1，r2的同学面试难很多。前两轮投递的话Dan至少还会问一些概念性的问题，比如matrix trace/determinant等等，最后一轮就是直接上强度。我最后有两个题都没有完整做出来，对心态是很大的考验。因此准备好了就尽早的投递。round 3和round 4的难度会明显提升，round 2的面试时间会和UCB，MIT，CMU等撞车，因此round 1就是最佳选择。
  2. **说清楚思路**。任何任何思路，想到就说，对错无所谓。如果Dan看到你的思路不对，可能会move on，也可能会给你一些hint。哪怕是最简单的，比如考虑一种特殊情况下的分类讨论，都会比什么都不说好。
  3. **Think fast, move fast**。 面试时间只有30min，Dan不希望你坐在那里一直思考，他想过尽可能多的题目。因此，你需要给出非常快的feedback，并且根据他的hint及时的调整你的做法。虽说多数人反应Dan的压力面非常恐怖，但本人的体验其实还好，对方的语速快，但其实也是在比较正常的level，并且发音也不会出现听不清的情况。

#### Princeton MFE

## 职业发展道路了解

- [Steven Shreve: Careers in Quantitative Finance](https://apply.mscf.cmu.edu/article/steve-shreve-industry-brief.pdf)
- [Emanuel Derman: My Life as a Quant](https://download.e-bookshelf.de/download/0000/5845/30/L-G-0000584530-0002384412.pdf)
- [QuantNet Threads: My Life as a Junior Quant](https://quantnet.com/threads/im-a-junior-buyside-quant-trader-ama.53762/)
- [QuantNet Threads: My Life as a Senior Quant](https://quantnet.com/threads/im-a-senior-buy-side-quant-researcher-ama.53587/page-2)
- [Buy-Side Quant Job Advice](https://www.reddit.com/r/quant/comments/1b2tnsi/buyside_quant_job_advice_by_giuseppe_paleologo/)