> 下文为[半撇私塾](www.bpteach.com)翻译自[adam-p](https://github.com/adam-p/) 的[Markdown 小抄表](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)，发布与Github [Markdown Cheetsheet]。


##### 目录  
[标题](#headers)  
[强调](#emphasis)  
[列表](#lists)  
[超链接](#links)  
[图片](#images)  
[代码块](#code)  
[表格](#tables)  
[引用块](#blockquotes)  
[行内 HTML](#html)  
[分隔符](#hr)  
[断行](#lines)  

<a name="headers"/>
## 标题

```no-highlight
# H1
## H2
### H3
#### H4
##### H5
###### H6

你也可以使用下划线的方式标记H1 与H2：

Alt-H1
======

Alt-H2
------
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

你也可以使用下划线的方式标记H1 与H2：

Alt-H1
======

Alt-H2
------

<a name="emphasis"/>
## 重点

```no-highlight
重点，又被称为斜体，在两边加上*星号* 或是_下划线_ 。

更强的重点，又称为粗体，在两边加上**两个星号** 或是__两个下划线__ 。

也可以用**星号与_下划线_** 结合重点。

删除线使用两个波浪符号。~~删除这个。~~
```

重点，又被称为斜体，在两边加上*星号* 或是_下划线_ 。

更强的重点，又称为粗体，在两边加上**两个星号** 或是__两个下划线__ 。

也可以用**星号与_下划线_** 结合重点。

删除线使用两个波浪符号。~~删除这个。~~


<a name="lists"/>
## 列表

（在这个例子里，前置与后面的空白以点的方式显示：⋅）
(In this example, leading and trailing spaces are shown with with dots: ⋅)

```no-highlight
1. 第一个有序列表项目
2. 另一个项目
⋅⋅* 无序子列表 
1. 实际数字不重要，只要它是一个数字
⋅⋅1. 有序子列表
4. 与其他项目

⋅⋅⋅要在列表项目下加入段落，只要缩进就好了。注意前面的空白行，以及前置的空白（至少要一个空白，不过我们在这里会使用三个空白以刚好对齐原始的文字）。

⋅⋅⋅要使文字段行而不会成为新的段落，你只需要在后面加上两个空白。⋅⋅
⋅⋅⋅注意这行已经分开了，不过还是在同样的段落中。
⋅⋅⋅（如果不要求后面的两个空格，就为伴了典型的GFM 断行格式。）

* 无序列表可以使用星号
- 或减号
+ 或加号
```

1. 第一个有序列表项目
2. 另一个项目
  * 无序子列表 
3. 实际数字不重要，只要它是一个数字
  1. 有序子列表
4. 与其他项目

   要在列表项目下加入段落，只要缩进就好了。注意前面的空白行，以及前置的空白（至少要一个空白，不过我们在这里会使用三个空白以刚好对齐原始的文字）。

   要使文字段行而不会成为新的段落，你只需要在后面加上两个空白。  
   注意这行已经分开了，不过还是在同样的段落中。
   （如果不要求后面的两个空格，就为伴了典型的GFM 断行格式。）

* 无序列表可以使用星号
- 或减号
+ 或加号

<a name="links"/>
## 超链接

有两个方法可以建立超链接

```no-highlight
[这是一个行内样式的超链接](https://www.google.com)

[这是一个加上标题的行内样式超链接](https://www.google.com "Google 的首页")

[这是一个引用样式的超链接][任意不区分大小写的文字]

[以相对的文件路径引用其他文件](../blob/master/LICENSE)

[可以用数字来宣告一个引用样式的超链接][1]

或让他空白并使用[超链接文字本身]。

网址，或是尖括号中的网址会自动转换成超链接。
http://www.example.com 或<http://www.example.com> 甚至有时候example.com 也可以（只是举例，Github上无效）。

引用超链接可以在一些文字后面。

[任意不区分大小写的文字]: https://www.mozilla.org
[1]: http://slashdot.org
[超链接文字本身]: http://www.reddit.com
```

[这是一个行内样式的超链接](https://www.google.com)

[这是一个加上标题的行内样式超链接](https://www.google.com "Google 的首页")

[这是一个引用样式的超链接][任意不区分大小写的文字]

[以相对的文件路径引用其他文件](../blob/master/LICENSE)

[可以用数字来宣告一个引用样式的超链接][1]

或让他空白并使用[超链接文字本身]。

网址，或是尖括号中的网址会自动转换成超链接。
http://www.example.com 或<http://www.example.com> 甚至有时候example.com 也可以（只是举例，Github上无效）。

引用超链接可以在一些文字后面。

[任意不区分大小写的文字]: https://www.mozilla.org
[1]: http://slashdot.org
[超链接文字本身]: http://www.reddit.com

<a name="images"/>
## 图片
```no-highlight
这是我们的Logo（把鼠标指向Logo 可以看到标题文字）

行内样式：
![alt 文字](https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon48.png "Logo 标题文字1")

引用样式: 
![alt 文字][logo]

[logo]: https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon48.png "Logo 标题文字2"
```

这是我们的Logo（把鼠标指向Logo 可以看到标题文字）

行内样式：
![alt 文字](https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon48.png "Logo 标题文字1")

引用样式: 
![alt 文字][logo]

[logo]: https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon48.png "Logo 标题文字2"

<a name="code"/>

## 代码与语法高亮

代码区块是Markdown 规格的一部分，不过语法高亮不是。无论如何，许多渲染器──如Github 和*Markdown Here* ──支援语法高亮。每个渲染器支援的程式语言，以及程式语言的名字写法都不一样。*Markdown Here* 支援几十种语言（以及不一定是真的程式语言，像d​​iffs 与HTTP headers）的语法高亮；要看完整的列表，以及语言的名称，请见[highlight.js 的示范页](http://softwaremaniacs.org/media/soft/highlight/test.html)。


```no-highlight
行内的`代码` 用`反引号` 包围起来。
Inline `code` has `back-ticks around` it.
```

行内的`代码` 用`反引号` 包围起来。

代码区块可以用只有三个反引号<code>```</code>的一行围起来，或是以四个空格缩排。我建议用三个反引号的方式围起来── 这比较简单，而且只有这个方式支援语法高亮。

<pre lang="no-highlight"><code>```javascript
var s = "JavaScript 语法高亮";
alert(s);
```
 
​```python
s = "Python 语法高亮"
print s
```

```
没有指定程式语言，所以没有语法高亮。
不过，我们可以放进一个<b>标签</b>。
```
</code></pre>



```javascript
var s = "JavaScript 语法高亮";
alert(s);
```

```python
s = "Python 语法高亮"
print s
```

```
没有指定程式语言，所以Markdown Here 没有语法高亮（在Github 上可能不一样）。
不过，我们可以放进一个<b>标签</b>。
```


<a name="tables"/>
## 表格

Markdown 的核心标准没有表格，不过表格是GFM 的一部分，而且*Markdown Here* 支援表格。这是在电子邮件中加入表格的好方法－ 本来是需要从其他应用程式复制贴上的工作。

```no-highlight
冒号可以用来标示栏位的对齐方式。

| Tables | Are | Cool |
| ------------- |:-------------:| -----:|
| 第三栏| 靠右对齐| $1600 |
| 第二栏| 置中对齐| $12 |
| 斑马条纹| 是整齐的| $1 |

每个标头元件都要用至少三个破折号分隔开来。
最外面的竖线可以省略，你也不需要让原始的文字排列整齐。你也可以使用行内样式的Markdown。

不| 漂亮| 的文字
--- | --- | ---
*依然* | `渲染的` | **很好**
1 | 2 | 3
```

冒号可以用来标示栏位的对齐方式。

| Tables | Are  |  Cool |
| ------ | :--: | ----: |
| 第三栏    | 靠右对齐 | $1600 |
| 第二栏    | 置中对齐 |   $12 |
| 斑马条纹   | 是整齐的 |    $1 |

每个标头元件都要用至少三个破折号分隔开来。
最外面的竖线可以省略，你也不需要让原始的文字排列整齐。你也可以使用行内样式的Markdown。

| 不    | 漂亮    | 的文字    |
| ---- | ----- | ------ |
| *依然* | `渲染的` | **很好** |
| 1    | 2     | 3      |

<a name="blockquotes"/>
## 引用文字

```no-highlight
> 在电子邮件中，引用文字可以很方便的模拟回应的文字。
> 这行也在同样的引用区块。

引用区块结束

> 就算这行很长，只要包裹的好，依然可以很好的被引用。哦，我们继续写以保证每个人都确实的被包在里面。喔，你也可以在引用文字中*放入* 其他**Markdown** 语法。
```

> 在电子邮件中，引用文字可以很方便的模拟回应的文字。
> 这行也在同样的引用区块。

引用区块结束

> 就算这行很长，只要包裹的好，依然可以很好的被引用。哦，我们继续写以保证每个人都确实的被包在里面。喔，你也可以在引用文字中*放入* 其他**Markdown** 语法。

<a name="html"/>
## 行内HTML

你也可以在Markdown 里面撰写原始的HTML，这些HTML 一样大多数运作的很好。

```no-highlight
<dl>
  <dt>定义列表</dt>
  <dd>有时候，人们偶尔会用到。</dd>

  <dt>在HTML 中撰写Markdown</dt>
  <dd>*无法* 运作的**非常** 好。改用HTML<em>标签</em>。</dd>
</dl>
```

<dl>
  <dt>定义列表</dt>
  <dd>有时候，人们偶尔会用到。</dd>

  <dt>在HTML 中撰写Markdown</dt>
  <dd>*无法* 运作的**非常** 好。改用HTML<em>标签</em>。</dd>
</dl>

<a name="hr"/>
## 水平线

```
三个或更多个……

---

连字符

***

星号

___

下划线
```

三个或更多个……

---

连字符

***

星号

___

下划线

<a name="lines"/>
## 断行

如果你想要学习断行如何运作，我基本上建议最好就是实验看看── 按<Enter>一下（也就是，插入一个换行符号），接着再按一次(也就是，插入两个换行符号)，看看会发生什么。你很快就会得到你想要的。「Markdown Toggle」是你的好朋友。

你可以试试看这里的一些方式：

```
我们从这一行开始。

两个换行符号分开了这行和前面那一行，所以这会变成**分开的段落** 。

这行也是个分开的段落，不过……
只有一个换行符号分开这行，所以这是*同段落* 中的分开两行。
```

我们从这一行开始。

两个换行符号分开了这行和前面那一行，所以这会变成**分开的段落** 。

这行也是个分开的段落，不过……
只有一个换行符号分开这行，所以这是*同段落* 中的分开两行。

（技术提示: *Markdown Here* 使用GFM 的换行，所以不用使用Markdown 原先的两个空格换行法。）



---

License: [CC-BY](https://creativecommons.org/licenses/by/3.0/)

翻译自[adam-p](https://github.com/adam-p/) 的[wiki](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)