---
layout: post
title: "选择Github Pages + Jekyll的理由"
description: ""
category: Web
tags: [杂记, Github]
---
{% include JB/setup %}

进入二十一世纪第二个十年，互联网的发展态势依然迅猛。对于我们这些80后的IT从业者来说，网络信息量的持续爆炸式增长与有限的脑细胞容量使得个人知识的存储与处理成为了很严重的问题：刚刚申请的帐号密码转眼便已遗忘，零散的笔记文章与收藏遍布各大博客网站然而大都不会再看一眼，多年前的博文因服务关闭而永久消匿，……

为了提高知识的使用效率，避免其过高的遗忘、检索成本，我们需要对个人知识进行管理。我的观点是，抛云浮夸的诱惑，把个人内容集中起来。通常来说，个人的网络知识包含以下内容：1，公开知识，如博客；2，私人记事，如日记；3，参考知识，这类知识比较零散，通常是文章的灵感来源；4，素材，如照片、视频资料。

公开知识存储的常见方式便是博客，博客表达了作者的公开意见，或者客观事实，可以与网络用户进行充分的交流。网络上的博客服务数不胜数，本文不赘述。私人记事可以采用Evernote之类的知识管理应用，对于日记这种特殊类型可以使用Ohlife.com的服务。参考类知识也可以通过知识管理应用维护，但维基百科通常是更好的选择。网络上有不少维基引擎，如MediaWiki, 互动百科等。更轻量级的选择是Vimwiki。对于照片类素材来说，选择范围也是非常的广，国内的服务基本都能满足应用，如QQ的空间相册、网易相册、又拍网，国外则有Flickr，如果是图片收藏，则有花瓣这类的应用。视频类不必多言，选择太少。

本文偏挖一隅，讲讲为何要选择Github Pages + Jekyll来搭建博客。最近几年，越来越多的人正从Wordpress迁徙到Jekyll上，这并不单单是因为好奇心。

先说说Github Pages, 这是Github提供的静态站点托管服务，后台基于Jekyll引擎。与Dropbox Pages相比，Github Pages有着先天的优势：站内的内容可以通过Git来进行版本控制。事实上，Github Pages关联的是用户的Github中的一个代码仓库(Repo)，用户若要更改站点中的内容中，只需要在该仓库中进行提交即可。既然是一个Repo，而又因为Git天生是分布式的，那么基本上不用担心数据丢失的问题。本地的.git将见证所有历史。

其实提供静态网站托管的服务也有不少，但Github并不算严格的静态的，因为它采用的是Jekyll博客引擎，支持Markdown标记语言与Liquid模板语法。这样一来，用户写博客更像是在写作，而不需要关心繁琐的格式细节。此外，利用Liquid模板语言，用户对自己博客享有充分的定制自由度。目前Jekyll已有拥有相当多的用户群体，在Jekyll的官方文档中可以找到一些由Jekyll驱动的样例网站。

还有一个不得不提的理由：Github Pages是免费的。Linus Torvalds曾有句名言：
>Software is like sex; it's better when it's free