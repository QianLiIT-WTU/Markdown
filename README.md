# MarkDown

---
**Author：EasterFan**

---


# 目录


## markdown语法
- 语法一
  - [标题](README.md#标题)
  - [段落](README.md#段落)
  - [强调](README.md#强调)
  - [列表](README.md#列表)

- 语法二
  - [链接](README.md#链接)
  - [图片](README.md#图片)
  - [引用](README.md#引用)
  - [代码块](README.md#代码块)

- 语法三
  - [表格](README.md#表格)
  - [水平分割线](README.md#水平分割线)
  - [HTML语法](README.md#HTML语法)
  - [GFM](README.md#GFM)
  - [表情符号](README.md#表情符号)

- 语法四
  - [混合强调样式](README.md#混合强调样式)
  - [图片链接](README.md#图片链接)
  - [有序表的打断与连接](README.md#有序表的打断与连接)

## markdown工具
- [Windows 平台](README.md#Windows平台)
- [Linux 平台](README.md#Linux平台)
- [Mac 平台](README.md#Mac平台)
- [在线编辑器](README.md#在线编辑器)
- [浏览器插件](README.md#浏览器插件)
- [高级应用](README.md#高级应用)




## 其他资料
- [码字必备：18 款优秀的 Markdown 写作工具 | 2015 年度盘点](https://sspai.com/post/32483)
- [简洁与强大，从不是矛盾的事物：写作工具 MarkEditor 功能详解](http://sspai.com/34317)
- [不止是一款简单的码字工具：MarkEditor 进阶功能介绍](http://sspai.com/34656)



---

# 标题
有n个“#”，就是n级标题
```
# 标题1
## 标题2
### 标题3
#### 标题4
##### 标题5
###### 标题6
```

# 段落
正常打字出来的都是段落正文
两个段落之间换行-----**两个空格**

# 强调

我是*斜体*文字样式
我是**粗体**文字样式
我是***加粗倾斜***样式

我是~~删除文字样式~~

# 列表

### 无序列表
- 季节
  - 春
  - 夏
  - 秋
  - 冬（只要在开头加**两个空格**）
- 年代

### 有序列表

1. 基本数据类型
  1. 整型
  2. 字符型
  3. 浮点
  4. 逻辑 （只要在开头加**两个空格**）

# 链接
### 内嵌式链接
  - 外部链接
   [百度](http://www.baidu.com)
  - 内部链接
    - 链接仓库的其他文件[demo1](Demo1.md)
    - 链接本文档的其他部分[代码块](Demo2.md#代码块)

### 引用式链接
- 外部链接
   [百度]
  - 内部链接
    - 链接仓库的其他文件[markdown]
    - 链接本文档的其他部分[代码块]

# 图片

- 外部图片
  ![alt](url text)
  ![my github avatar](https://ss3.bdstatic.com/70cFv8Sh_Q1YnxGkpoWK1HF6hhy/it/u=3025836231,1085548956&fm=26&gp=0.jpg "我的github图标")
 - 内部图片
 ![alt](url text)
  ![谭咏麟](image/photo.jpg "谭咏麟")

- 图片的引用式链接
  - ![my github avatar]
  - ![谭咏麟]

# 引用
- 单重引用
> 我常以为是丑女造就了美人。我常以为是愚氓举出了智者。我常以为是懦夫衬照了英雄。我常以为是众生度化了佛祖。                                                                                                                      《我与地坛》


- 多重引用
>>> 这是一个多重引文


# 代码块

- 行内代码

这个代码用来声明变量是`var = a`,用来打印变量函数是`console.log(a)`;

- 块式代码

```javascript
var a = 10;
console.log(a);

```

# 水平分割线

水平分割线三个横杠（横杠与文字有一个空行）
---

三个星号
***

三个下划线
___

# HTML代码

- 让文字居中
<p align = "center">Hello world!</p>

- 注释文字
<!--
这些文字不会显示在markdown中
-->

# 表格

<!--表格默认左对齐，这一行通过: 控制左右对齐-->

| 这     | 是      | 表    | 头     |
| ----|:----:|-----|----:|
|row1 |row2  |row3 | row4|
|**加粗**|[baidu](http://www.baidu.com)|ajhdfjk|![表格图片](images/photo.jpg "谭咏麟" )|

```
| 这     | 是      | 表    | 头     |
| ----|:----:|-----|----:|
|row1 |row2  |row3 | row4|
|**加粗**|[baidu](http://www.baidu.com)|ajhdfjk|![表格图片](images/photo.jpg "谭咏麟" )|
```
# GFM
github flvored markdown

 ## task list (任务列表)
 - [x] task1
 - [ ] task2
 - [ ] task3

 # 表情符号
    :emoji code:


[github表情符号码官网](http://www.emoji-cheat-sheet.com)
或者在[这里](emoji.md)
:last_quarter_moon_with_face::first_quarter_moon_with_face:


# 混合强调样式

基本强调样式

- *倾斜*
- **加粗**
- ~~删除~~

混合强调样式

- ***加粗倾斜***
- **~~加粗删除~~**
- *~~倾斜删除~~*


# 图片链接

基本文字链接

    [链接文字](URL)

    [baidu](http://www.baidu.com)

基本图片

    ![alt](url text)

![谭咏麟](images/photo.jpg "谭咏麟")

图片链接
    [![alt](url text)](URL)

[![谭咏麟](images/photo.jpg "谭咏麟")](http://www.baidu.com)

# 有序列表的打断与连接

- 问题一：多级列表打断------空行不行，用文字打断
- 问题二：多级列表连接------将文字段落缩进四格

1. item1
  1. item1.1
  2. item1.2

2. item2
  1. item2.1
  2. item2.2

这段文字用来打断2和3，重新编号


3. item3
  1. item3.1
  2. item3.2

---

1. item1
  1. item1.1
  2. item1.2

2. item2
  1. item2.1
  2. item2.2

    这段文字用来缩进4格，不会打断2和3


3. item3
  1. item3.1
  2. item3.2




# Windows平台

- [MarkdownPad](http://markdownpad.com/)
- [MarkPad](http://code52.org/DownmarkerWPF/)
# Linux平台

- [ReText](https://sourceforge.net/p/retext/home/ReText/)
# Mac平台

- [Mou](http://25.io/mou/)
# 在线编辑器

- [Markable.in](https://markable.in/)
- [Dillinger.io](http://dillinger.io/)
# 浏览器插件

- MaDe (Chrome)
# 高级应用

- [Sublime Text 2](http://www.sublimetext.com/2) + [MarkdownEditing / 教程](http://ttscoff.github.io/MarkdownEditing/)




# 参考资源

- [xirong](https://github.com/xirong/my-markdown)
- [guodongxiaren](https://github.com/guodongxiaren/README)









<!--下面是本文所用到的链接-->
[百度]: http://baidu.com
[markdown]: README.md
[代码块]: README.md#代码块
[谭咏麟]: image/photo.jpg "谭咏麟"
[my github avatar]: https://ss3.bdstatic.com/70cFv8Sh_Q1YnxGkpoWK1HF6hhy/it/u=3025836231,1085548956&fm=26&gp=0.jpg "我的github图标"
