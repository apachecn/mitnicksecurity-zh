# 渗透测试报告剖析[信息图]

> 原文：<https://www.mitnicksecurity.com/blog/the-anatomy-of-a-penetration-testing-report-an-infographic>

各行各业的专家都会捍卫执行常规渗透测试的价值，但并非所有的渗透测试都是平等的。

对于那些接受测试的人来说，只有报告的详细和全面才是有价值的，他们才能理解如何最好地应用测试结果。

虽然有六种类型的渗透测试[](https://www.mitnicksecurity.com/blog/understanding-the-6-main-types-of-penetration-testing)，但每份报告都应该有类似的结构——遵循渗透测试的四个阶段[——不管是谁执行的。](https://www.mitnicksecurity.com/blog/the-4-phases-of-penetration-testing)

在我们之前的帖子中，[*Pentest 报告中包含了什么内容*](https://www.mitnicksecurity.com/blog/whats-included-in-a-penetration-test-report) *，*我们从高层次上看了一下攻击后您可能会收到什么内容。在这次深入剖析 pentest 的过程中，我们将分析你通常能从最终报告中得到什么。

![Mitnick_PenetrationTesting-Infographic_final-02222021](img/212c4fb70f243168a6be265c4beb4487.png)

## 执行摘要

执行摘要就像它听起来的那样:报告发现的摘要，给公司的管理人员看。

这份完整报告的缩略版旨在用简单易懂的语言为高管们提供可操作的要点，不涉及技术细节。由于其简洁、直接的性质，大多数 pentest 报告都以这种高层次的概述开始。

以下是您可以期望测试报告的执行摘要包括的一些内容:

### 积极的观察

一些 pentesters 喜欢从一些公司在安全措施方面做得很好的例子开始。由于报告的大部分主要集中在主题的安全性失败的方式上，这一开头部分可以帮助提醒读者，至少他们的部分防御和努力是值得认可的。

#### 正面观察的例子

*   当(某个员工)得到(特定安全尝试)警报时，他向 IT 部门报告了可疑活动
*   (特定员工或员工组)的浏览器中没有缓存密码，这使得 pentesters 更难找到进入的途径

### 攻击者目标完成

从一开始，pentester 就会详细说明一旦他们攻破了目标的基础设施，他们能够做些什么。这通常被编辑成一个项目列表，揭示了 pentester 完成的成就的摘要。

#### 实现的目标示例

*   提取域上的所有(电子邮件提供商)用户密码哈希
*   受损(服务器名称或端点)
*   获得对预定义目标(即知识产权、源代码、财务信息、客户名单等)的访问权限。)或获得在此过程中发现的先前未识别的目标的访问权

### 战略建议

在 pentesters 概述了他们从哪里获得访问权限后，他们将深入到他们对减轻、转移或接受您的风险的建议中。

正是在这一点上，他们将把短期、中期和长期目标分解得很清楚。

#### 目标桶示例

这些不同的类别将根据您的 pentester 而有所不同，但它们应该在其独特的评分系统中明确定义每个目标类型的参数。

以下是我们在 Mitnick Security 中划分目标的方式:

*   短期目标建议在测试后三个月完成
*   在六个月内实现中期目标
*   未来两年内的长期目标

您的战略建议将根据您独特的业务问题进行高度定制，但为了便于举例，以下是您可能会在抽样测试报告中看到的一些常见要点:

#### 建议示例

*   设置最少 25 个字符的[](https://www.mitnicksecurity.com/blog/8-password-security-tips-from-kevin-mitnick-for-better-login-protection)密码策略，不强制使用大小写、数字或符号
*   在面向外部的登录界面上启用多因素身份认证，并且在支持多因素身份认证的情况下，确保对每个人强制实施多因素身份认证
*   将密码管理器应用程序配置为在空闲 15 分钟后注销

在上面的例子中，所有的建议都与密码管理有关，但是真正的测试报告会提供一系列的建议，涵盖目标的安全问题的全貌。

**查看抽样测试报告时，寻找可行的、有用的建议**。像“改进密码管理”这样的建议过于宽泛和不具体。

另一方面，要警惕那些过于具体的圣灵降临者。Mitnick 安全团队是产品不可知的，这意味着我们很少推荐特定的软件/产品作为解决方案:技术总是在变化，行业与行业之间的业务需求也不尽相同。相反，我们为您需要做的事情提供建议。从那时起，内部安全团队可以选择使用谁或什么来实现概述的安全目标。

### 自定义功能

具有特定或独特目标的公司可能需要在传统的测试报告模板中进行自定义。例如，如果你想更深入地了解你的风险阈值，你的报告可以包括一个关于你所在行业的*风险评级&比较*的小节。

如果您希望安全团队分析或探索某个重要元素，请确保选择一个愿意满足您期望的合作伙伴。

## 目标和范围

一旦报告开始详细讨论目标和范围，这通常是一个清晰的指标，表明*执行摘要*部分的结束。测试报告的以下部分面向 IT 专业人员以及公司内外负责制定战略建议的人员。在这里你会看到清晰定义的目标，那些测试人员和目标在测试前达成一致的目标。

#### 目标和范围示例

*   在(客户的)(特定基础架构)上执行外部网络渗透测试。
*   执行网络渗透，以确定外围安全控制的有效性，并评估检测能力。
*   提供一份全面的报告，详细说明任何已识别的漏洞，并提供修复任何已识别的安全缺陷的建议。

这一部分对于那些从一开始就不了解测试意图的人来说至关重要，可以让他们理解测试的主要目标。也是在这里，你可以看到一个精心安排的时间表，例如，包含了一个 6 周的有明确日期的测试。

## 年代叙事

接下来，您将看到 pentesters 为实现其目标而采用的各个攻击媒介的详细说明。

您会发现这一部分通常是一致的，因为它将详细说明 pentesters 如何策划和采取初步的立足点，逐步升级访问，并在整个基础架构中进行横向移动，直到实现其预期的访问。

尽管结构和攻击媒介通常相似，**渗透测试报告的这一部分非常针对客户的*****，一步一步地概述了 pentesters 如何进入他们的确切系统。通过这种方式，每个叙述都将是独一无二的，通常会展示特定的截屏和攻击媒介的示例以及由此导致的升级。***

 *叙述将分解每种攻击方法，解释 pentester 到底做了什么，以及他们如何能够操纵用户和技术来危害您的安全。

然而，详细程度和解释将很大程度上取决于你选择的测试公司。在米特尼克安全公司，我们不同于其他 pentesting 报告，在我们独特的故事叙述。与其他只显示结果表格的 pentesters 不同，我们清楚地概述了我们如何开始测试的一步一步的解释，以一种播放播放的方式列出了具体的方法，通常带有图片和视觉效果，以讲述我们如何获得访问权限的完整故事。

## 网络钓鱼和社会工程

网络钓鱼和 [社交工程](https://www.mitnicksecurity.com/blog/social-engineering-attacks) 经常在任何渗透测试中扮演如此重要的角色，以至于 pentests 经常在报告中留出单独的部分来概述特定于社交工程的攻击媒介。

该部分通常会显示被攻击员工的姓名和电子邮件地址，以及发送的网络钓鱼电子邮件的准确截图、漏洞利用持续时间的时间表等等。

## 技术漏洞

在解释了每个攻击媒介的详细信息后，pentesting 报告将按照严重性顺序列出每个漏洞的完整建议列表。

就像每个 pentester 在执行摘要中都有自己推荐的目标阈值一样，pentester 将定义自己独特的漏洞评级系统。通常，您会看到五种不同的风险:

1.  关键风险
2.  高危
3.  中等风险
4.  低风险
5.  信息(无风险)

#### 风险评级系统示例

**这是我们在 Mitnick Security 的风险评级系统的一个例子:**

**![Mitnick_PenetrationTesting-Infographic_technical-vulnerabilities-example](img/79a655a0e1c9b2fc3c4bfae2d8227728.png)**

#### 补救措施图表示例

在那里，您通常会找到针对每个漏洞的建议补救措施项目。这通常被组织成一个图表，可能看起来像这样:

![Mitnick_PenetrationTesting-Infographic_remedial-actions-chart-example](img/76e66f5a53aed2d321ae3ddb6d8c682b.png)

这样，你的渗透测试报告就完成了。

在 Mitnick Security，我们允许我们的客户有 10 天的时间来审查和要求澄清或调整他们的报告——这项服务并不是所有的 penetesters 都提供的。

## 寻找什么样的伴侣

既然您已经了解了从全面的渗透测试报告中可以期待什么，那么是时候开始寻找合适的合作伙伴了。

当决定一个 pentester 时，寻找一个根据你的组织的独特需求定制他们的方法的公司——他们不会给你留下含糊的和无益的千篇一律的报告。

[**在选择合适的伴侣**](https://www.mitnicksecurity.com/blog/4-considerations-before-choosing-the-right-type-of-pentesting-company) **之前，这里有四个考虑因素，帮助你选择最适合你目标的伴侣。**

对渗透测试报告如何改变您的安全性感到好奇吗？了解我们在 Mitnick Security 的团队如何帮助客户发现关键漏洞，并做出重大改变来提高他们的防御能力。

了解 Mitnick Security 如何帮助世界冲浪联盟发现其漏洞并提出改进建议。*