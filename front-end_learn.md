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

| 标签名               | 定义       | 说明                                                       |
| -------------------- | ---------- | ---------------------------------------------------------- |
| `<html>` `</html>`   | HTML标签   | 页面中最大的标签,称为 根标签                               |
| `<head>` `</head>`   | 文档的头部 | 注意在`head`标签中必须设置的标签是`title`                  |
| `<title>` `</title>` | 文档的标题 | 让页面拥有一个属于自己的网页标题                           |
| `<body>` `</body>`   | 文档的主体 | 元素包含文档的所有内容 , 页面内容 基本都是放到`body`里面的 |

HTML 文档的后缀名必须是 `.html`或`.htm` , 浏览器的作用是读取 HTML 文档 , 并以网页的形式显示出它们。



##### 4.3.2 基本结构标签总结

<img src="https://raw.githubusercontent.com/sddfs2019/blogImags/main/web_front-end/202210142055834.png"  />

#### 4.4 网页开发工具

##### 4.4.1 VSCode 的使用

1. 双击打开软件。
2. 新建文件 (`Ctrl` + `N`)。
3. 保存 (`Ctrl` + `S`) , 注意要保存为 `.html` 文件。
4. `Ctrl` + `加号键` , `Ctrl` + `减号键` 可以放大缩小视图。
5. 生成页面骨架结构
   输入 `!` , 再按下 `Tab` 键。



##### 4.4.2 VsCode 工具生成骨架标签新增代码

1. `<!DOCTYPE>` 标签
2. `lang` 语言
3. `charset` 字符集



###### 4.4.2.1 文档类型声明标签

`<!	DOCTYPE>` 文档类型声明 , 作用就是告诉浏览器使用哪种 HTML 版本来显示网页。

```html
<!DOCTYPE html>
```

这句代码的意思是 : 当前页面采取的是 HTML5 版本来显示网页。

<b>注意 :</b>

1.  `<!DOCTYPE html>` 声明位于文档中的最前面的位置 , 处于 `<html>` 标签之前。
2. `<!DOCTYPE html>` 不是一个 HTML 标签 , 它就是文档类型声明标签。



###### 4.4.2.2 lang 语言种类

用来定义当前文档显示的语言。

1. `en` 定义语言为英语
2. `zh-CN` 定义语言为中文

简单来说 , 定义为 `en` 就是英文网页 , 定义为 `zh-CN` 就是中文网页
其实对于文档显示来说 , 定义成 `en` 的文档也可以显示中文 , 定义为 `zh-CN` 的文档也可以显示英文
这个属性对浏览器和搜索引擎(百度,谷歌等)还是有作用的



###### 4.4.2.3 字符集

字符集 (Character set) 是多个字符的集合。以便计算机能够识别和存储各种文字。

在 `<head>` 标签内 , 可以通过 `<meta>` 标签的 `charset` 属性来规定 HTML 文档应该使用哪种字符编码。

```html
<meta charset="UTF-8" />
```

`charset` 常用到的值有 : GB2312、BIG5、GBK 和 UTF-8 , 其中 UTF-8 也被称为万国码 , 基本包含了全世界所有国家需要用到的字符。

<font color=orange>注意 : 上面语法是必须要写的代码 , 否则可能引起乱码的情况。</font>一般情况下 , 统一使用 UTF-8 编码 , 尽量统一写成标准的 UTF-8 , 不要写成 utf8 或 UTF8。



###### 4.4.2.4 总结

1. 以上三个代码 VSCode 自动生成 , 基本不需要自己写。
2. `<!DOCTYPE html>` 文档类型的声明标签 , 告诉浏览器这个页面采取 HTML5 版本来显示页面。
3. `<html lang="en">` 告诉浏览器或者搜索引擎 , 这是一个英文网站 , 本页面采取英文来显示。
4. `<meta charset="UTF-8" />` 必须写 , 采取 UTF-8 来保存文字 , 如果不写就会乱码。
