![img](https://mmbiz.qpic.cn/mmbiz_png/uDRkMWLia28gfbCThQozkH3IBzdSM5IrAZv5CjC7A2cSL0KrQAQIfD7kibCjpPtcjwEHWicHFmw5M9Gr6VLjDWlicA/640)

大家好，我是小 G。

在文章开始之前，先给大家安利一波我们的公众号：**GitHubDaily**，目前每天都会在上面更新至少 3 篇文章，主要分享比较实用的开发工具与开源项目，偶尔也会聊聊技术圈内最近发生的新鲜事，感兴趣的小伙伴可以关注一下哈。

上周四的时候，我们在公众号分享了一篇文章：《[听说玩这些游戏能提升编程能力？](http://mp.weixin.qq.com/s?__biz=MzAxOTcxNTIwNQ==&mid=2457919248&idx=2&sn=b45af850f29fe6008edcd7c47760c8e7&chksm=8cb6bafabbc133ec1b6e31ff79d0d4079ba5f4d3d3060c96f2a20e8da93d80e6a0bf1f951f33&scene=21#wechat_redirect)》，里面提到了一款 Git 小游戏，今天打算借此机会跟大家细聊下。

对于 Git 这款工具，相信很多开发者都不会感到陌生。

作为目前最为流行的分布式版本控制工具，Git 打从 2005 年面世时起，便一直受到无数开发者喜爱。随着时间的慢慢推移，Git 发展到了今天，也成为了诸多开发者人手必备的开发工具。

2007 年，Chris Wanstrath、PJ Hyett 和 Tom Preston-Werner 三名开发者基于 Ruby on Rails 框架，联手开发了一个可用于托管项目源码的网站：GitHub。

![img](https://mmbiz.qpic.cn/mmbiz_jpg/uDRkMWLia28h0MuaiaPYRah7VNBSXyxtMsnWb2H7K4D4yiafjBMqorVrawZ0lFgAqaagJCzxR6dIAHQyWz6ETefJQ/640)

现如今，GitHub 已成为世界最大的开发者社区，在上面，每天都有大量开发者使用 Git 进行协作开发，也累积下一批批优质的开源项目，为后来者提供了宝贵的学习机会与参考价值。

因此，学会使用 Git，相当于你购入了一张通往世界顶级开发者社区的门票。

今天，学习 Git 已不再是难事，回想我在早年间刚接触 Git 那会，中文互联网上于此相关的资料少的可怜，更不用说有人讨论 GitHub 上的开源项目了。

我最早接触 Git 和 GitHub 的时候，是读了 Michael Hartl 的一本书《Ruby on Rails tutorial》。这本书可以说是打开了我通往技术圈的一扇大门，里面教授的各种编程理念与开发技巧，令我受益至今。感兴趣的同学，可以自己去找来看一下。

<p align="center">
   <img src="https://mmbiz.qpic.cn/mmbiz_png/uDRkMWLia28h0MuaiaPYRah7VNBSXyxtMsjr7ODeHgNiaqDZTYOW9QTu91e7OjmIbn5dryK1R2BL865NoJGPPRETA/640">
</p>

下面我们接着聊回 Git。

如果你想学好 Git，用 Google 和百度一搜，就能找到很多适合新手学习的入门书籍，包括此前我们也在公众号（GitHubDaily）上面分享过一些 Git 教程：

- [卧槽！小姐姐用动画图解 Git 命令，这也太秀了吧？！](http://mp.weixin.qq.com/s?__biz=MzAxOTcxNTIwNQ==&mid=2457919169&idx=2&sn=7514209811adbd09b6161093e8ae3eb4&chksm=8cb6bb2bbbc1323dc0cd1c9110fcc6a2a06774040586fc21a01db98129a03ece8ee4cdb73960&scene=21#wechat_redirect)
- [Linus 在 Google 分享了 Git 的设计思路，顺带怼了一大波人（视频）](https://mp.weixin.qq.com/s?__biz=MzAxOTcxNTIwNQ==&mid=2457915907&idx=1&sn=7f39b7943bf0e9ba4a2b12b47d4a70d7&scene=21#wechat_redirect)
- [用好这几个工具，能大幅提升你的 Git/GitHub 操作效率！](https://mp.weixin.qq.com/s?__biz=MzAxOTcxNTIwNQ==&mid=2457915558&idx=1&sn=de0cdcb9fb199162ffe565e371b3dbf4&scene=21#wechat_redirect)
- [强烈推荐下 GitHub 官方的这个教程](https://mp.weixin.qq.com/s?__biz=MzAxOTcxNTIwNQ==&mid=2457914680&idx=1&sn=0061f76dbd0e33468216a460c624c2b4&scene=21#wechat_redirect)
- [收好这份 Git 命令应急手册，关键时刻可保你一命](https://mp.weixin.qq.com/s?__biz=MzAxOTcxNTIwNQ==&mid=2457914802&idx=1&sn=a8d2cb9b626da84d94d8b2ebd9e85c24&scene=21#wechat_redirect)

但是，文字的表现张力往往不如画面来的强烈，缺少实时交互反馈机制，也是其最大的硬伤之一。

如果你觉得学习 Git 的过程非常枯燥且乏味，那不妨换一种方式。比如，通过玩游戏来学好 Git 的基础操作。

今天在这里给大家推荐一款游戏：Learn Git Branching。

![img](https://mmbiz.qpic.cn/mmbiz_png/uDRkMWLia28h0MuaiaPYRah7VNBSXyxtMsxicic1iaWUF0nePMR4ZzH9OONxtUuNibNRBkr8sZOYgxEqbHzErJticHB0A/640)

Learn Git Branching 的作者，是毕业自美国加州大学伯克利分校的一名开发者：Peter Cottle。

<p align="center">
   <img src="https://mmbiz.qpic.cn/mmbiz_jpg/uDRkMWLia28h0MuaiaPYRah7VNBSXyxtMsBsEGUTfzWyaibgiagMf3lCEuf1HDIqQkC8oJPhsfRWgicTDsCKdCDKUZQ/640">
</p>

在这款游戏中，开发者需要通过一系列关卡挑战，来慢慢掌握对 Git 的使用。在每一个关卡里面，作者都会为你提前设定好一个 Git 学习目标。

当你真正沉浸其中，研究具体该如何进行下一步操作时，你学会用 Git 便指日可待了。

具体演示如下：

<p align="center">
   <img src="https://mmbiz.qpic.cn/mmbiz_gif/uDRkMWLia28h0MuaiaPYRah7VNBSXyxtMsymjVd30riaPlIw4ztMnh9Lf94ia6xpYoPXdOiaKdKc6BzMDc5rgglXq3g/640">
</p>

该项目的玩法整体都比较简单，没有过多花里胡哨的东西，配合网站上默认集成的虚拟终端环境与预览页面，可以让我们很清晰的看到每一行命令的实际运行效果。

这种实时交互反馈式的编程体验，无疑能让开发者更为亲切的感受到 Git 的魅力。

同时，来自不同国家的开发者还在 GitHub 上为该项目翻译了中文、日文、韩文等多个语言版本。

在很久前，这款游戏的所有代码便早已开源到了 GitHub 上，想研究它具体原理实现的同学，也可以看一下：

https://github.com/pcottle/learnGitBranching 

--

文末，照旧安利一波我们的公众号：**GitHubDaily**，目前每天都会在上面更新至少 3 篇文章，主要分享比较实用的开发工具与开源项目，偶尔也会聊聊技术圈内最近发生的新鲜事，感兴趣的小伙伴可以关注一下哈。

<p align="center">
   <img src="https://raw.githubusercontent.com/GitHubDaily/GitHubDaily/master/assets/weixin.png">
</p>