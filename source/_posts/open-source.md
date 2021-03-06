---
title: 如何参与开源项目(译)
date: 2018-08-22 08:56:47
tags:
---

<div align=center width = "30" height = "30">![open source](ban.jpg)

[原文连接:How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)


    开源项目参与手册


### **为什么参与开源项目**


> 在[freenode](http://webchat.freenode.net/)上的工作（经历）帮我获得了很多技能， 这些技能在我后续的大学学习以及真正工作中都用到了， 我觉得在开源项目上的工作于我于项目都彼此受益
--@errietta, “Why I love contributing to open source software”


参与开源项目是学习，教学以及积累各项技能技能经验的有效方式。
为什么人们参与开源项目呢？ 原因太多了！

##### *提升现有技能*

* 不管是写代码， 用户接口设计， 平面设计， 文案写作还是组织安排， 只要你想训练， 总有一个开源项目适合你。

##### ***与有趣味相投的人相遇***

* 社区氛围温暖友善的开源项目吸引人们流连数年， 很多人在参与开源项目期间或在论坛偶遇时， 或在长夜网聊煎饼果子时，建立了终生的友谊。

##### ***寻找导师和教导他人***

* 与他人共事一个公共项目， 意味着只要你向他人求助， 你就要向别人说明你如何工作的，参与双方的教和学变成了一项非常有趣的活动。

##### ***创造公共作品培育声望和事业***

* 顾名思义（开源项目）， 你所有的开源工作都是公开的， 这意味着你可以随时随地展示你的工作成果。

##### ***向他人学习***

* 参与开源是锻炼领导力提升管理技能的好机会， 比如解决冲突， 组织团队成员以及对轻重缓急做取舍。

##### ***哪怕小小的改变也能令人兴奋***

* 开源并不意味着要做终生贡献者， 你是否看到网站上看到了错别字， 然后想有人会去修复它？ 在开源项目中， 你就可以修复它， 开源能让人们感受到他们的生活处在行动中， 感受到他们是如何体验世界， 这本身就是非常愉悦的。


### **贡献开源意味着什么**

> 如果你刚刚参与开源项目， 这个过程可能令人生畏。 
如何找到合适的项目？ 不会写代码怎么办？ 事情搞砸了怎么整？

别急， 参与到开源项目中的途径非常多， 一些小的技巧可以帮你（在开源项目中）充分利用你的经验

##### ***你不一定要贡献代码***

参与开源项目就必须要贡献代码， 这是一个常见的误解， 事实上一个开源项目的[非代码](https://blog.github.com/2016-06-23-the-shape-of-open-source/)部分的工作总是被忽略和轻视, 如果你能做一些非代码部分的工作， 也将对项目产生巨大的帮助

    我因在CocoaPods项目上的工作而被人所知， 但多数人并不知道
    我压根没有做过针对CocoaPods工具本身的工作， 我的时间主要
    放在文档和项目推广上
     ---— @orta, “Moving to OSS by default”

即便你喜欢写代码， 其他类型的贡献是通向参与项目，
结交社区成员的途径，构建与项目和社区成员的关系可以创造机会参与到项目的其他部分

	我第一次接触Python开发团队（aka python-dev）是在2002年7月17号， 因发patch我向mail list发邮件
	我快速找到开源bug，我决定为成员组整理邮件列表，
	他们给了我一个理由，然后请求主题相关的澄清， 最最关键的是，当有人指出有东西需要修复时， 我能够意识到。

##### ***你喜欢规划事情么***

- 为项目组织场地或聚会， 比如[@fzamperin did for NodeSchool](https://github.com/nodeschool/organizers/issues/406) 

- 组织项目的会议(如果有的话)

- 帮助社区成员网罗合适的会议和提交发言建议 

##### ***你喜欢设计么***

- 重构布局， 提升产品的可用性

- 实施用户调研， 重构和完善产品的导航或菜单，比如像这样[Drupal suggests](https://www.drupal.org/community-initiatives/drupal-core/usability)

- 创造艺术比如t-shirt 或者一个新logo， 比如像这样[hapi.js’s contributors did](https://github.com/hapijs/contrib/issues/68)

##### ***你喜欢写作么***

- 书写提升项目的文档质量

- 组织examples的文件夹， 展示项目是如何使用的

- 整理项目的时事通讯录， 从邮件列表中组织一下关键点

- 翻译文档

    认真地讲， 文档非常非常重要， babel的文档非常棒， 
    扮演着杀手锏的角色， 有一些章节很花费功夫
    甚至在不同地方添加额外的段落， 这非常赞！
    — @kittens, “Call for contributors”

##### ***你喜欢组织工作么***

- 重复的issue进行链接， 建议新issue的label， 让事情井然有序

- 仔细检查open状态的issue， 建议关闭旧的issue 像这样[@nzakas did for ESLint](https://github.com/eslint/eslint/issues/6765)

- 在最新的issue提出好的问题（清晰， 准确， 精确）， 推动讨论

##### ***你喜欢写代码么***

- 找一个open状态的issue， 然后解决它

- 询问是否可以开发一个新的feature

- 项目启动工程化改造

- 提升工程化水平和测试覆盖率

##### ***你喜欢帮助他人么***

- 回答他人有关项目的问题， 比如这样[like this Postgres example](https://stackoverflow.com/questions/18664074/getting-error-peer-authentication-failed-for-user-postgres-when-trying-to-ge) stackoverflow 或者reddit

- 回答issue相关的问题

- 帮助调节谈论去和对话通道

##### ***你喜欢帮助他人写提升代码质量么***

- 对别人的代码提交做review

- 写有关项目使用的教程

- 对他人提供指导， 像这样[@ereichert did for @bronzdoc on Rust](https://github.com/rust-lang/book/issues/123#issuecomment-238049666)

##### ***你也不一定要参与软件项目***

开源通常指代软件， 你也可以协作任何事情， 比如书籍， 食谱， 清单， 课程等借助开源开发的任何事情

比如：

- [@sindresorhus curates a list of “awesome” lists](https://github.com/sindresorhus/awesome)

- [@h5bp maintains a list of potential interview questions for front-end developer candidates](https://github.com/h5bp/Front-end-Developer-Interview-Questions)

- [@stuartlynn and @nicole-a-tesla made a collection of fun facts about puffins](https://github.com/stuartlynn/puffin_facts)

即使你是一个软件开发者， 文档工作也可以帮你参与到开源中去， 参与项目但不提交代码通常并不会令人生畏， 参与的过程可以帮你树立信心， 积累经验


### **新项目指南**


> 如果你去看issue跟踪器， 很多人你会感到困惑 这些工具需要大量的隐藏知识， 别人可以帮你指引方向， 你也可以问他们问题— @shaunagm, “How to Contribute to Open Source”

除了修复错别字之外， 参与开源就像在一个party上走向一群陌生人，如果你开始谈论美洲驼， 而其他人在谈论金鱼， 他们可能会用一点奇异的眼光看你。

在盲目地提出建议之前， 先要观察一下房间， 这样可以增加你的想法被注意和倾听的机会 

##### ***剖析一个开源项目***

每一个开源社区都各不相同

在一个开源项目上投入数年， 意味着你已经知道了一个开源项目， 转移到一个不同的项目上， 你会发现词汇， 规范， 以及社区形态截然不同

也就是说， 很多开源项目遵循相似的组织架构， 了解社区角色和整体流程的差异， 可以帮你快速适应任何新项目

一个典型的开源项目包含以下几类人

- 作者（author）： 创造这个项目的人或组织

- 所有者（owner）： 对组织或repository持有管理所有权的人(与author并不总是相同)

- 维护者（maintainer）： 负责推进项目愿景和掌控项目组织工作的贡献者

- 贡献者（contributor）：所有为项目做出过贡献的人

- 社区成员: 使用项目的人， 他们可能积极对话或者对项目的方向发表自己的观点

更大一些的项目可能还有小组委员会或者对应不同事务的工作组，比如工具， 分类， 社区审核和事件组织， 在项目的网站上查看‘团队’页面， 或者管理文档的存储库中查找这些信息

一个项目还有文档， 这些文档通常在仓库的最顶层

- 许可（lisence）：根据定义， 每个开源项目都必须有一个开源许可， 如果没有许可证，那么它不是开源的

- README： 指导手册， 欢迎新社区成员加入项目， 它解释为什么这个项目是有用的， 以及如何开始。

- 贡献（contributing）： readme文档帮助人们使用项目， 文献文档帮助人们为项目做贡献， 它解释了需要哪些类型的贡献以及这个过程是如何工作的。虽然不是每个项目都有贡献文件，但它的存在表明这是一个值得贡献的项目。  

- CODE_OF_CONDUCT: 行为守则为参与者的相关行为设定了基本规则，有助于培育友好的环境。虽然不是每个项目都有CODE_OF_CONDUCT文件，但它的存在表明这是一个值得贡献的项目。

- 其他文档:可能还有其他文档，比如教程、演练或治理策略，尤其是在大型项目上。

最后，开源项目使用以下工具来组织讨论。阅读这些档案会让你对这个社区的想法和运作有一个很好的了解。

- issue tracker:人们讨论与项目相关的问题的地方。

- pull request:人们讨论和检查正在进行的更改的地方。

- Discussion forums or mailing lists:一些项目可能会使用这些渠道来讨论主题(例如，“How do I…”或“What do you think about…”而不是bug报告或功能请求)。其他人对素有问题使用issue tracker。

- 同步聊天通道:一些项目使用聊天通道(比如Slack或IRC)进行非正式对话、协作和快速交流


### **找一个项目参与**

> 既然您已经了解了开源项目是如何工作的，现在是时候找到一个项目来贡献自己的力量了!

如果你以前从未为开源做过贡献，那就听听美国总统约翰f肯尼迪(John F. Kennedy)的建议。肯尼迪曾说过:“不要问你的国家能为你做些什么，而要问你能为你的国家做些什么。”

对开源的贡献发生在所有级别，跨项目。你不需要过多地考虑你的第一个贡献是什么，或者它看起来会是什么样子。相反，从你已经使用或想要使用的项目开始。你将积极贡献的项目是你发现自己不断回顾的项目。

在这些项目中，无论何时你发现自己认为某件事可能会更好或不同，那就根据你的直觉行事

开源并不是一个排外的俱乐部;它是像你一样的人做的。“开放源码”只是一种解决世界问题的美好形式。

> 对开放源代码的常规贡献中有[28%是文档](https://www.igor.pro.br/publica/papers/saner2016.pdf)，比如错误修复、重新格式化或编写翻译

您也可以使用以下资源之一来帮助您发现和贡献新的项目:

- [GitHub Explore](https://github.com/explore/)
- [Open Source Friday](https://opensource.guide/how-to-contribute/)
- [First Timers Only](http://www.firsttimersonly.com/)
- [Your First PR](https://yourfirstpr.github.io/)
- [CodeTriage](https://www.codetriage.com/)
- [24 Pull Requests](https://24pullrequests.com/)
- [Up For Grabs](https://up-for-grabs.net/)
- [Contributor-ninja](https://contributor.ninja/)

##### ***参与之前的清单***

当你找到一个你想要贡献的项目时，快速扫描一下，确保这个项目适合接受贡献。否则，你的努力工作可能永远得不到回应。

这里有一个方便的清单来评估一个项目是否适合新的贡献者。

满足开源的定义

- 它有许可证么吗?通常，这是存储库根中的一个名为LICENSE的文件。

项目积极接受代码提交

查看主分支上的提交活动。在GitHub上，您可以在仓库的主页上看到这些信息。

- 最近一次提交是什么时候?

- 这个项目有多少贡献者?

- 人们贡献的频率怎样?(
在GitHub上，你可以通过点击顶部的“提交”来找到它。)

接下来，看看这个项目的问题（issues）。

- 有多少悬而未决的问题?

- 当打开问题时，维护人员会快速响应吗?

- 关于这些问题是否有积极的讨论?

- issue时效是否为最新?

- 问题是否被关闭?(在GitHub上，单击“已关闭”选项卡，查看已关闭的问题。)

现在对项目的pull request执行相同的操作。

- 有多少打开pull request?

- 在打开pull request，维护人员会快速响应吗?

- 对于pull request是否有积极的讨论?

- pull request是最近的吗?

- 最近是否合并了任何pull request?(在GitHub上，点击pull request页面上的“关闭”选项卡，查看关闭的PRs。)

项目受欢迎

一个项目友好表示他们将包容新的贡献者。

- 维护人员是否对问题中的问题做出有益的响应?

- 在问题、讨论论坛和聊天(例如IRC或Slack)中，人们是否友好?

- pull request 有review么

- 维护人员是否致谢贡献者?

> 当您看到一个长线程时，您可以在线程中看到来自核心开发人员的响应。他们是否有建设性地进行总结，并采取措施在保持礼貌的同时将思路带向决策?如果你看到战争纷飞，这通常是精力导向争论而不是发展的信号。— @kfogel, Producing OSS

### **如何(正确)提交代码**

> 你已经找到了一个你喜欢的项目，你已经准备好做出贡献了, 以下是如何以正确的方式获得你的贡献。

##### ***有效地沟通***

无论您是一次性的贡献者还是尝试加入社区，与他人合作是您在开放源代码中开发的最重要的技能之一。

> (作为一名新贡献者)我很快意识到，如果我想要结束这个问题，我就必须提出问题。我浏览了一下代码库。一旦我对发生了什么有了一些了解，我就要求更多的方向。瞧!在得到了我需要的所有相关细节之后，我终于解决了这个问题。 — @shubheksha, A Beginner’s Very Bumpy Journey Through The World of Open Source

在提问或者发起pull request时，或者在聊天中问一个问题之前，记住这些要点，以帮助有效地实现你的想法。

给问题的场景。帮助别人快速理解。如果您遇到错误，请说明您正在尝试做什么，以及如何重现错误。如果你在提出一个新想法，解释一下为什么你认为它对项目有用(不仅仅对你有用!)

```
  “X doesn’t happen when I do Y”

  “X is broken! Please fix it.”
```

事先做好功课。不了解不要紧，但要表现出你的努力。在寻求帮助之前，一定要检查项目的自述文件、文档、问题(打开或关闭)、邮件列表，并在互联网上搜索答案。当你表现出你在努力学习时，别人会欣赏你。

```
  “I’m not sure how to implement X. I checked the help docs and didn’t find any mentions.”

  “How do I X?”
```

保持请求的简短和直接。就像发电子邮件一样，每一个贡献，无论多么简单或有用，都需要别人的review。许多项目收到的请求比可以提供帮助的人要多。保持简洁。你将增加有人帮助你的机会。

```
  “I’d like to write an API tutorial.”

  “I was driving down the highway the other day and stopped for gas, and then I
   had this amazing idea for something we should be doing, but before I explain
    that, let me show you…“
```

保持所有公共公开。私下接触维护人员尽管这很诱人，但不要这样做，除非您需要共享敏感信息(比如安全问题或严重的行为违规)。当你公开谈话时，更多的人可以从你的交流中学习和受益。讨论本身就是贡献。

```
  (as a comment) “@-maintainer Hi there! How should we proceed on this PR?”

  (as an email) “Hey there, sorry to bother you over email, but I was wondering 
  if you’ve had a chance to review my PR”
```

问问题是可以的(但要有耐心!)每个人在某个时候对这个项目都很陌生，即使是经验丰富的贡献者在他们看到一个新项目时也需要加快速度。出于同样的原因，即使是长期的维护人员也不总是熟悉项目的每个部分。向他们展示你希望他们展示给你的耐心。

```
  “Thanks for looking into this error. I followed your suggestions. Here’s the output.”

  “Why can’t you fix my problem? Isn’t this your project?”
```

尊重社区的决定。您的想法可能与社区的优先级或远景不同。他们可能会提供反馈，或者决定不遵从你的想法。您应该讨论并寻找妥协，维护人员认同你的决策所用的时间比你自己所用时间要长。如果你不同意他们的观点，你就可以自己动手fork，开始自己的项目。

```
  “I’m disappointed you can’t support my use case, but as you’ve explained it
   only affects a minor portion of users, I understand why. Thanks for listening.”


  “Why won’t you support my use case? This is unacceptable!”
```

最重要的是，保持优雅。开源是由来自世界各地的合作者组成的。上下文在跨越语言、文化、地理和时区时丢失。此外，书面交流也使得表达语气或情绪变得更加困难。在这些对话中预设良好的意图。你可以礼貌地拒绝一个想法，询问更多的背景信息，或者进一步阐明你的立场。努力让互联网变成一个更好的地方。

##### ***收集场景上下文***

在做任何事情之前，先快速检查一下，确保你的想法没有在其他地方讨论过。略去项目的自述、问题(打开和关闭)、邮件列表和堆栈溢出。你不需要花几个小时浏览每一件事，但是快速搜索几个关键的词汇会大有帮助。

如果你在别的地方找不到你的想法，你就准备好采取行动了。如果项目在GitHub上，您可能会通过打开一个问题或拉出pull request来进行沟通:

- issues就像开始谈话或讨论一样

- pullrequest是用来启动解决方案的。

- 对于轻量级的通信，比如澄清或操作的问题，试着询问Stack Overflow、IRC、Slack或其他聊天频道, 如果项目有的话。

在打开问题或pull request之前，检查项目的贡献文档(通常是一个名为贡献的文件，或者在自述文件中)，看看是否需要包含任何特定的内容。例如，他们可能会要求您遵循一个模板，或者要求您使用测试。

如果你想做出实质性的贡献，在着手解决之前，先提出一个issue。在GitHub上看一段时间的项目是很有帮助的(在GitHub上，你可以点击“watch”来获知所有的对话)，在工作之前了解社区成员， 不然很可能不会被接受。

> You’ll learn a lot from taking a single project you actively use, “watching” it 
on GitHub and reading every issue and PR. — @gaearon on joining projects

### **open一个问题**

你通常应该在以下情况下提出一个问题:


- 报告一个你自己无法解决的错误

- 讨论一个高级主题或想法(例如，社区、远景或策略)

- 提出一个新特性或其他项目想法

沟通问题的技巧:


- 如果你看到一个你想要解决的公开问题，就评论这个问题，让人们知道你正在处理它。这样，人们就不太可能重复你的工作。

- 如果一个问题是在一段时间之前打开的，那么它可能正在其他地方被处理，或者已经被解决，所以请在开始工作之前请求确认。

- 如果你打开了一个问题，但后来自己找到了答案，那么就对这个问题发表评论，让人们知道，然后结束这个问题。甚至记录这个结果也是对项目的贡献。

##### ***打开一个pull request***

在下列情况下，你通常应该打开一个pull请求:


- 提交琐碎的修复(例如，一个错误、一个坏链接或一个明显的错误)

- 开始做一个已经被要求的贡献，或者你已经讨论过的问题

pull request并不意味着已经完成的工作。通常情况下，最好是尽早打开一个请求，这样其他人就可以观察或反馈你的进展情况。在subject line上把它标记为“WIP”(正在进行中的工作)即可。以后可以添加更多的提交。


如果项目在GitHub上，下面是提交pull request的方式:


- Fork存储库并在本地克隆它。通过将本地存储库添加为远程存储库，将其连接到原始的“上游”存储库。经常从“上游”中pull更改，以便您保持最新，提交拉请求时，合并冲突的可能性更小。[(请参阅这里的详细说明。)](https://help.github.com/articles/syncing-a-fork/)

- 为变动创建一个[分支](https://guides.github.com/introduction/flow/)。

- 在您的PR中引用任何相关的问题或支持文档(例如，“关闭#37”)。

- 如果您的更改包含HTML/CSS的差异，请包含前后的屏幕截图。将图像拖放到您的拉请求的主体中。

- 测试您的更改!如果存在任何现有的测试，运行您的更改，并在需要时创建新的测试。无论测试是否存在，请确保您的更改不会破坏现有的项目。

- 在项目的风格上尽你最大的努力。这可能意味着使用缩进、半冒号或注释与您在自己的存储库中使用的不同，但是使维护人员更容易合并，其他人更容易在将来理解和维护。

如果这是您的第一个pull request，请查看[案例](http://makeapullrequest.com/)，这是@kentcdodds作为一个演练视频教程创建的。您还可以在@Roshanjossey创建的第一个贡献存储库中练习发出pull request。

[6 提交代码之后需要做什么](postPr.md)
### **提交代码之后需要做什么**

> 你做到了!祝贺您成为开源贡献者。我们希望这众多参与中的第一个。

你提交commit之后， 下面中的一件事情接着会发生

##### ***没有反馈***

希望您在做出贡献之前检查了项目的活动迹象。然而，即使是在一个活跃的项目上，你的贡献也可能得不到响应。


如果你一个多星期都没有收到回复，那么你可以礼貌地在同一个帖子里回复，让别人给你写评论。如果你知道评审你的贡献的人，你可以@-在这个帖子里提到他们。


不要私下和那个人接触;请记住，公共通信对于开源项目是至关重要的。


如果你礼貌地撞了一下，仍然没有人回应，很有可能永远不会有人回应。这种感觉并不好，但不要因此而气馁。这种事会发生在每个人的身上!你没有得到回复的原因有很多，包括你无法控制的个人情况。尝试寻找另一个项目或方式来贡献。如果有的话，这是一个很好的理由，在其他社区成员参与和响应之前，不要在做出贡献上花费太多时间。

##### ***有人让你对贡献做出变动***

您经常会被要求对您的贡献进行更改，无论是对您的想法范围的反馈，还是对代码的更改。


当有人请求更改时，要做出响应。他们花了很多时间来review你的贡献。打开PR然后走开是不好的。如果你不知道如何做出改变，研究一下这个问题，如果你需要的话，可以寻求帮助。


如果您不再有时间处理这个问题(例如，如果对话已经进行了几个月，并且您的环境发生了变化)，让维护人员知道，这样他们就不会期望得到响应。其他人可能很乐意接手。

##### ***你的贡献不被接受。***

你的贡献最终可能被接受，也可能不被接受。希望你没有做太多的工作。如果您不确定为什么不接受它，那么完全有理由要求维护者提供反馈和澄清。然而，最终，你需要尊重这是他们的决定。不要争论，也不要怀有敌意。如果您不同意，欢迎您fork然后在自己版本上工作!

##### ***你的贡献被接受***

万岁， 您已经成功地做出了开源贡献

### **你可以做到的**

无论您是刚刚完成您的第一个开源贡献，还是您正在寻找新的贡献方式，我们都希望您能够受到启发，采取行动。即使你的贡献没有被接受，当一个维护人员努力帮助你时，请不吝表达感激。开源是由这样的人做的:一个问题，一次pull request，评论，或者击掌。

---

[原文:How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
