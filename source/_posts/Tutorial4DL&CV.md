---
title: 深度学习、计算机视觉入门和技能经验
description: '写给拟加入本课题组开展学习研究的同学'
date: 2023-10-12 11:30:55
tags:
	- 深度学习
    - 机器学习
categories: 学习
---

## 知识入门篇

### 说在前面

选跟一个优质的公开课或简明教程有助于学科入门。学会提问是开始研究的第一步，若大脑没有一定的信息输入和内化积累，很可能迷茫到“连自己的问题是什么都不知道”的地步，更别提下一步应该学什么、研究什么。老师和学生仅仅是“闻道有先后”的区别，每个人都有可能成为领域小专家并获得大家的尊重，成长为靠谱的合作伙伴。

“Slow is fast”，在该有的年纪里做这个时间段该做的事，人生最大的财富莫过于记忆和感受，没必要拼命跳过体验过程急忙奔赴人生最终的稳态。学习科研本就是一场艰难且孤独的修行，趁年轻，就应充满热情和动力，不轻易放弃，相信大神们也是肉体凡胎。时间充裕时，坚持发扬遍历精神，从品味基本概念描述和代码里每一个字符开始。最后，前期打基础时一定多折腾多把玩多踩坑多搜索，熟能生巧！

### 推荐资源

在海量网络资源和AI问答式工具触手可及的今天，只要有兴趣和毅力，纯小白也能完成从“面向谷歌/百度的学习编程”到“跟踪学术最前沿，站在浪潮之巅”的转变。下面简单推荐几个学习资源，也是本组成员人均刷过，交流探讨起来比较熟练。当然了，如果已经明确不做学术或算法研究岗的同学在理解深度上可以降低要求。

