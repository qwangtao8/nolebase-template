---
uid: 20230817143255
title: 6- 期刊追踪：RSS 订阅
tags: [zotero]
description: 
author: windingwind,Ali
type: other
draft: false
editable: false
modified: 20230817190931
---

# 6- 期刊追踪：RSS 订阅

## 功能简介

> [!success] 最佳实践
> - 追踪期刊目录更新
> - 追踪数据库中某些【关键词】相关的文献更新情
> - 订阅任意网站的内容更新，例如 b 站 up 主的视频更新

## 1.Zotero 订阅设置

在 Zotero 主界面，左上角工具栏选择 **\=>新建订阅=>来自 URL 订阅**

![52e679130fe6e3e69af0059159b2afee_MD5](https://cdn.pkmer.cn/images/202308171540496.png!pkmer)

之后会弹出以下窗口，需要填入**URL，**zotero 识别成功之后会自动填入**标题（**可以自己手动更改）并且进行**高级设置，保存** 之后即可在主界面左侧**订阅**处看到订阅的内容及更新**。**

![bd0df2a5dc07b154194b42d78076fa7c_MD5](https://cdn.pkmer.cn/images/202308171540497.png!pkmer)

![a7141015a79d21db277a172abd4ced4e_MD5](https://cdn.pkmer.cn/images/202308171540498.png!pkmer)

### 1.1 URL 订阅

**“来自 URL”是最直接、最方便的添加 RSS 订阅的方式，只需要提供订阅源的链接即可，是我们用 zotero 追踪期刊更新时最常用的方式，以下涉及的实例也将基于此方式进行。**

### 1.2 OPML 订阅

“**来自 OPML**”主要用于之前有使用其它 RSS 阅读器，从其它阅读器中导入已经订阅的内容至 Zotero 中，一般用户不会使用此方式，故不过多介绍。

### 1.3 高级设置

![5e5ec40596937d45461596a82055f488_MD5](https://cdn.pkmer.cn/images/202308171540499.png!pkmer)

【更新订阅每**N**小时】，即设定订阅间隔，每**N**个小时从订阅 URL 爬取期刊目录，加载在该【订阅】界面。例如《社会学研究》为双月刊，建议从其发刊日时添加订阅，N 设定为 2X30X24 小时。如果 N 设置为 24，则每 24 小时会刷新一遍订阅，订阅界面会 24 小时加载一次期刊目录，导致期刊【订阅】界面出现重复文献条目。以下为【订阅】界面因为设置**订阅间隔 N**并不契合期刊更新间隔时出现的条目重复示例。

![816462ebf76a0c8dd67b8ed8e137ec66_MD5](https://cdn.pkmer.cn/images/202308171540500.png!pkmer)

> [!danger]  注意
> 订阅间隔设置不当导致的条目重复问题尚未完美的解决方案，只能根据期刊更新周期设定订阅间隔

【删除已读提要题目于之后 N 天】，即点击了该条目查看右侧的条目详细信息（zotero 会自动设置为“已读”状态）N 天后在期刊订阅界面删除该条目，如果不想删除已读条目，则将 N 设置为一个较大的数值，例如 1000000。

【删除未读提要条目于之后 N 天】，即该条目一直处于未点击查看该条目的具体信息，N 天后在期刊订阅界面删除该条目。如果不想删除未读条目，则将 N 设置为一个较大的数值，例如 1000000。

以上三项订阅参数的默认设置入口：

Win：**编辑=>首选项=>高级=>订阅**

Mac：**Zotero=>首选项=>高级=>订阅**

![f6073dd4f0e03307f2de430bd6ee394c_MD5](https://cdn.pkmer.cn/images/202308171540502.png!pkmer)

### 1.4 填入 URL 后不能自动识别与保存的解决方法

检查或更换网络，重启 zotero 后第一时间进入订阅填入 URL，能够自动识别并填充标题即可成功订阅；部分 URL 需要在科学网络的情况下才能识别成功，因此此时需要保证自己的网络足够科学。

## 2.中文期刊订阅——以知网为例

进入 [知网期刊导航界面](https://navi.cnki.net/knavi/journals/index?uniplatform=NZKPT)，在【搜索框 🔍】输入想要订阅的【中文期刊全称】，并点击【出版来源检索】

![7d670cd2f184e7017b2e13cb7f8c5769_MD5](https://cdn.pkmer.cn/images/202308171540503.png!pkmer)

在搜索结果界面，点击进入期刊页面

![f1566221004ef3b8d64812190559988d_MD5](https://cdn.pkmer.cn/images/202308171540504.png!pkmer)

在期刊主页左上角找到并点击【RSS 订阅】

![5ef8eb4e88ee9afe115413d0752a1032_MD5](https://cdn.pkmer.cn/images/202308171540505.png!pkmer)

复制浏览器地址栏中的 URL，进入 zotero

![5b31f48079ce31a8498d28fec6680c8c_MD5](https://cdn.pkmer.cn/images/202308171540506.png!pkmer)

在 Zotero 主界面，左上角工具栏选择 ![[Resource/Images/8eaf1075ad6e7d0388d8022378be4104_MD5.png]]**\=>新建订阅=>来自 URL 订阅，在弹出的界面填入 URL，自动识别好标题之后自己根据需要修改标题**（zotero 不会根据期刊订阅先后排序，可以手动在期刊名前面加上 1234 或者字母来排序），并且设置好订阅参数，点击【保存】，即可在左侧订阅界面看到该期刊的目录

![5e5ec40596937d45461596a82055f488_MD5](https://cdn.pkmer.cn/images/202308171540499.png!pkmer)

![5828615d2872e752040f488d88a138a8_MD5](https://cdn.pkmer.cn/images/202308171540508.png!pkmer)

## 3.英文期刊订阅——以 Annual Review of Psychology 为例

打开 [Annual Review of Psychology](https://www.annualreviews.org/journal/psych) 网页，找到右上角的 RSS feed![043db87586de71ebba4cba43f3481913_MD5](https://cdn.pkmer.cn/images/202308171540509.png!pkmer) 符号，点击打开

![6c394b00b840ac9746e6eb9d002274af_MD5](https://cdn.pkmer.cn/images/202308171540510.png!pkmer)

打开之后如下图示，**复制浏览器地址栏的 URL 链接**

![1817608b65e6e0ea8ae9fce9e52a9a82_MD5](https://cdn.pkmer.cn/images/202308171540511.png!pkmer)

在 Zotero 主界面，左上角工具栏选择 ![[Resource/Images/8eaf1075ad6e7d0388d8022378be4104_MD5.png]]**\=>新建订阅=>来自 URL 订阅，在弹出的窗口中把刚刚复制的链接粘贴到“URL”中，**zotero 会自动识别并填入标题（标题出来之后自己可以自定义修改）**，并参照本章 1.3 设置好高级选项**的内容，**点击保存**，即可在主界面**“订阅”** 处看到该期刊的最新期刊目录。

![63e200e934124703dd50f2c69bef5ce0_MD5](https://cdn.pkmer.cn/images/202308171540512.png!pkmer)

## 4.关键词订阅（PubMed 专属）

打开 [PubMed](https://pubmed.ncbi.nlm.nih.gov/) 官网，在搜索栏输入你想追踪的文献关键词，例如“heat wave”，点击搜索

![6bbc5f8b0e8e429b5164ca998824a347_MD5](https://cdn.pkmer.cn/images/202308171540513.png!pkmer)

如下图示，点击搜索框下面的**“Create RSS”，进入该关键词订阅的设置界面**

![9504a6ac3523a5ff0ae126bfc652c848_MD5](https://cdn.pkmer.cn/images/202308171540514.png!pkmer)

在设置界面，修改为合适“Number of items displayed”（追踪的文献条目数量），点击**“Create RSS”,生成“RSS Feed link”后点击 copy，将其在 zotero 订阅设置中填入，** 即可订阅追踪该关键词的相关文献进展。![51d51ced07392bd73eb9b251205922d3_MD5](https://cdn.pkmer.cn/images/202308171540515.png!pkmer)

## 5.配合 RSSHub Radar 订阅任意网站内容

以 b 站为例

### 5.1 RSSHub Radar 简介

RSSHub Radar 是 [RSSHub](https://www.appinn.com/rssbud-with-rsshub-for-ios/) 的衍生项目，用来快速发现当前网页的 RSS 地址，如果支持 RSSHub 则显示 RSSHub 地址，支持包括**Zotero**、 [Tiny Tiny RSS](https://www.appinn.com/tiny-tiny-rss/)、FreshRSS、Feedly、Inoreader 在内的 11 款阅读器一键订阅。

主要功能：

- 快速发现和订阅当前页面自带的 RSS
- 快速发现和订阅当前页面支持的 RSSHub
- 快速发现当前网站支持的 RSSHub
- 支持一键订阅 RSS 到 Tiny Tiny RSS、Miniflux、FreshRSS、Feedly、Inoreader、Feedbin、The Old Reader、Feeds.Pub、本地阅读器

一旦检测出 RSS 地址，RSSHub Radar 就会在角标上显示出数量。

**RSSHub Radar 浏览器插件下载与安装（含教程）：**[**Github 主页**](https://github.com/DIYgod/RSSHub-Radar)**、**[**Gitee 镜像主页**](https://gitee.com/mirrors/RSSHub-Radar)

### 5.2 RSSHub Radar 与 Zotero 联动

![0f018d4f0a79c4f58bca52dbd6494b28_MD5](https://cdn.pkmer.cn/images/202308171540516.png!pkmer)

打开你想关注的 UP 主（以 sharestuff 为例），点击浏览器右上角的 RSSHub Radar 插件图标

![6342efb70226f9526382c1241f07543d_MD5](https://cdn.pkmer.cn/images/202308171540517.png!pkmer)

选择所需要订阅的内容，点击**“复制”，进入 zotero 进行 URL 订阅** 即可

## 6.从“订阅”添加文献条目到“我的文库”/“群组”

![05a893bde58d3e7153b24445cc26483a_MD5](https://cdn.pkmer.cn/images/202308171540518.png!pkmer)

点开 zotero 某一期刊/RSS 订阅内容，点击具体条目，看到右侧的信息栏，**点击右侧信息栏的 ▽ 倒三角图标**，选择你想要保存到的本地文库文件夹 📂/在线群组文件夹 📂，再点击**“添加到 XXXX”**，即可从订阅中添加到自己的文献库中。![1bd11327f21a1f897aa898b459e4d071_MD5](https://cdn.pkmer.cn/images/202308171540519.png!pkmer)

下一篇 [[7_高级设置]]