title:  扩散注意力：应对软件工程的复杂度(2)
date: 2015-08-12 22:17:34
categories: translation
tags:
- software engineering
---

> 原文：http://deconcentration-of-attention.com/
> 翻译 repo：https://github.com/dopcn/deconcentration-of-attention-cn

# 1. 背景 vs. 关注对象

从背景信息中隔离出关注对象一般被认为是注意力的主要功能。有些时候甚至可以尝试将注意力集中在注意力所起到的隔离作用本身。注意力在 wikipedia.org 上的定义如下：

> 注意力是一个将注意力集中在环境中的某一方面忽略其他方面的认知过程。

如果我们将注意力放在其本身，就可以发现注意力并不是一个抽象的事物，他是一个实际的能力，包含多种功能。

在下图中

![image1](http://s295901768.onlinehome.us/deconcentration/images/01-cup-01.png)

注意力，通常位于眼睛所看的位置，会隔离或者应该说是创造出一个茶杯的图像。为了形成茶杯的图像在背景中的其他元素统统被过滤掉。注意力也可以创造其他图像，例如茶匙或者桌子的图像。

下图是注意力在创造图像时构建的层次结构：

![image2](http://s295901768.onlinehome.us/deconcentration/images/02-cup-spoon-diagram.png)

这种层次的处理方式用于处理某一些问题是很合适的。但对于其他问题，将图片作为一个不可分割的整体可能才是更好的方式，也就是说注意力的成像功能要停止运作。这种方式之下屏幕上和黑点变成不可分割，黑点和白点具有同样的意义，甚至屏幕上的灰尘也一样，而在前一种处理方式中灰尘是被完全忽略掉了的。这样以来将不存在任何图形只有一个不可分割包含一切的背景。这种认知能力可以通过训练来获得。

如果我们明白对背景的整体认知是如何在大脑空间中运行的，就会更清楚地认识到软件工程需要这种对背景的整体认知。

让我们想象一个网络服务器

![image3](http://s295901768.onlinehome.us/deconcentration/images/03-web-server-solo.png)

在实际中，我们的想象会发生特定的上下文中，一个规模很大的上下文。

![image4](http://s295901768.onlinehome.us/deconcentration/images/04-web-server-context.png)

除了对网络服务器的一般定义，这个上下文包含了一些具体的服务器和所有相关的概念，例如协议，标准，编程语言，操作系统和硬件。全部的大学学校学习也是这个上下文的一部分。这个上下文也可以称之为背景。

常说的「某个人的专业背景」描述的正是字面上的意思，一个思想上的背景。

![image5](http://s295901768.onlinehome.us/deconcentration/images/05-web-server-context-hierarchy.png)

在这个例子中「网络服务器」是一个思想上被隔离出来的图像，所有的上下文信息是他的背景。换一个说法我们可以说「网络服务器」从他的背景中被有意识的识别出来，而他的背景则处于无意识的状态。如果需要注意力可以转移到背景中某个特定的元素上去。然而同时处理所有的元素也是有可能的。

这种特殊的思维活动与一般的思考不同，一般的思考中注意力会线性关注每一个单独元素。这种不同的思考方式有他不同的优势和劣势，适用于解决不同类型的问题。这种思考方式最适合于解决没有明显解决方式或可能获取解决方式的途径的问题。

下面我们来研究一下在思维的大背景下信息是怎样组织起来的，以及怎样可以主动进行这样的组织。