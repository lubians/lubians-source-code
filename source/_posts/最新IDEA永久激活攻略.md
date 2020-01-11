---
title: 最新IDEA永久激活攻略
date: 2020-01-08 21:37:04
tags: ['随笔','攻略','Java']
id: ideagonglve
---



### 前言

写这篇文章的原因是我最近想自己写两个项目,却发现自己的IDEA过期了,对,就是那个JAVA编辑器,于是研究了一下IDEA的激活.发现网上的攻略大多数不可用.

<!-- more -->

当然这里推荐大家去官网购买正版使用.下面是官网链接:

请点击https://www.jetbrains.com/idea/buy/

购买正版，谢谢合作学生凭学生证可免费申请正版授权 | 创业公司可5折购买正版授权
但又由于自己已经不是学生了,无法免费申请注册,好了,不找这么多理由了,其实主要原因呢,还是穷,不然我就买正版去了.
下面直接开始. 此攻略支持最新版2019.3版本IDEA的永久激活,向下兼容.

### 1.激活前的准备工作

如果在hosts里配置了jetbrains相关的项目,请移除

### 2.下载最新版破解补丁

**公众号后台回复关键词 IDEA 下载补丁文件 jetbrains-agent.jar** (在文末,或[传送门](https://lubians.github.io/2019/01/about/))
下载好之后将它放置到安装的IDEA目录下(位置可以随意放,这里主要是因为怕误操作删除了破解文件).
![](https://i.loli.net/2020/01/11/WstSfQiEmTyZHkD.png)
ps:如果文件失效,可以直接联系我,重新发链接.

### 3.进入项目界面

如果你之前已经使用过有效期激活可跳过此步骤,如果你和我一样是刚下载的IDEA,则需要点击激活窗口的"Evaluate for free"免费试用,然后再创建一个项目,这样就可以进入到IDEA的工作页面了.
![](https://i.loli.net/2020/01/11/QkyzlRS3EioGvAr.png)
![](https://i.loli.net/2020/01/11/O3bfgQHvwpGNDS9.png)
![](https://i.loli.net/2020/01/11/O9HUos2dVnwG3eE.png)
![](https://i.loli.net/2020/01/11/NEL17CQsrngkMiR.png)

什么?你不会基础配置IDEA,不会建项目?那你先学会再说,谢谢.

### 4.修改配置文件

进入到项目界面后,点击IDEA最上面的菜单栏中的"Help" --> "Edit Custom VM Options..." ,如果提示是否要创建文件,请点 "Create"
![](https://i.loli.net/2020/01/11/IefNySFk5M2HGcR.png)

在打开的vmoptions文件编辑窗口末行添加 :

```
-javaagent:你的破解补丁放置目录(大概率为你安装IDEA目录)\jetbrains-agent.jar
```

如下图:
![](https://i.loli.net/2020/01/11/3zjcZSe2K1YE7LU.png)

请仔细检查补丁路径是否正确，如果错误则会出现Idea打不开的情况，这时候可以删除用户配置目录下的Idea文件夹:windwos：
C:\Users\用户名

**本教程适用Windows、Mac、Ubuntu等所有平台.**

修改完配置文件,重启IDEA
修改完配置文件,重启IDEA
修改完配置文件,重启IDEA
重要的话说三遍

### 5.输入激活码

重启IDEA之后,点击菜单栏中的 "Help" --> "Register...",这里有三种激活方式:我们选择最后一种激活方式,为啥不用前面两种?说了没钱
言归正传:

选择最后一种License server激活方式，地址填入：[http://jetbrains-license-server](http://jetbrains-license-server/) （应该会自动填上），或者点击按钮：”Discover Server”来自动填充地址，完成激活
![](https://i.loli.net/2020/01/11/BQLaqeXDnHt4oMT.png)

### 6.查看有效期

激动人心的时刻来了,当你激活完毕后会出现两种可能,大概意思都是告诉你,兄弟,你的努力没有白费,终于白嫖了一回,你激活成功了.
![](https://i.loli.net/2020/01/11/5tYgiISBsWNJKjw.png)
![](https://i.loli.net/2020/01/11/PzmFYeKnRcabfNg.png)

服务器激活是永久的,以后再也不用担心......嗯哼?
![1920683-20200111133123417-639013409.png](https://i.loli.net/2020/01/11/I5rwpkDGJg1VBL8.png)

说点煽情的话好么?别走,就两句.

第一句:作为一个技术渣,资深IT民工,打算把自己代码传三代的码农一直玩世不恭,不务正业,在搞什么诗和远方,实在是舍本逐末,在某一日,天雷滚滚,好像我不清醒就要劈我一样,然后我就痛改前非,洗心革面,好好敲代码了,此篇福利先给诸多同行.

第二句:如果已经关注了这个号的人,看到我发这个文章,不要怀疑,你一定是看错了,我还是一个拥有诗和远方的好青年,如果没关注这个号的人,那还说什么,点关注呀,**本号长期关注大数据生态圈,会发一些相关的技术文章和大数据行业报道,主要还是技术.希望关注我的你和我一起进步.**

说两句就两句,绝不多哔哔.



**我是鲁边,2020 love and peace.**

我的个人微信公众号:鲁边社，欢迎关注

<img src="https://i.loli.net/2020/01/11/qrwfVFtR1SKD2bL.jpg" alt="avatar" width="300" />

