# 前端学习

## HTML

### 1. 网页

#### 1.1 什么是网页

<font color=orange>网站</font>是指在因特网上根据一定的规则,使用`html`等制作的用于展示特定内容相关的网页集合。
<font color=orange>网页</font>是网站中的一"页",通常是`html`格式的文件,它要通过浏览器来阅读。
<font color=orange>网页是构成网站的基本元素</font>,它通常有图片、链接、文字、声音、视频等元素组成。通常我们看到的网页,常见以`.html`或`.html`后缀的文件,因此将其俗称为`html`文件。

#### 1.2 什么是 HTML

<font color=orange>HTML</font>指的是<font color=orange>超文本标记语言(Hyper Text Markup Language)</font>,它是用来描述网页的一种语言。
`html`不是一种编程语言,而是一种标记语言(markup language)。
标记语言是一套标记标签(markup tag)。

所谓超文本,有两层含义:

1. 它可以加入图片、声音、动画、多媒体等内容(超越了文本限制)。
2. 它还可以从一个文件跳转到另一个文件,与世界各地主机的文件连接(超级链接文本)。



#### 1.3 网页的形成

网页是由网页元素组成的,这些元素是利用`html`标签描述出来,然后通过浏览器解析来显示给用户的。

![](https://raw.githubusercontent.com/sddfs2019/blogImags/main/web_front-end/202210112151978.png)



#### 1.4 网页总结

网页是图片、链接、文字、声音、视频等元素组成,其实就是一个`html`文件(后缀名为`html`)
网页生成制作: 有前端人员书写`html`文件,然后浏览器打开,就能看到了网页。
HTML:超文本标记语言,用来制作网页的一门语言,由标签组成,比如 图片标签、链接标签、视频标签等...



### 2.常用浏览器

网页是通过浏览器来展示的,关于浏览器我们要介绍以下两点:

1. 常用的浏览器
2. 浏览器内核

#### 2.1 常用的浏览器

浏览器是网页显示、运行的平台。常用的浏览器有 IE、火狐(Firefox)、谷歌(Chrome)、Safari和Opera等。

![](https://raw.githubusercontent.com/sddfs2019/blogImags/main/web_front-end/202210132212246.png)

#### 2.4 浏览器内核

浏览器内核(渲染引擎) : 负责读取网页内容, 整理讯息 , 计算网页的显示方式并显示页面。

| 浏览器       | 内核    | 备注                                             |
| ------------ | ------- | ------------------------------------------------ |
| IE           | Trident | IE、猎豹安全、360极速浏览器、百度浏览器          |
| FireFox      | Gecko   | 火狐浏览器内核                                   |
| Safari       | Webkit  | 苹果浏览器内核                                   |
| Chrome/Opera | Blink   | Chrome/Opera 浏览器内核。Blink其实是WebKit的分支 |

目前国内一般浏览器都会采用Webkit/Blink内核,如360、UC、QQ、搜狗等。



### 3. Web 标准(重点)

<font color=orange>Web标准</font>是W3C组织和其他标准化组织指定的<font color=orange>一系列标准的集合</font>。W3C(万维网联盟)是国际最著名的标准化组织。

#### 3.1 为什么需要 Web 标准

浏览器不同,他们显示页面或者排版就有些许差异。

![](https://raw.githubusercontent.com/sddfs2019/blogImags/main/web_front-end/202210132236739.png)

遵循 Web 标准除了可以让不同的开发人员写出的页面更标准、更统一外，还有以下优点 :

1. 让 Web 的发展前景更广阔
2. 内容能被更广泛的设备访问
3. 更容易被搜索引擎搜索
4. 降低网站流量费用
5. 使网站更易于维护
6. 提高页面浏览速度



#### 3.2 Web 标准的构成

主要包括<font color=orange>机构(Structure)、表现(Presentation)</font>和<font color=orange>行为(Behavior)</font>三个方面。

| 标准 | 说明                                                         |
| ---- | ------------------------------------------------------------ |
| 结构 | 结构用于对网页元素进行整理和分类,现阶段主要学的是`html`      |
| 表现 | 表现用于设置网页元素的版式、颜色、大小等外观样式，主要指的是`css` |
| 行为 | 行为是指网页模型的定义及交互的编写，现阶段主要学的是`javascript` |

Web 标准提出的最佳体验方案 : <font color=orange>结构、样式、行为相分离</font>。
简单理解 : <font color=orange>结构写到 html 文件中 , 表现写到 css 文件中 , 行为写到 javascript 文件中</font>。

![](https://raw.githubusercontent.com/sddfs2019/blogImags/main/web_front-end/202210132304094.png)

结构类似身体 , 表现类似外观装饰 , 行为类似行为动作 , 相比较而言 , 三者中结构最重要。



### 4. HTML 标签

#### 4.1 基本语法概述

1. HTML标签是由<font color=orange>尖括号包围的关键字</font> , 例如 `<html>`。
2. HTML标签<font color=orange>通常是成对出现的</font> , 例如 `<html>` 和 `</html>` , 我们称为<font color=orange>双标签</font>。标签对中的第一个标签是开始标签 , 第二个标签是结束标签。
3. 有些特殊的标签必须是单个标签(极少情况) , 例如 `<br />` , 我们称为<font color=orange>单标签</font>。



#### 4.2 标签关系

双标签关系可以分为两类 : <font color=orange>包含关系</font>和<font color=orange>并列关系</font>。

<font color=red><b>包含关系</b></font>

```html
<head>
    <title> </title>
</head>
```

![](https://raw.githubusercontent.com/sddfs2019/blogImags/main/web_front-end/202210132330890.png)



<font color=red><b>并列关系</b></font>

```html
<head> </head>
<body> </body>
```

![](https://raw.githubusercontent.com/sddfs2019/blogImags/main/web_front-end/202210132332950.png)



#### 4.3 HTML 基本结构标签

##### 4.3.1 第一个 HTML 网页

每个网页都会有一个基本的结构标签(也称为骨架标签) , 页面内容也是在这些基本标签上书写。
HTML 页面也称为 HTML 文档。

```html
<html>
    <head>
        <title>我的第一个页面</title>
    </head>
    <body>
        hello,world
    </body>
</html>
```

