---
title:  Transease

date:   2019-08-10 14:37:52 -0400 #date this page is written

categories: projects 2018 spring #project folder, beginning year and season
tags: Highlight All Event_Planning Leadership Marketing Negotiation Video_Editing Web_Design
#tags options: Highlight Event_Planning Entrepreneurship Leadership Game_Design Marketing Negotiation Video_Editing Web_Design

start-season: "2018 Spring"

assetLoco: /images/projects/Transease
coverPic: /cover.png
carousel:
  - image: /bg1.png

---
在我高三，我们有一位来自英国新老师叫马克。但问题是他完全不会说中文。所以，当他需要租房子或和当地人聊天时，他需要我们帮忙翻译。

这让我开始思考。如果每次人们需要翻译的时候，总有一个人可以奇迹般地出现并帮助他们，这不是很好吗?

受Uber的启发，我开发了一款实时的人工翻译应用，可以以很低的价格实现这一点。通过与我的朋友Tony Lian和Yujie Wang的合作，我们设计出了一个初期品，并在2018年微软创新杯大创意挑战赛中获得了世界前50名。我们也是2018年唯一一支获得该奖项的中国大陆团队。

{% include image.html img="award.png" caption="他们把我的姓名写反了我也很无奈~" %}

## Table of Contents
{:.no_toc}

* Table of Contents
{:toc}

## 问题

我去过17个不同的国家，但我只会说两种语言。因此，尝试跨语言交流一直是我想要解决的问题。目前，人们倾向于使用免费的在线翻译应用程序，如谷歌翻译或聘请昂贵的翻译。问题是这些翻译应用不准确。这里有一个例子。尽管中国“能穿多少穿多少”是一样的,有完全不同的含义在不同的设置。在下列情况中，它的实际意思是“天气很热，尽可能少穿衣服。”
{% include image.html img="Translation_Error.jpg" caption="Translation Error"%}
至于雇翻译，嗯，太贵了。所以，我想看看是否有一个中间地带，可以使人工翻译被常人所负担得起。

## 解决方法

Uber让我着迷，因为它的核心理念很简单，但它解决了我们社会中的一个巨大问题。如果优步可以把可用的司机和需要搭车的人联系起来，为什么我们不能把可用的翻译人员和需要翻译服务的人联系起来呢?

### 一个用户故事
洁坷是一位到美国旅游的中国游客。他想和当地的一位店主聊天十分钟，但他不会说英语。所以，他打开我们的应用程序Transease在他的手机和点击“翻译”。
{% include image.html img="1.png"%}<br>

我们的系统将搜索谁是有空的，并将他们与洁坷对接起来

假设在地球的另一端，一个美国交换生Jack刚刚在一所中国大学完成了他的课程。他会说英语和汉语，大约有10分钟的时间。他可以打开我们的应用程序，点击“开始接受工作”。
{% include image.html img="2.png"%}<br>

然后我们的系统将洁坷和Jack连接起来，让Jack通过语音电话为洁坷翻译。服务结束后，Jack会从洁坷那里得到一小笔费用。然后洁坷可以给Jack的翻译打分，然后继续旅行，直到他再次需要翻译服务。
{% include image.html img="3.png"%}<br>

### 原型

为了确保这个想法是可行的，我想出了一个MVP。我请了6位会说中文和英文的朋友帮忙。我把他们的联系方式放在一个表中，显示了他们的可用时间。我还招募了两名中文不太好的外教作为我们的测试对象。在MVP项目中，无论何时受试者需要翻译服务，他或她都可以查表并拨打那段时间内可用的电话号码。有空的人会通过电话为他们翻译。
{% include image.html img="Call_Table.png" caption="Call Table"%}<br>
这个MVP就像一个概念的证明，来证明通过语音通话显示翻译实际上是可行的。我们收到了很多反馈。我们试图在第一个原型中解决大部分问题。

为了避免为不同平台开发应用程序的高成本，我们的第一个原型是一个针对移动用户进行优化的网站，它具有登录和语音通话功能。之后我们增加了更多的功能，比如评级和视频聊天。这个原型帮助我们赢得了2018年微软创新杯的创意大赛。

## 发展潜力

在我们项目的中期，我意识到一个更重要的问题。如果翻译算法足够好，我们的应用程序很容易被替换。况且人们已经习惯使用免费翻译软件。我们怎么才能鼓励他们多花点钱用我们的软件呢?

如果我有更多的时间，这些就是我想要改进的地方。首先，我想举行另一个用户测试，这次要求人们实际为服务付费。然后，通过更多的迭代，我想改善我们的应用程序的UI设计和一个更好的支付系统。此外，在未来，如果这款应用真的能运行，我们将拥有数百万分钟的翻译记录。这些数据可以帮助我们训练出一种算法，其性能可以超过大多数免费翻译服务。

但遗憾的是，我们去了不同的大学后就停止了这个项目。
{% include image.html img="bg1.png"%}<br>

## Credits

实际的应用程序开发都是由我的朋友Tony Lian和Yujie Wang完成的。Tony 负责设计后台，Yujie负责设计前端。

除了提出这个想法之外，我在这个项目中的角色是跨迭代提供反馈，并确保我们的项目范围正常工作。我还负责用户测试、市场调研、调查和市场推广。
