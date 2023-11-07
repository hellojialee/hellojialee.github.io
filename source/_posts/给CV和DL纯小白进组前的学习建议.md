---
title: 招生贴--CV和DL菜鸟自学建议
description: '写给希望申请加入本课题组开展学习研究的同学'
date: 2023-10-12 11:30:55
tags:
	- 深度学习
categories: 学习
---

## 入门篇

### 说在前面

选跟一个优质的公开课或简明教程有助于学科入门。学会提问是开始研究的第一步，若大脑没有一定的信息输入和内化积累，很可能迷茫到“连自己的问题是什么都不知道”的地步，更别提下一步应该学什么、研究什么。老师和学生仅仅是“闻道有先后”的区别，每个人都有可能成为领域小专家并获得大家的尊重，成长为靠谱的合作伙伴。

学习科研本就是一场艰难且孤独的修行。趁年轻，就应充满热情和动力，不轻易放弃，相信大神们也是肉体凡胎。时间充裕时，坚持发扬遍历精神，从品味基本概念描述和代码里每一个字符开始。最后，前期打基础时一定多折腾多把玩多踩坑多搜索，熟能生巧！

### 推荐资源

在海量网络资源和AI问答式工具触手可及的今天，只要有兴趣和毅力，纯小白也能完成从“面向谷歌/百度的学习编程”到“跟踪学术最前沿，站在浪潮之巅”的转变。下面简单推荐几个学习资源，也是本组成员人均刷过，交流探讨起来比较熟练。当然了，如果已经明确不做学术或算法研究岗的同学在理解深度上可以降低要求。

