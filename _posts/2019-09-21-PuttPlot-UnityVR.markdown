---
title: PuttPlot
title2: PuttPlot #title shown in first line
date:   2019-09-21 20:40:23 -0400 #date this page is written

categories: projects 2019 fall #project folder, beginning year and season
tags: Product_Project_Management Game_Design All
#tags options: Highlight Event_Planning Entrepreneurship Product/Project_Management Game_Design Marketing Negotiation  Web_Design

start-season: "2019 Fall"

assetLoco: /images/projects/PuttPlot
coverPic: /cover.png
carousel:
  - image: /cover.png

---
这项工程仍在进行中。我将每周更新这个网站。下一个更新将于2019年10月5日发布(Hopefully)

这是一个CMU 53-451课程的团队项目。课程名称为：游戏开发中的科研问题:XR的设计。这是一门由Tom Corbett教授教授的游戏设计/研究课程，我们将以团队的形式在VR/AR中设计电子游戏。

在这个项目中，我们设计了一个高尔夫约会模拟游戏PuttPlot。可以理解为一个日式的2D约会模拟游戏，但你可以通过将球打到相应的洞中来选择你的反应。这个项目既具有挑战性又有趣，因为我们需要在VR中模拟3D高尔夫动作和物理，同时通过2D动画讲述一个有趣的故事。

在这个为期6周的项目中，我是游戏的制作人/程序员。我们将为游戏进行6次迭代，每周开发一个样板，并在每周五展示一个Demo。

这就是我们的故事。

## Table of Contents
{:.no_toc}

* Table of Contents
{:toc}

## Week 1 - 脑洞大开
我们的项目有很大的自由度。教授对我们的唯一的要求是它必须是一个可玩的VR游戏，并且灵感要来自任何野餐聚会游戏。当然，它还需要在6周内由，可以由一个5-6人的团队开发出来。

我们在8月30日星期五组成了我们的团队。第二天，我们举行了第一次会议。在会议中，我们花了大约4个小时讨论游戏理念。我们的讨论范围很广，从技术挑战性强的 _HallBall_，到美式黑色幽默游戏 _Catch With Dad_。我提出的游戏理念是一款环境教育沙盒游戏，名为《树木》(_Tree_)，你可以在其中种植并摧毁树木，从而影响全球气温。遗憾的是，对于一个为期6周的项目来说，它有点超出了scope，所以我们最终没有实践它。

经过几轮投票，我们最终产生了一个约会模拟高尔夫游戏的想法:_PuttPlot_。
### Producing
在我们决定了游戏理念后，我们需要在下一个周五展示一个可玩的Demo。我们合作把任务分配给团队中的每个人。这些任务包括演示板设计、2D艺术和击球机制。所有单独的任务都要在周三晚上完成。我们会用周四晚上的时间来合并所有单独的部分，成为一个游戏。
### Programming
在我们的第一个演示中，我们只是在球上使用刚体的代码，并在高尔夫球杆上添加了一个collider。每当球被击中时，我们都会在球棒的方向上给球加上一个力。因此，Unity引擎自带的物理将处理碰撞和高尔夫球将如何飞行。

我们第一周做得很好。我们的Demo运行的很正常，听众们都挺喜欢它。我们也收到了很多建设性的反馈。
{% include image.html img="week1.png" caption="Concept Art for the game"%}

## Week 2 - 前期制作
为了让事情顺利进行，我们这周做了很多前期准备工作。
### Producing
首先，我们决定了游戏的三大支柱:

1. 笑:游戏应该非常非常有趣/颠覆预期
2. 吸引人的故事:玩家的决定很重要
3. 2D和3D的融合：球击中的板子需要与到对话选项难度相呼应

我们的游戏主要由两个部分组成:一个是高尔夫力学，另一个是一个有趣的故事。所以在第二周，我们的作家Gus负责撰写故事，最后得到了一堆索引卡，里面全是他写的有趣的故事。我们的美工家Angelina负责设计概念图和角色艺术。我们的程序员Carter和Ann力于高尔夫球的挥杆动作。我负责3D板的设计和制作工作。

我们仍然使用星期四融合到星期五展示的方法。由于我们做的很多工作都是前期制作，所以我们在周五展示的demo与前一周并没有太大的不同。
{% include image.html img="week2-story.png" caption="Draft story tree for the game"%}

### Programming
本周，我们将尝试模拟高尔夫球在现实世界中的工作原理。在现实生活中，高尔夫球与球杆接触后不会立即飞走，而是会被球杆稍稍抬起一点，然后飞走。

因此，我们试图在游戏中做到这一点，即在接触球后立即将球添加为球杆的子对象，这样球就会粘在球杆上。当球向挥杆的方向移动几毫秒后，我们将释放球并增加一个力使它飞起来。

这个概念很好，但是最终的结果并不像我们希望的那样成功。球还是跑得太快，没有落在玩家期望的位置。

### Feedback for this week
和上周一样，我们在周五的demo之后收到了很多反馈，我们总结为四点:

* 球太快/不够明显
* 文字看起来很糟糕
* UI需要设计
* 击球的感觉不好。需要一个斜坡

遗憾的是，我们忘记在前两个迭代中记录游戏视频，所以你将无法看到它们。

{% include image.html img="week2-game.png" caption="The second iteration"%}
## Week 3 - 艰难的一周:(

在游戏的第三个迭代中，事情开始变得有点困难。这周我们召开了技术机会大会，这是CMU每年最大的招聘会。很多队友都在周一、周二和周三的招聘会中度过了他们所有的空闲时间。

### Producing
这意味着我们周三的checkpoint没有达到。所以我们只能在最后一分钟把所有东西放到一起。Carter、Gus和我在Hunt图书馆地下室一直呆到午夜以后。即使在那之后，我们提交的版本仍然有很多bug。

我为游戏设计了几个关卡。而是因为我们没能及时实现对话过渡。我们从来没有机会达到新的关卡。因此，我们周五的演示并不理想。

### Programming

好在我们有一个坡道。我们上周得到的反馈之一是，仅仅把球打到洞里的感觉并不好。我们通过增加一个加速坡道来解决这个问题。在这种情况下，玩家只需要把球推到斜坡上，球就会飞到板上。

希望下周我们能做得更好。

写于2019年9月28日。
{% include image.html img="week3-ramp.png" caption="The ramp"%}

## Week 4 - Play-Testing
Will be updated on Oct 5, 2019.
## Week 5
Will be updated on Oct 12, 2019.
## Week 6 - Release
Will be updated on Oct 19, 2019.
## Credits
To be written
