+++

title = "怎么选择和快速搭建个人博客"
date = 2017-10-20
description = "直观展示10种不同的博客搭建方式，帮助你选择适合自己的个人博客网站。"
draft = false
toc = true
tags = ["Blog", "博客", "Markdown", "git", "Github Pages", "Coding Pages", "SegemtFault", "简书", "知乎", "CSDN", "博客园", "hexo", "hugo", "jekyll", "WordPress", "ghost"]

+++



<!--

# 怎么选择和快速搭建个人博客
tags: [blog, 博客, markdown, git, github pages, coding pages, segemtfault, 简书, 知乎, CSDN, 博客园, hexo, hugo, jekyll, wordpress, ghost]

 -->


本来只是想搭建一个博客让自己凌乱的笔记显得正常和体面一些，但是被网上各种各样的技术带入各种坑位，本着不折腾不会死的态度全部通关一遍，于是便有了此文。我尝试了10个目前比较流行的搭建博客的方式，通过搭建的技术门槛和颜值等分别做简单介绍，如果你正准备搭建一个博客，能够比较直观的了解目前流行的技术和最终的实现效果，帮助你做出适合自己的选择。（本文偏向技术类博客，但也适用其他工种）

<!--more-->

:warning: 本文多图预警，没有详细的博客安装教程，安装请查看官方文档或自行摆渡**xx教程、xx一键包**。

---

## 怎么面对博客 :bow:

- 博客不像微博，有一定的含金量，而不是走马灯的宣言（拿微博治国的人不代表大多数
- 写作的过程其实就是思考的字面化，梳理知识体系的同时反思知识的内化程度，分清楚哪些是“知道了”，哪些是“掌握了”
- 通过博客的形式分享是学习的一种技巧（费曼技巧，让小孩子明白你要讲述的内容），内化知识的同时也从分享中得到快乐
- 用写作来记录成长的过程，保持这种习惯能让你听到意志力成长的声音（zi...
- 同时博客也是一种无形的资产，量变的积累过程兴许会带来许多隐形的机会（接广告，出书啊等等知乎上忽悠的），总之多写总没错

---

## 怎么把博客放到网上 :earth_asia:

目前比较流行的博客实现可以分为三种方式，各有不同程度的技术门槛、功能支持、主题颜值等。接下来将会通过实例展示不同的博客形式。

- :point_right: **个人主页注册**。指的是在现有的博客网站、论坛或社区上注册个人主页

- :point_right: **静态网站生成**。通常是由jekyll、hugo或hexo等技术生成静态网站，然后通过git上传到Github Pages、Coding Pages等托管平台免费展示

- :point_right: **内容管理系统**。带有后台管理的博客系统，需要配置空间（服务器）、数据库以及域名等，然后安装成熟的WordPress、ghost等内容管理系统


### 一) 个人主页注册

:pill: 注册形式的个人博客，优势是没有技术门槛，注册即用；拥有成熟的平台支持，方便推广。但是平台风格单一，不仅自定义程度低，而且还有许多形式限制（当然限制也有专心于内容的好处），推荐给嫌麻烦不喜欢折腾又不反感条条框框的人。


#### 1) [SegmentFault](https://segmentfault.com/) :+1:

- 中式StackOverFlow论坛，成熟的技术交流平台
- 网站提供文章专栏板块，并且有审核机制
- 功能： Markdown / 标签 / 评论 / 智能目录
- :lipstick: 颜值：正常 / 简洁

<img src="https://ws4.sinaimg.cn/large/006tKfTcly1fkk34th9foj31kw1ijne4.jpg" alt="segmentfault" width="100%">


#### 2) [简书](http://www.jianshu.com/) :+1:

- 专注文字的轻博客平台，定位清新
- 功能：Markdown / 评论 / 标签
- :lipstick: 颜值：正常 / 干净

<img src="https://ws1.sinaimg.cn/large/006tKfTcly1fkk4w40v4sj31kw0t4n47.jpg" alt="jianshu article list" width="100%">

<img src="https://ws2.sinaimg.cn/large/006tKfTcly1fkk4w91rw8j31kw1l5wnj.jpg" alt="jianshu artical content" width="100%">


#### 3) [知乎](https://www.zhihu.com/)

- 泛娱乐化的专业知识交流平台，提供文章板块
- 功能：Markdown / 评论 / 标签
- :lipstick: 颜值：正常 / 大气

<img src="https://ws1.sinaimg.cn/large/006tKfTcly1fkk3popy90j31kw1oa480.jpg" alt="zhihu" width="100%">



#### 4) [CSDN](http://www.csdn.net/)

- 老牌技术论坛
- 关注公众号才能注册，8位数验证码等一堆反人类交互体验很不是能忍
- 功能：Markdown / 评论 / 标签 / 皮肤 / 老式文章管理
- :lipstick: 颜值：不卸妆的话还能看，卸妆就...

<img src="https://ws1.sinaimg.cn/large/006tKfTcly1fkk4x9dhclj31kw0qx7dv.jpg" alt="csdn" width="100%">


#### 5) [博客园](https://www.cnblogs.com/)