- [**CS231n: Deep Learning for Computer Vision**](http://cs231n.stanford.edu)。逐字逐句研读课程的英文Notes，积累和熟悉基础概念和英文术语表达，琢磨课后代码作业，也可以观看课程视频或PPT等材料。该公开课最初由AI领域网红博士生**Andrej Karpathy**完善，让很多人受益，汉化翻译版很容易获得。课后作业基本用Python和Numpy包实现，简直就是实现了一个简单的深度学习框架。学习之后相信能对计算机视觉和深度学习常见问题有一定认识，并且积累不少关于自动微分和数值优化的具体代码经验。以此课程为出发点，对这个领域的认识和进一步学习方向会清晰很多。
- 机器学习主题的[**StatQuest|Youtube**](https://www.youtube.com/@statquest/about)可视化讲解视频【可选】。一图胜千言，个人很喜欢图解，如果能把抽象的东西用作图的手段阐明，那肯定有了很深入的直观理解。
- **其他优质中英文博客**。一门课程或一本专著难以解决自己的所有疑惑，对于关键问题完全可以自行“觅食”，**变被动的信息接收为主动的信息获取**。丰富的信息推送看似有营养，其实大部分都是会被抛之脑后的垃圾，严格筛选或查找最有针对性的资料是一项基本技能。针对完全小白的同学，也可以参考当年纯小白的我，面向浏览器摘录或撰写的[<font color="#ddd00"> 我的博客专栏|CSDN</font>](https://blog.csdn.net/xiaojiajia007)，仅仅抛砖引玉，看看各种*深度学习、ubuntu工作环境、python、git实用技能*和其他扫盲笔记是否对自己有启发价值。
- **MIT线性代数** by Gilbert Strang【可选】。无需多言，线性代数是被国内高校严重低估的基础课程。考虑到已有线性代数基础，推荐阅读网上流传的douTintin撰写的上中下笔记，短小精悍。
- [**Pytorch模型训练实用教程**](https://github.com/TingsongYu/PyTorch_Tutorial) 【可选】。用好成熟的深度学习框架，有扎实的基本功后对特别细枝末节的东西即便没有亲自实现过也大概知道包括什么，用别人的工具和代码均是建立在信任的基础上。在成为调包侠之前，再推荐两个优质博文阅读[Understanding PyTorch with an example: a step-by-step tutorial](https://towardsdatascience.com/understanding-pytorch-with-an-example-a-step-by-step-tutorial-81fc5f8c4e8e)，[Understanding all of Python, through its builtins](https://tushar.lol/post/builtins/)。

### 待补充

黑盒模型时代有些东西乍看如天外来物，其实了解它的前世今生后就没那么难以接受了，例如一个讲解一阶、二阶优化算法的博文[一个框架看懂优化算法之异同 SGD-AdaGrad-Adam|知乎](https://zhuanlan.zhihu.com/p/32230623)，技术优化的背后演变很可能也是源自朴素的动机。再比如[CS583: Deep Learning](https://github.com/wangshusen/DeepLearning#cs583-deep-learning)课程中的Recurrent neural networks章节，从最原始的RNN开始，一路讲到如何催生出LSTM、Attention、Transformer。工科技术研究不同于纯理论，一个纯理论证明的完成意味着终结某个难题。而技术研究虽然不少在本质上也是做优化问题，但现实生活中的变量太多，很难通过得到解析解形式而一劳永逸。

### 仅供组内分享的资源

此处略。。。

申请加入师兄师姐自发组织的研讨，小分队在这里 [<font color="#ddd00"> ReadingPapers|GitHub</font>](https://github.com/ReadingPapers)

另外提出一个小要求，鉴于还没入驻实验室且自学课程可能枯燥和孤单，建议每周发送一次周报（引入外部监督，坚持打卡），简述知识点所学情况，例如下面一个组内同学的某次周报截图，当然也不需要详细。这么做的目的是服务于自己对领域知识体系的构建（好记性不如烂笔头），坚持积累就有了属于个人的知识图谱，借此机会能够反思一周过去了有没有收获，最后利于导师掌握学习进度并帮忙查缺补漏。

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202310170841600.png" alt="image-20231017上午84131388" style="zoom:80%;" />



## 技能篇

工欲善其事必先利其器，无论是资讯跟踪、文献收集整理、工作环境搭建、远程解释器工具、代码版本维护等，都找一个趁手的家伙，能够极大提升自己的效率。建议优先挑选开源（免费且第三方插件丰富）或学生免费的软件，这里罗列自己经常使用的文字软件，具体如何配置打造成自己喜欢的样子，请自行搜索和动手。

### 文献管理工具 Zotero

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202310121646102.png" alt="WechatIMG288" style="zoom:67%;" />

### 基于Markdown语法的双链笔记 Obsidian

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202310121649295.png" alt="WechatIMG289" style="zoom:67%;" />

这里荐个好看的Heatmap Calendar插件，功能如同github上显示活跃度的热图。安装插件之后把定制如何显示的dataviewjs代码块插入到想展示的markdown文件位置（例如HomePage）即可，效果如下

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202310281102449.jpeg" alt="WechatIMG1039" style="zoom:40%;" />

### 谷歌快讯 推送至邮箱

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202310121653140.png" alt="WechatIMG291" style="zoom: 50%;" />

### ChatGPT很有必要充分利用起来

<font color="#0000dd"> **ChatGPT is absolutely a game changer！**</font> 

不论是对英文表达、领域知识基本概念、或是各种命令行工具、网络模型、代码编程上存在问题，你都可以尝试向它提问，通过多轮交互对话，一步步人机相互引导找到可能的解决办法。一定要用好AI工具，这是继计算机信息网络发明后的又一划时代工具，是人类可能走向更高级文明的标志（石器时代的小故事无需我多言，人最大的本领就是发明和利用各种工具）。不过，如果你已经是一名专家，就能感觉到目前ChatGPT还不如自己的理解深刻和可靠，但它可以作为面向小白的耐心导师。

这里顺便说一句，新东方**《考研英语经典必背500句》**也可以看看，里面有不少长难句分析，素材来自于各种从句嵌套的科技论文，读一读有助于提高对语法结构和复杂表达的理解水平。

### 其他工具

除此之外，日常使用的还有Pycharm专业版、VSCode、Transmit（Mac端FTP工具，其实Pycharm和VSCode也能以GUI方式做到）、Dash（API文档聚合管理）、MathPix（Latex公式识别）等都非常推荐尝试。

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

⚠️注：如果远程服务器因为网络问题没法安装某些开发包或者访问某些网站，可以在局域网内共享本地端的流量代理服务，例如在远程服务器上生命代理的局域网地址和端口

```
export https_proxy=http://局域网代理本机地址:http监听端口号 http_proxy=http://局域网代理本机地址:http监听端口号all_proxy=socks5://局域网代理本机地址:socket监听端口号
```

长期挂载远程服务器需要给路由器端口设置固定IP地址，否则机器重启之后IP地址可能被重新分配。如果不会设置，请咨询师兄师姐，暂时分享一下他们的代理服务器完成开发环境的各种工具安装。自己长时间解决不掉的问题，很可能别人一句话就能帮忙解决，因此小白前期不要羞耻于提问，要有一颗发烧的心和不怕失败的坚韧。

#### 文件传输

- linux 常用命令: scp, mv, cd , rm, ssh

- 文件传输：winscp, [mobaxtem](https://mobaxterm.mobatek.net/)

- **代码后台运行**: [tmux](https://blog.csdn.net/woswod/article/details/80353254) 防止客户端电脑休眠或关机等原因，导致远程服务器的程序运行自动停止
- ssh: [ssh-keygen产生公钥与私钥对，及密钥分发](https://blog.csdn.net/as4589sd/article/details/112352174)

zsh【可选】:[ Ubuntu下安装ZSH - 知乎](https://zhuanlan.zhihu.com/p/514636147)。推荐插件: zsh-autosuggestions, zsh-syntax-highlighting。祖传配置文件： zsh_history & .zshrc & oh-my-zsh

#### 代码助手

学习使用AI代码助手：Copilot或ChatGPT

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202310170904466.png" alt="image-20231017上午90421965" style="zoom:65%;" />

## 进阶篇

### 研究经验

内部分享，此处略。。。

### 研究生的核心--短暂而宝贵的研究生涯

每个人都有自己的节奏，工作的一天里抓住一次deep work的状态（沉浸地工作满4小时）就挺好了，提高执行效率鼓励自己keep going，别总盯着别人不停忙活而焦虑内耗。与其焦虑不如想办法从最简单的事情开始干起。只要用功，积累一段时间即便暂时没有成功但肯定也有许多收获。理性面对麻烦，遇到困难意味着找到了问题关键，尝试解决它则离成功更进一步，很可能走的弯路是通往成功的必经之路。别忘了，你的背后还有一群小伙伴会支持你，你在这里不是一个人在战斗。

<img src="https://cdn.jsdelivr.net/gh/hellojialee/PictureBed@master/img2bolg/202310121710818.png" alt="WechatIMG293" style="zoom:80%;" />

学术品位是有门槛的，导师和学生需要一起提升，去回答“做什么研究”这个最难的问题。研究生阶段要尽快从工程师思维转变到科学研究思维，哪些是本领域的本质问题，哪些研究具有意义、创新性或普适性，学术论文应该怎么写，这部分一时半会说不完，姑且交给“线下面基”环节，以便尽快结束本文吧 :)



## 选择篇

本小组认可“work hard, play hard”的理念，需要大家一起维护自我驱动的、弹性的工作作风。和导师或课题组其他同学探讨很有意义，理想的状态是互为师生，主动交流。团队的良好风气能让成员耳濡目染，感受熏陶并在不知不觉中成长。人生的追求本来就是多元化的，可以放弃自己选择躺平，但是不要否定他人干扰他人的追求，保持阳光的心态去看这个世界，尊重欣赏身边的朋友。
