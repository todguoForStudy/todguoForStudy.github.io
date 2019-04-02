# LessOrMore


致谢
====================================
+ 感谢[Less官网](http://lesscss.cn/)的样式，本Jekyll框架的样式都是基于Less官网的样式直接拷贝过来的。只是重构了JS，并且加入了Jekyll语法而已。
+ 感谢[Github](https://github.com/)提供的代码维护和发布平台
+ 感谢[Jekyll](https://jekyllrb.com/)团队做出如此优秀的产品
+ 感谢[Freud Kang](https://github.com/luoyan35714/LessOrMore)提供的Jekyll版本，因为之前就有建个人首页的仓库，就没选择fork的方式，而是直接clone再弄过来到这个项目。
+ 关于原作者：更多个人信息和联系方式可以参照[他的简介](http://www.hifreud.com/Resume.io/)。


------------------------------------

本项目支持三种统计，分别是

+ [百度统计](https://tongji.baidu.com)

百度统计是后台统计，并没有再页面有任何展示，但是可以通过登录百度统计官网查看更详细的访问记录分析。
当Fork本项目之后需要去百度统计官网申请自己的baidu统计ID替换 `_config.yml` 文件中的 `baidu_analysis`。

+ [revolvermaps地图统计](http://www.revolvermaps.com/)

revolvermaps地图统计是展示在左侧当行栏的地图展示，具体展示形式可以去官网定制。
当Fork本项目之后需要去revolvermaps地图官网申请自己的统计ID， 替换`_config.yml` 文件中的 `revolvermaps`。


如何写文章
------------------------------------

在`LessOrMore/_posts`目录下新建一个文件，可以创建文件夹并在文件夹中添加文件，方便维护。在新建文件中粘贴如下信息，并修改以下的`titile`,`date`,`categories`,`tag`的相关信息，添加`* content {:toc}`为目录相关信息，在进行正文书写前需要在目录和正文之间输入至少2行空行。然后按照正常的Markdown语法书写正文。

``` bash
---
layout: post
#标题配置
title:  标题
#时间配置
date:   2016-08-27 01:08:00 +0800
#大类配置
categories: document
#小类配置
tag: 教程
---

* content
{:toc}


我是正文。我是正文。我是正文。我是正文。我是正文。我是正文。
```