- 元老级技术论坛，申请博客需要人工审核（上班时间8分钟通过
- 功能：Markdown / 评论 / 标签 / 老式文章管理 / RSS / 年代感皮肤 / 相册 / 文件
- :lipstick: 颜值：Logo可以有不止3种Word渐变色3D投影展示，老得有味道

<img src="https://ws4.sinaimg.cn/large/006tKfTcly1fkk5mcy351j31kw1dlh26.jpg" alt="cnblogs" width="100%">


注册形式的博客还有许多老牌供应商，如网易，新浪和搜狐博客等，有些可能已经不维护了，而且大多定位也不是技术类博客，这里就不介绍了。注册形式的博客当然还可以申请微信订阅号，或者在知乎、StackOverFlow或Quora等问答平台写以答案的形式，甚至百度贴吧搭楼也可以，**虽然是不正经的博客，但确是正经的写博客初衷**。

---


### 二) 静态网站生成技术
:wrench: **技术门槛： Markdown / Linux命令 / git / Github Pages / 域名解析**


:pill: **生成静态网站**。文章以特定的标头格式书写，放置在指定的文件夹，执行命令快速生成完整的静态网站；通过git将文件上传至[Github](https://github.com/)或[Coding](https://coding.net/)等代码托管平台，这些平台提供免费展示页面功能。

:pill: **快速搭建**。静态网站生成的博客很轻，可以绑定自己的域名，适合中小型项目快速建站，省去服务器费用、免去搭建配置服务器等的繁琐过程。官网文档都有详细的教程，配置好所需环境后，理论上搭建一个静态网站到上线只需要输入**10多行**命令，不熟悉的话一般**40分钟**左右就可以上线（熟悉的话**10分钟**），并且这些技术都有贴心的本地预览功能。当然，也正因为轻，没有数据库的支持，所以对于有多图和高清图片、大体量博客等需求实现起来不是非常友好。

:pill: **自定义程度高**。静态网站生成技术提供一系列可以配置CSS样式和修改网页行为的方式，有可供选择的大量插件，很容通过插件实现评论、搜索、分析等你想要的所有功能（标配并不带有这些功能）。

:pill: **主题丰富，高颜值**。静态网站的主题不是简单的皮肤，而是一个静态网站的解决方案，一般会内置插件并且提供许多实用场景的解决方案，如代码高亮、图像支持等等。

:pill: **技术更新迭代快**。静态网站升生成技术相关的讨论很活跃，因此更新维护及时，出现问题比较容易解决。反作用是因为更新换代非常快，而且官网提供各种技术间的快速迁移，所以如果入坑的话比较容易掉入深坑无法自拔，谨慎入坑。

目前比较流行的有[jekyll](http://jekyll.com.cn/)、[hugo](http://gohugo.io/)以及[hexo](https://hexo.io/zh-cn/)等方式，一般将网站搭在[Github Pages](https://pages.github.com/)或[Coding Pages](https://pages.coding.net/)上。通过生成网站搭建博客的方式相对来说有一点点繁琐，因为每次发布文章都需要重新生成，虽然操作很简单（当然可以配置自动化部署），但也是需要那么几步操作。推荐给喜欢新技术，喜欢自定义，不折腾不痛快的人。


#### 6) [hexo](https://hexo.io/zh-cn/) :+1::+1:

- 基于Node技术实现快速生成，Github代码库12k+
- 安装过程一路流畅，没有波折，配置、发布人性化，十分贴心
- 社区活跃，对技术不熟且英文不要的人非常友好
- :lipstick: [主题](https://hexo.io/themes/)155+，高颜值

<img src="https://ws2.sinaimg.cn/large/006tKfTcly1fkmsvpdp4pj31kw1lmb29.jpg" alt="hexo default" width="100%">

<img src="https://ws4.sinaimg.cn/large/006tKfTcly1fkmsw2sog9j31kw0trgqm.jpg" alt="hexo theme" width="100%">


#### 7) [hugo](http://gohugo.io/) :+1:

- 基于GO语言实现，极速生成网站，Github代码库11k+
- 安装配置十分流畅，但是在部署发布时遇到一点坎坷（需要了解一点Shell脚本
- 相对来说中文不是很友好，中文社区不是很活跃
- :lipstick: [主题](https://themes.gohugo.io/)670+，品位和颜值

<img src="https://ws1.sinaimg.cn/large/006tKfTcly1fkmt94x4ynj31kw0xznpe.jpg" alt="hugo default" width="100%">

<img src="https://ws2.sinaimg.cn/large/006tKfTcly1fkmt9h7d0nj31kw0t4gq7.jpg" alt="hugo theme" width="100%">


#### 8) [jekyll](http://jekyll.com.cn/)

- 基础Ruby实现，Github官方推荐亲儿子，Github代码库30k+
- 因为有后台，所以可以任性不依赖本地环境配置，直接在网站上生成
- 本地环境配置上有一些坑位，高级但是不友好（反正我是踩坑了
- :lipstick: [主题](http://jekyllthemes.org/)只能说正常，总有一种不是官方在维护皮肤的感觉

<img src="https://ws3.sinaimg.cn/large/006tKfTcly1fkmtptf7mlj31kw0t4tfb.jpg" alt="jekyll" width="100%">


- 以上的3种技术的配置流程和搭建思路大同小异，彼此之间都提供低成本迁移办法
- 如果害怕国外服务器大姨妈，以及对于搜索引擎收录有需求的话，建议搭在Coding Pages上，比较省心（会员等级不够高会有广告跳转，解决方式是主页上帮他作广告）
- 如果通过Github托管的话，另外推荐静态网站专业托管平台[Netlify](https://www.netlify.com/)，虽然自动编译还有很多坑位，但是可以自动插入HTML代码到post、免费实现https、SSL / TLS等功能、DNS解析等等

---

### 三) 内容管理系统

:wrench: **技术门槛：服务器 / 域名解析 / 数据库 / Linux命令 / ftp**

:pill: **后台管理**。具有贴心的后台界面，可以管理文章、相册、主题等。因为有数据库支持，所以可以实现多用户维护管理，高清大图上传等。

:pill: **高级还免费**。内置搜索、评论等常用功能，还有丰富的插件市场可以轻松满足各种需求。免费使用系统，但是配置服务器需要支付一定的费用（低配年费要大几百）。

:pill: **丰富与臃肿**。如今是用户体验当道和流行扁平化的时代，和往前大而多的需求不太一样，所以现在对于这种臃肿的博客系统是既爱又恨，爱他的丰富，又嫌弃人家的大脑袋。

:pill: **高门槛**。搭建一个后台管理式博客系统需要了解比较多的web知识，例如服务器，域名解析，数据库等知识都需要简单了解。虽然各大服务器商均有提供WordPress服务器镜像，可以实现**5分钟**快速搭建，但是如果不了解一些基本的web知识，会比较容易在搭建和使用过程中摸不着头脑。

#### 9) [WordPress](https://cn.wordpress.org/) :+1:

- 15岁高龄，现在是从php编写到开源后采用各种流行语言重写的第二春
- 市场占有率超高的内容管理系统，做博客只是功能之一，搭企业级网站也是很轻松
- 中文最友好了，服务器镜像5分钟搭建网站，一键包安装也是轻松带微笑
- :lipstick: [颜值](https://wordpress.org/themes)中上，形式非常丰富，可以适合各类工种的需求

<img src="https://ws2.sinaimg.cn/large/006tKfTcly1fkmvnqimqxj31kw21jnpe.jpg" alt="wordpress dafault" width="100%">

<img src="https://ws1.sinaimg.cn/large/006tKfTcly1fkmvnyk58oj31kw0uvqch.jpg" alt="wordpress console" width="100%">

<img src="https://ws2.sinaimg.cn/large/006tKfTcly1fkmvo26sgvj31kw16ojwh.jpg" alt="wordpress theme" width="100%">

#### 10) [ghost](https://ghost.org/)

- 基于Node实现的，社区活跃度高
- 相比WordPress去掉许多臃肿的功能，简洁大气
- 专为写作生产力的极致博客系统，WordPress良好替代品
- 有一定的搭建门槛，我用一键包也踩了很多坑位，花了**90分钟**才搭建完成
- :lipstick: [颜值](http://marketplace.ghost.org/)是所有例子中最高的，好评

<img src="https://ws3.sinaimg.cn/large/006tKfTcly1fkmw8q87sqj31kw0uzwje.jpg" alt="ghost default" width="100%">

<img src="https://ws1.sinaimg.cn/large/006tKfTcly1fkmw8svw13j31kw0t4wlq.jpg" alt="ghost console" width="100%">


内容管理系统博客虽然重，但是整体来看比较省心，一次配置完即可以在后台界面实现各种操作，虽然要花一些时间了解技术门槛知识、花点费用去配置服务器，但是一劳永逸（花钱的会比较用心维护是真的），推荐给有频繁更新、多人维护等需求的人。

---

## 最后说两句 :memo:

**新手村指南**。如果你是新手，对于以上的技术门槛一窍不通，但是又想要主题精美的个人博客网站，建议从[Markdown](https://daringfireball.net/projects/markdown/)语言开始学起（半天入门，一天出师），之后只需要了解一些基本的命令行知识和[git](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/)操作，就可以跟随各种教程，从生成静态网站入门快速搭建博客，完全不花钱。

**个人推荐**（良心推荐不收钱）

- :+1: **首推hexo**。性价比最高，中文友好，快速上线，贴心配置，免费高颜值
- :+1: **其次WordPress**。满足多人维护的需求，资料繁多等需求，可以一劳永逸，虽然门槛高一点，体量大了点，还要花钱，但是很稳定，很有安全感。
- 个人博客最终选择了**hugo + Gihub + Netlify**，可以丢鸡蛋 [onegee.space](http://onegee.space)
- 审美强迫症友情提示：hugo的颜值高于hexo，可以低成本无痛迁移；ghost颜值甩WordPress，为了美需要舍弃一些功能

:clap: **最后1毛钱，内容高于形式，入坑需谨慎 ：）**
