# 关于本站

====================================
+ 此站点为wangxch的博客网站，更多内容请访问我的[GIS网站](https://www.qhftdx.cn/)，[GIS数据共享](https://www.qhftdx.cn/)
+ 此站点更多的发表一些个人写的文章，因为我是个热爱开源，热爱折腾的GIS全栈软件工程师。
+ 此站点所有资源你可以免费下载使用，但不得用于商业用途。
+ 此站点是从[LessOrMore](https://github.com/luoyan35714/LessOrMore.git)主页下载并进行修改而成，你也可以尝试下载使用。

使用
====================================

下载
------------------------------------

使用git从[LessOrMore](https://github.com/luoyan35714/LessOrMore.git)主页下载项目

``` bash
git clone https://github.com/luoyan35714/LessOrMore.git
```

配置
------------------------------------

`LessOrMore`项目需要配置的只有一个文件`_config.yml`，打开之后按照如下进行配置。

> 特别注意`baseurl`的配置。如果是`***.github.io`项目，不修改为空''的话，会导致JS,CSS等静态资源无法找到的错误

``` bash
name: 博客名称
email: 邮箱地址
author: 作者名
url: 个人网站
# baseurl修改为项目名，如果项目是'***.github.io'，则设置为空''
baseurl: "/LessOrMore"
resume_site: 个人简历网站
github: github地址
github_username: github用户名称
# 请到百度统计官网[https://tongji.baidu.com/](https://tongji.baidu.com/)申请自己的网站ID并在此处替换，否则将无法正常统计访问量
baidu_analysis: 94be4b0f9fc5d94cc0d0415ea6761ae9
# 请到revolvermaps [http://www.revolvermaps.com/?target=setupgl](http://www.revolvermaps.com/?target=setupgl)申请自己的网站ID并在此处替换，否则将无法正常统计访问量
revolvermaps: 5ytn1ssq6za
```

关于统计
------------------------------------

本项目支持三种统计，分别是

+ [百度统计](https://tongji.baidu.com)

百度统计是后台统计，并没有再页面有任何展示，但是可以通过登录百度统计官网查看更详细的访问记录分析。
当Fork本项目之后需要去百度统计官网申请自己的baidu统计ID替换 `_config.yml` 文件中的 `baidu_analysis`。

+ [revolvermaps地图统计](http://www.revolvermaps.com/)

revolvermaps地图统计是展示在左侧当行栏的地图展示，具体展示形式可以去官网定制。
当Fork本项目之后需要去revolvermaps地图官网申请自己的统计ID， 替换`_config.yml` 文件中的 `revolvermaps`。

+ [不蒜子统计](http://busuanzi.ibruce.info/)

不蒜子统计是出现在页面右上角的`本站总访问量n次`统计，本统计会自动识别客户所对应的域名，根据不同域名统计，所以并不需要Fork本项目者做任何修改。
更多不蒜子的展示方式可以去官网查看。


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

执行
------------------------------------

``` bash
jekyll server
```

效果
------------------------------------
打开浏览器并输入URL`http://localhost:4000/`,回车。


关于作者
====================================

热爱开源，热爱折腾的Java程序猿。更多个人信息和联系方式可以参照[GIS数据共享](https://www.qhftdx.cn/)。

写在最后
====================================

可能会有人问我为什么[GIS数据共享](https://www.qhftdx.cn/)网站里面已经发布博客，在这里还要发布：
+    1）[GIS数据共享](https://www.qhftdx.cn/)是我个人网站，同时也为我的亲朋好友们提供一些服务，因为买的云服务器，性能并不好；
+    2）因为我是个热爱编程的程序猿，我开发过无数个新闻列表、新闻详情页，通过后台我很快能够编辑一篇文章，但是那会将我限定在我的富文本编辑器里面，并不能让我随心所以的编写文档；
+    3）喜欢开源、喜欢探索、喜欢别人对我说我这儿那儿写的不好。在这里只要不是用于商业用途，你可以在这里你可以查看和下载我的源码。
+    4）在自己服务器部署的程序只能看见View（视图界面），无法拿来共享；
+    5）github下写的文章我单独解析为xml格式，至于什么用途我还不知道，就是喜欢瞎折腾；
+    6）如果你想问为什么不全部开源，那是因为复杂站点无法在GitHub托管，我在其他网站上设置的账户名密码什么的也不能直接公布在此处，毕竟GitHub在全球有互联网的地方就可以访问。

如果你也像我一样在寻觅一个简洁的博客主题。不妨试下LessOrMore。

之前此处是有打赏功能的，不过最近在整理自己，发现打赏功能偏离了我写这个Jekyll主题的初衷，所以删除了打赏功能。

非常感谢之前打赏过的朋友们！！