- [**CS231n: Deep Learning for Computer Vision**](http://cs231n.stanford.edu)。逐字逐句研读课程的英文Notes，积累和熟悉基础概念和英文术语表达，琢磨课后代码作业，也可以观看课程视频或PPT等材料。该公开课最初由AI领域大神博士生**Andrej Karpathy**完善，让很多人受益，汉化翻译版很容易获得。课后作业基本用Python和Numpy包实现，简直就是实现了一个简单的深度学习框架。学习之后相信能对计算机视觉和深度学习常见问题有一定认识，并且积累不少关于自动微分和数值优化的具体代码经验。以此课程为出发点，对这个领域的认识和进一步学习方向会清晰很多。此外关注度比较高的还有台大李宏毅系列课程。建议学习初期只要选择一个简明的课程和实战就够了，以后坚持深化认知。
- 顺便提一下，Karpathy毕业工作后依然热衷为大家烹饪可口的tutorial，例如从头动手搭建一个简单大语言模型，制作BPE Tokenier，LLM101n，详情见[Karpathd的Youtube频道](https://www.youtube.com/@AndrejKarpathy)🚀和[LLM101n建设中｜Github](https://github.com/karpathy/LLM101n)，太佩服了。
- 机器学习主题的[**StatQuest|Youtube**](https://www.youtube.com/@statquest/about)可视化讲解视频【可选】。一图胜千言，个人很喜欢图解，如果能把抽象的东西用作图的手段阐明，那肯定有了很深入的直观理解。
- **其他优质中英文博客**。一门课程或一本专著难以解决自己的所有疑惑，对于关键问题完全可以自行“觅食”，**变被动的信息接收过滤为主动的信息获取**。丰富的信息推送看似有营养，其实大部分都是会被抛之脑后的垃圾，严格筛选或查找最有针对性的资料是一项基本技能。针对完全小白的同学，也可以参考当年纯小白的我，面向浏览器摘录或撰写的[<font color="#ddd00"> 我的博客专栏|CSDN</font>](https://blog.csdn.net/xiaojiajia007)，仅仅抛砖引玉，看看各种*深度学习、ubuntu工作环境、python、git实用技能*和其他扫盲笔记是否对自己有启发价值。
- **MIT线性代数** by Gilbert Strang【可选】。无需多言，线性代数是被国内高校严重低估的基础课程。考虑到已有线性代数基础，推荐阅读网上流传的douTintin撰写的上中下笔记，短小精悍。这里顺便强推一下[**3Blue1Brown**的Youtube频道](https://www.youtube.com/c/3blue1brown)，B站上也有官方翻译频道，主打一个可视化微积分、线性代数、甚至深度学习。这两年不咋关注了，但看完之后确实受益匪浅，对曾经自己的死读书感到痛心疾首。国内很多有点名气的视频UP和知乎er基本都是模仿和使用3B1B开发的数学可视化python库，主打一个信息差。
- [**Pytorch模型训练实用教程**](https://github.com/TingsongYu/PyTorch_Tutorial) 【可选】。用好成熟的深度学习框架，有扎实的基本功后对特别细枝末节的东西即便没有亲自实现过也大概知道包括什么，用别人的工具和代码均是建立在信任的基础上。在成为调包侠之前，再推荐两个优质博文阅读[Understanding PyTorch with an example: a step-by-step tutorial](https://towardsdatascience.com/understanding-pytorch-with-an-example-a-step-by-step-tutorial-81fc5f8c4e8e)，[Understanding all of Python, through its builtins](https://tushar.lol/post/builtins/)。

### 待补充

黑盒模型时代有些东西乍看如天外来物，其实了解它的前世今生后就没那么难以接受了，例如一个讲解一阶、二阶优化算法的博文[一个框架看懂优化算法之异同 SGD-AdaGrad-Adam|知乎](https://zhuanlan.zhihu.com/p/32230623)，技术优化的背后演变很可能也是源自朴素的动机。再比如[CS583: Deep Learning](https://github.com/wangshusen/DeepLearning#cs583-deep-learning)课程中的Recurrent neural networks章节，从最原始的RNN开始，一路讲到如何催生出LSTM、Attention、Transformer。工科技术研究不同于纯理论，一个纯理论证明的完成意味着终结某个甚至一系列具体问题。而技术研究虽然不少在本质上也是做优化问题，但现实生活中的变量太多，很难通过得到解析解形式而一劳永逸。

### 仅供组内分享的资源

此处略。。。

申请加入师兄师姐自发组织的研讨，小分队在这里 [<font color="#ddd00"> ReadingPapers|GitHub</font>](https://github.com/ReadingPapers)，研讨小组每周精选的论文分享笔记也将同步到[<font color="#ddd00">ReadingPapers分享精选|知乎</font>](https://www.zhihu.com/column/c_1737122861716979712)。

另外提出一个小要求，鉴于还没入驻实验室且自学课程可能枯燥和孤单，建议每周发送一次周报（借助外在约束，坚持打卡），简述知识点所学情况，例如下面一个组内同学的某次周报截图，当然也不需要详细。这么做的目的是服务于自己对领域知识体系的构建（好记性不如烂笔头），坚持积累就有了属于个人的知识图谱，借此机会能够反思一周过去了有没有收获，最后利于指导老师和高年级同们掌握学习进度并帮忙查缺补漏。

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202310170841600.png" alt="image-20231017上午84131388" style="zoom:80%;" />



## 工具技能篇

工欲善其事必先利其器，无论是资讯跟踪、文献收集整理、工作环境搭建、远程解释器工具、代码版本维护等，都找一个趁手的家伙，能够极大提升自己的效率。建议优先挑选开源（免费且第三方插件丰富）或学生（教育）免费的软件，这里罗列自己经常使用的文字软件，具体如何配置打造成自己喜欢的样子，请自行动手配置。

### 文献管理工具 Zotero

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202310121646102.png" alt="WechatIMG288" style="zoom:67%;" />

PDF预览、Tag、翻译等功能需要通过第三方插件实现。如果你是Alfred软件爱好者，不怕折腾甚至还能配置其Zotero的Workflow，具体可参考 [ZotHero，Alfred Workflow for Zotero｜知乎](https://zhuanlan.zhihu.com/p/598001777)。额外提醒一句，默认只提供200M的文献PDF同步空间，我们自己可以设置Zotero文件夹中storage的软连接（ln -s），把实际的文献库存储目录storage托管到自己的云盘中，从而实现免费无限制的多平台同步。至于Zotero的meta info和notes，则可以通过官方同步，因为这两种文件是无空间限制的。

### 基于Markdown语法的双链笔记 Obsidian

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202310121649295.png" alt="WechatIMG289" style="zoom:67%;" />

第三方插件非常多，例如Github Copilot，配合教育认证获得免费的Pro账号，可以无限畅玩GPT-4o等Chat模型，更重要的是可以inline自动提示补全，本质上是代码补全功能，只不过也支持自然语言补全。还有一个更强大Obsidian Copilot插件，可以配置DeepSeek、Google Gemini等API即可实现对话。提醒一下，首先要**选择一个Embedding模型对vault中的笔记文件进行向量化之后，既可以实现基于RAG的对话**（该插件称之为vault QA功能），挺有意思。对于颜值党，荐个好看的Heatmap Calendar插件，功能如同github上显示活跃度的热图。安装插件之后把定制如何显示的dataviewjs代码块插入到想展示的markdown文件位置（例如HomePage）即可，效果如下：

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202310281102449.jpeg" alt="WechatIMG1039" style="zoom:40%;" />

还有一个时间进度条的展示，能用行内dataview实现，将下面代码复制到markdown文档里即可。

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202403071124362.png" alt="WechatIMG1039" style="zoom:50%;" />

```markdown

| 周期             | 已过去                                                                                      | 总间隔                                                                                                          | 进度条                                                                                                                                                                                                                                                      | 百分比                                                                                                                                                                                                                             | 当前时间                                      | 
|:---------------- | ------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| Day     (今天)   | `= dateformat(date(now), "HH")`                                                             | 24 小时                                                                                                         | `= "<progress max=" + 24 + "  value=" + number(dateformat(date(now), "HH")) + "> </progress>"`                                                                                                                                                              | `= round((number(dateformat(date(now), "HH")) / 24)*100) + " %"`                                                                                                                                                                   | `= dateformat(date(now), "EEEE, dd-MM-yyyy")` |
| Week   （本周）  | `= dateformat(date(now), "E")`                                                              | 7 天                                                                                                            | `= "<progress max=" + 7 + "  value=" + number(dateformat(date(now), "E")) + "> </progress>" `                                                                                                                                                               | `= round((number(dateformat(date(now), "E")) / 7)*100) + " %"`                                                                                                                                                                     | `= dateformat(date(now), "kkkk-'W'WW")` 周    |
| Month   (本月)   | `= dateformat(date(now), "dd")`                                                             | `= dateformat(date(eom), "dd")` 天                                                                              | `= "<progress max=" + dateformat(date(eom), "dd") + "  value=" + number(dateformat(date(now), "dd")) + "> </progress>"`                                                                                                                                     | `=round((number(dateformat(date(now), "dd")) / number(dateformat(date(eom), "dd")))*100) + " %"`                                                                                                                                   | `= dateformat(date(now), "kkkk-MM")` 月       |
| Quarter (本季度) | `$= dv.date("now").toFormat("ooo") - dv.date("now").startOf("quarter").toFormat("ooo") + 1` | `$= dv.date("now").endOf("quarter").toFormat("ooo") - dv.date("now").startOf("quarter").toFormat("ooo") + 1` 天 | `$= "<progress max=" + (dv.date("now").endOf("quarter").toFormat("ooo") - dv.date("now").startOf("quarter").toFormat("ooo") + 1) + "  value=" + (dv.date("now").toFormat("ooo") - dv.date("now").startOf("quarter").toFormat("ooo") + 1) + "> </progress>"` | `$= Math.round(((dv.date("now").toFormat("ooo") - dv.date("now").startOf("quarter").toFormat("ooo") + 1) / (dv.date("now").endOf("quarter").toFormat("ooo") - dv.date("now").startOf("quarter").toFormat("ooo") + 1))*100) + " %"` | `= dateformat(date(now), "kkkk-'Q'q")` 季     |
| Year    (今年)   | `= dateformat(date(now), "ooo")`                                                            | `= dateformat(date(eoy), "ooo")` 天                                                                             | `= "<progress max=" + dateformat(date(eoy), "ooo") + "  value=" + number(dateformat(date(now), "ooo")) + "> </progress>"`                                                                                                                                   | `=round((number(dateformat(date(now), "ooo")) / number(dateformat(date(eoy), "ooo")))*100) + " %"`                                                                                                                                 | `= dateformat(date(now), "kkkk")`  年         |


```

### 谷歌快讯 推送至邮箱

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202310121653140.png" alt="WechatIMG291" style="zoom: 50%;" />

建议通过关键词和查询语法缩小推送范围，邮箱塞入太多论文推送估计被动阅读的日常活动反而不会执行了。另外更加推荐直接订阅大牛或者自己感兴趣的研究者的最新论文，推送的质量更有保证。

### ChatGPT很有必要充分利用起来

<font color="#0000dd"> **ChatGPT is absolutely a game changer！**</font> 

不论是对英文表达、领域知识基本概念、或是各种命令行工具、网络模型、代码编程上存在问题，你都可以尝试向它提问，通过多轮交互对话，一步步人机相互引导找到可能的查找方向。一定要用好AI工具，这是继计算机信息网络发明后的又一划时代工具，是人类可能走向更高级文明的标志（石器时代的小故事无需我多言，人最大的本领就是发明和利用各种工具）。不过，如果你已经是一名专家，就能感觉到目前ChatGPT还不如自己的理解深刻和可靠，但它可以作为面向小白的耐心导师。

### 其他工具和插件

除此之外，日常使用的还有Pycharm专业版（教育邮箱免费）、VSCode（自己只是大部分情况用来写Latex）、Transmit（Mac端FTP工具，其实Pycharm和VSCode也能以GUI方式做到）、Dash（API文档聚合管理）、MathPix（Latex公式识别）等都非常推荐尝试。
这里点一下个人很喜欢的Pycharm（或VS Code插件TODO Tree）支持的TODO高亮和全局聚合管理功能，建议用不同的关键字和颜色高亮管理不同的TODO项，例如

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202401121108226.jpeg" alt="WechatIMG1402" style="zoom: 45%;" />



### 学长推荐必备工具

特别感谢陈银同学的热情分享，另外也可以参考 [我的博客专栏|CSDN](https://blog.csdn.net/xiaojiajia007)，虽然已经比较老旧了但应该还有参考和实践价值。

#### 服务器的连接

主要通过ssh连接，传文件可以使用sftp工具，或者scp命令。
命令：ssh -p port user@hostname

连接方法: 

1. 终端（cmd, powershell等等）
2. 专用软件（xshell, mobaxterm，termius) 
3. VScode, Pycharm

#### 深度学习环境搭建

[conda ](https://blog.csdn.net/SARACH_WONG/article/details/89328307)[环境创建｜博客](https://blog.csdn.net/SARACH_WONG/article/details/89328307) & pytorch [安装（官网）,](https://pytorch.org/get-started/previous-versions/)  [docker｜博客](https://cyinen.github.io/wiki/00-思维碎片/docker使用/) 或者 [virtualenvwrapper｜我的博客](https://blog.csdn.net/xiaojiajia007/article/details/85054798)

⚠️注：如果远程服务器因为网络问题没法安装某些开发包或者访问某些网站，可以在局域网内共享本地端的流量代理服务，例如在远程服务器上用环境变量声明提供代理服务的本地机的局域网地址和端口

```
export https_proxy=http://局域网代理本机地址:http监听端口号 http_proxy=http://局域网代理本机地址:http监听端口号all_proxy=socks5://局域网代理本机地址:socket监听端口号
```

长期挂载远程服务器需要给路由器端口设置固定IP地址，否则机器重启之后IP地址可能被重新分配。如果不会设置，请咨询师兄师姐，**暂时分享一下他们的代理服务器完成开发环境的各种工具安装**。自己长时间解决不掉的问题，很可能别人一句话就能帮忙解决，因此小白前期不要羞耻于提问，要有一颗发烧的心和不怕失败的坚韧。

#### 文件传输

- linux 常用命令: scp, mv, cd , rm, ssh

- 文件传输：winscp, [mobaxtem](https://mobaxterm.mobatek.net/)

- **代码后台运行**: [tmux](https://blog.csdn.net/woswod/article/details/80353254) 防止客户端电脑休眠或关机等原因，导致远程服务器的程序运行自动停止
- ssh: [ssh-keygen产生公钥与私钥对，及密钥分发](https://blog.csdn.net/as4589sd/article/details/112352174)

zsh【可选】:[ Ubuntu下安装ZSH - 知乎](https://zhuanlan.zhihu.com/p/514636147)。推荐插件: zsh-autosuggestions, zsh-syntax-highlighting。祖传配置文件： zsh_history & .zshrc & oh-my-zsh

#### 代码助手

学习使用AI代码助手：Copilot或ChatGPT

{% gp 2-2 %}
<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202310170904466.png" alt="image-20231017上午90421965" style="zoom:65%;" />
<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202401121113933.png" alt="WechatIMG1444" style="zoom:65%;" />
{% endgp %}

多说两句，Copilot Chat功能已经上线，这是对原有Copilot代码辅助功能的重要补充，虽然Copilot Chat的通用知识没有chatgpt 3.5丰富和深刻（更新：对于Pro用户Copilot目前已经可以无限制使用GPT-4o等主流对话模型），但是它把本地项目的（或者打开的多个窗口文档中的）代码当作上下文，给出更具体和有针对性的回答，可以加快理解别人的代码。例如下面的简单提问：

{% gp 2-2 %}
<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202403022152972.png" alt="WechatIMG1444" style="zoom:50%;" />
<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202403022158621.png" alt="WechatIMG1444" style="zoom:50%;" />
{% endgp %}

## 科研进阶篇

### 研究经验

内部分享，此处略。。。 

### 劝诫到抓狂

#### 关于idea构思和实现

有些同学实验失败的原因可谓匪夷所思，虽然总是强调使用深度学习技术的创新要从计算流开始验证，参与运算的tensor的维度要能前后匹配，有时换一种计算的顺序或对tensor的shape进行变换会意外得到新的结构，但这不代表自己意淫出来的结构就能训练成功。我曾见到往CNN模型中插入了巨大参数量的全连接层这种“逆天下之大不韪”，“开历史倒车”的“创新”。这种失败肯定要归因于自己没有脚踏实地学习基础知识或遍历过三四个优秀的开源论文。

低年级的同学务必注意，科研工作其实也是先学习消化然后再输出的过程。“学而不思则罔，思而不学则殆”这句话我们念叨了很多很多年，但身边的一些同学依然领悟不到这句话的真谛！<font color="#ddd00"> 提idea、构思方法结构时，切勿凭空想象，不要你以为！而要理论以为，前人的经验以为！</font>“Talk is cheap, show me the code”，不断劝诫大家，要多看相关研究论文的源代码。至少对于新手来说，优秀的开源项目要尽量一行一行琢磨为什么是这样实现，为什么许多参数不是默认设置，不同代码模块前后有什么连锁效应。**自己切不可想当然地构建一个模型后一通瞎训练，然后反馈说idea不work**。自己开发的模块和写出来的代码一定**要有可靠的参考或出处**，关键代码经过了自己仔细调试和测试。记住咱们是工科研究生，是有行为能力的个体，再复杂的科研都是动手一点点**做**出来的。

#### 关于数据处理和模型调参

认真核对预处理和后处理代码的各种细致条件，确保使用别人的模型做测试时，模型始终处于相同的**最佳工作区间内**，否则会造成推理精度降低（因为都是过拟合和内插值了上游任务数据集）。例如某人的图像模型对于200x200尺寸图片预测准确率最佳，那你也应该把相应图片center crop+resize到200x200，甚至中心物体边缘是否保留空白这种细节也要注意。

自己训练模型前**一定要先观察数据/特征/标签/分布**，不要急着端到端跑代码，完全当作黑盒瞎搞。例如把预先提取好的训练集一部分的模态特征做个数值统计，是否有左右两段异常区间仍有分布的情况。若有，这大概率是操作不当带来的噪声或者离群点，可能会影响模型正常收敛速度，甚至影响最终精度，你应该考虑截断。

自己的模型在训练阶段的参数，在测试阶段依然可以调节。例如训练阶段分类判别阈值设定>0.5，但由于模型过拟合、过分自信，测试阶段判别阈值调整为>0.85，可能会让效果变得更好！

虽然现在提高模型训练稳定性的技术很多，但万不可把这些套餐当作万能的，深度模型依然无法智能对抗任何噪声和幅度差距非常大的不同模态数据。

以上就是是炼丹手艺的冰山一角，have fun！

### 心得体会

我们反复强调，不管是指导老师还是自己，在想到某个idea时不是第一时间迫不及待告知他人，而要经过大概的逻辑梳理和文献检索，<mark style="background: #D2B3FFA6;">idea必须具体化，接着所构思的每一个大模块都有可靠理论或者前人经验积累作为支持，到了这一步才适合正式拿出idea来讨论</mark>。不靠谱的异想天开只会浪费大家的宝贵时间。请记住，某个idea能work并不意味着这个idea能work well甚至very well，不能优化到SOTA往往难以打动“小学生”审稿人。**有一个idea到把这个idea做成，这两个段点间的过程可谓变幻莫测**。一方面要不怕麻烦敢于折腾，<font color="#ddd00"> 经常把自己推到个人能力的边界来挑战困难（如此才获得成长）</font>；另一方面要实时评估下一步的可行性，避免更大的沉没成本。不管是阶段性的成功或暂时的失败，一定要多分析总结为什么效果变好了，为什么失败了（定位到不work的原因更有研究价值）。

### 研究生的核心--短暂而宝贵的研究生涯

每个人都有自己的节奏，工作的一天里抓住一次deep work的状态（沉浸地工作满4小时）就挺好了，提高执行效率鼓励自己keep going，别总盯着别人不停忙活而焦虑内耗。与其焦虑不如想办法从最简单的事情开始干起。只要用功，积累一段时间即便暂时没有成功但肯定也有许多收获。理性面对麻烦，遇到困难意味着找到了问题关键，尝试解决它则离成功更进一步，很可能走的弯路是通往成功的必经之路。别忘了，你的背后还有一群小伙伴会支持你，你在这里不是一个人在战斗。

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202310121710818.png" alt="WechatIMG293" style="zoom:80%;" />

学术品位是有门槛的，导师和学生需要一起提升，去回答“做什么研究”这个最难的问题。研究生阶段要尽快从工程师思维转变到科学研究思维，哪些是本领域的本质问题，哪些研究具有意义、创新性或普适性，学术论文应该怎么写，这部分一时半会说不完，姑且交给“线下面基”环节，以便尽快结束本文吧 :)



## 双向选择篇

团队的良好风气能让成员耳濡目染，感受熏陶并在不知不觉中成长。本小组认可“work hard, play hard”的理念，尊重个性和效率，因此需要大家一起维护自我驱动的、弹性的工作作风，做到积极反馈和乐于交流，否则本小组所向往的理想化风格将彻底崩溃。

和指导老师或课题组其他成员多多探讨很有意义，理想的状态是互为师生，期待准备加入的小伙伴可以反向教会老师和同学们一些新东西，为小组带来新的可能。

人生的追求本来就是多元化的，自己可以放弃，但是不要否定他人干扰他人的追求，保持阳光的心态去看这个世界，尊重欣赏身边的朋友。最后，缺乏自我驱动力或不认同小组价值观的同学请不要加入或者及时离开。
