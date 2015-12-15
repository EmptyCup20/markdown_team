#目录结构：
[toc]
#**<i class="icon-sun"></i>Markdown简介**

- Markdown由[__StackEdit__](http://www.baidu.com)修改而来，一种轻量级标记语言，创始人为 John Gruber 和 Aaron Swartz。允许人们“使用易读易写的纯文本格式编写文档，然后转换成有效的 XHTML/HTML 文档”。

- OSC、CSDN、 Github、Wordpress、简书等都支持Markdown书写。 Markdown已逐渐成为事实上的网络写作规范。

- **专注内容、专注写作**，不让格式操作影响文章写作，适用于网络的书写语言，轻松完成文章写作。 可以轻松转换成html格式、pdf格式。

#**<i class="icon-sun"></i>Markdown的宗旨**
>**目标：**易读易写
>
>**语法的目标：**成为一种适用于网络的书写语言。
>
>**理念：**让文档更容易读、写和随意改。
>
>**Markdown和HTML不同：** HTML 是一种发布的格式，Markdown 是一种书写的格式。不在 Markdown 涵盖范围之内的标签，都可以直接在文档里面用 HTML 撰写。Markdown 允许 兼容 HTML。

#**<i class="icon-sun"></i>Markdown的优劣**
#**Markdown的优势**
>1. 实时预览
>1. 同步滚动
>1. 导入导出MD文件
>1. 支持离线写作
>1. 几乎全程的键盘操作、操作快捷键
>1. 语法简单，容易学习，格式简洁大方，可读性强。
>1. 兼容性强
>1. 格式转换方便 
>1. 功能强大(兼容html语法、特殊字符自动转换、轻松绘制表格、公式、流程图等。）
>>***操作快捷键***
>>
>加粗 `Ctrl + B` &ensp;&emsp; &emsp; &emsp; &emsp; 斜体 `Ctrl + I`
引用 `Ctrl + Q`	&ensp;&emsp; &emsp; &emsp; &emsp;	插入链接 `Ctrl + L`
插入代码 `Ctrl + K`&emsp; &emsp; &emsp;插入图片` Ctrl + G`
提升标题 `Ctrl + H`	&emsp; &emsp; &emsp;有序列表 `Ctrl + O`
无序列表 `Ctrl + U`	&ensp;&ensp; &emsp; &emsp;横线 `Ctrl + R`
撤销 `Ctrl + Z`&ensp; &ensp;&emsp; &emsp; &emsp; &emsp;重做 `Ctrl + Y` 

#**Markdown的劣势**

+ **格式难于自定义 **

	Markdown更加关注内容、更加关注写作本身，在格式自定义方面有所欠缺

+ **需要额外编译器** 

	浏览器不会默认编译Markdown，需要额外的编译器进行编译。

#**<i class="icon-sun"></i>Markdown的编辑工具**

* **客户端**
	1. Windows 平台
		MarkdownPad、MarkPad
	1. Linux 平台
		ReText
	1. Mac 平台
		Mou

* **在线编辑工具**
		Markable、Dillinger.io、markable、***stackedit***等
		
----

#**<i class="icon-sun"></i>Markdown语法**

##<i class="icon-tint"></i>**标题:**

###语法：
     1.Setext ：以底线  = （最高阶标题）和 - （第二阶标题）表示
     2.atx ：在行首插入 1 到 6 个 # ，对应 1 到 6 阶标题
###例子：

1级标题底线例子
=====
2级标题底线例子
-------
# 1级标题#号例子
##2级标题#号例子

##<i class="icon-tint"></i>**段落:**

###语法：
>段落是由一个以上的连接的行句组成，而一个以上的空行则会划分出不同的段落；2个空格+回车等于html的`<br />`
>
>**Tip：**首行缩进（&ensp;为1个空格，&emsp;为2个空格）

###例子：
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;段落例子段落例子段落例子段落例子段落例子段落例子段落例子**段落例子段落例子**段落例子***段落例子***段落例子段落例子段落例子段落例子段落例子段落例子段落例子段落例子段落例子段落例子段落例子段落例子段落例子段落例子段落例子。
&emsp;&emsp;段落例子<i class="icon-money">**Money图标**</i>段落例子<i class="icon-file"></i>**段落例子**段落例子段落例子段落例子段落例子

##<i class="icon-tint"></i>**引文或区块引用**
###语法：
在引用的文字之前添加`>`标记。引用段落时只在整个段落的第一行最前面加	上 `>`。引用里面可以使用强调、链接等其他语法。

     1.email：以`>`标识。区块间可嵌套标题、列表、代码 、区块等     
     2.缩进 4 个空格或是 1 个制表符
>**Tip:**引用可以嵌套，使用不同数量的`>`表示层次

###例子：
	空格或制表符缩进：下面是一段引用内容dsagasdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdsdfasdfasfasf
		空格或制表符再次缩进：段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容。
> 利用 `>` 符号进行缩进：落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩
>>利用 `>` 符号进行再次缩进:容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩进段落内容再次缩。
    
##<i class="icon-tint"></i>**强调、斜体、删除、分隔线**
###语法：
* 以星号`*`或底线`_`：1个代表斜体，2个代表强调。
* 在文本的首尾分别放2个`~` 符号，代表删除。
* 3个以上的星号`*`、减号`-`、底线`_`来建立一个分隔线，行内不能有其他东西。
###例子：
> _asgjlasd;jf斜体_
> *fasdgka斜体*
> __fdaskaksdg;kadsgadsg强调__
> **fa;sdlgk'adkgffasdfasdfa强调**
> ___adgnlad;fmgnklad斜体+强调___
> ~~删除线的文字~~

***

##<i class="icon-tint"></i>**列表**
###语法：
1.   **无序列**
以**`*、+、-`**做为列表的项目标记。
项目可以包含多个段落，每个项目下的段落都必须缩进4个空格或是1个制表符在列表项目内放进引用，那 `>`就需要缩进放代码区块的话，该区块就需要缩进两次，也就是 8 个空格或是 2 个制表符。
2. **有序列表 **
	数字(不必是顺序关系)接着一个英文句点和空格作为项目标记。

>**Tip：**
>1. 列表间可相互嵌套另外一种列表定义：
>2. 有序列表与想表达的数字产生歧义, 在句点前面加上反斜杠(1\. asfasfd. =>`1. 	asfasfd.`)
>3. 转义
 	反斜杠实现转义， 支持以下这些符号前面加上反斜杠来帮助插入普通的符号
 	例如：
	`\ ` 反斜线 &ensp;&emsp;&emsp;&emsp;&emsp;	`` `反引号
	 `* `星号&ensp;&emsp; &emsp;&emsp;&emsp;&emsp;	` _ `底线
 	`{} `花括号 &emsp;&emsp;&emsp;&emsp;	`[] `方括号 
	`() `括弧 &emsp;&emsp;&emsp;&emsp;&emsp;	`# `井字号 
	`+ `加号 &ensp;&emsp;&emsp;&emsp;&emsp;&emsp;	`-`减号 
	`. `英文句点&ensp;&ensp;&ensp;&ensp;&emsp;&emsp;	`!` 惊叹号

###例子：
* 无序列表1
* 无序列表２
* 无序列表３

----
- 无序列表1
- 无序列表2
- 无序列表3

----
+ 无序列表1
+ 无序列表2
+ 无序列表3

---
1. 有序列表1
2. 有序列表2
3. 有序列表3

---
有序和无序列表之间相互嵌套：

1. 有序列表1
90. 有序列表2
4767. 有序列表3
3.1\. agadgfasdgadgdaaaaaaaaaaaaaaaaaaaaaaaaaagdfgsdfgsdgfaaaaaa
3.2. asfdaffdafasdgfjmfghkfghnvsfasssdjghdjdssssfgsdgfsshsss
4. 有序列表4
     4.1 **有序列表4.1**
     4.2 ~~有序列表4.1~~
5. 有序列表5
+ 无序列表5.1
+ 无序列表5.2
+ 无序列表5.3
     * 无序列表5.3.1
     * 无序列表5.3.2
     * 无序列表5.3.3

**补充：**

[项目1][项目1id]
项目2
: 内容2.1
: 内容2.2

项目3[^项目3id]
:     
 
项目4
: 项目4.1
: 

项目5
: 项目5.1
> 项目5.1.1
>> 项目5.1.1.1
:  

项目6
:  
##<i class="icon-tint"></i>**链接**
###语法：
> 1. **行内链接** 
2. **参考链接**
3.  **隐式链接**
4.  **直接链接**

###例子：

 > 这是行内链接------[必应](http://bing.com.cn "必应搜索" )。
 > 
> 这是参考链接------[icon查询入口][icon]。
> 
> 这是隐式链接------[Google][]	
> 
> 这是直接链接------**<http://www.baidu.com>**

##<i class="icon-tint"></i>**图片** 
###语法：
>1. 行内形式
>2. 参考形式
>
> **Tip:**目前为止，Markdown 还没有办法指定图片的宽高，如果需要的话，可以使用普通的标签。

###例子：
  
![我的图像](http://pic1.nipic.com/2009-02-20/2009220135032130_2.jpg "旭日阳光")

![本地图片](https://github.com/hiklyTeam/markdown_team/blob/gh-pages/images/fj.jpg?raw=true )

> 图片链接：

>  [![专栏图标](http://avatar.csdn.net/blogpic/20150309232245583.jpg)](http://blog.csdn.net/column/details/markdown.html "CSDN-Markdown专栏")

##<i class="icon-tint"></i>**代码** 
###语法：
1. 行内代码
	以反引号`` ` 标记行内代码
2. 区块代码
	以3个反引号（ ` ``` ` ） 标记区块代码
	区段内的 &(`&amp;`)、 # 、< (`&lt;`)和 >(`&gt;`) 会被自动的转换成 HTML 实体。
###例子：
**行内代码: **代码`alert("内嵌代码");`  阿凡达时代啊发顺丰
```
	阿三；反思；肯尼迪啊发了吗多少了；烦恼啊；是的风景阿拉斯加发那女女女反思反思发生的反思
	烦恼啊；是的风景阿拉斯加发那女女女反思反思发生的反思
```

```javascript
var oldUnload = window.onbeforeunload;
	window.onbeforeunload = function() {
    saveCoverage();
    if (oldUnload) {
        return oldUnload.apply(this, arguments);
    }
    var s = "JavaScript syntax highlighting";
    alert(s);
};
``` 

```HTML
<div class="tab-pane">
   <ul class="clearfix">
    <li class="js-17830272 hide">
       <a href="#"><imgsrc="/views/home/esmp/css/images/head/topNav/ywjh.png"></a>
    </li>
    <li class="js-17830272 hide">
       <a href="#"><img src="/views/home/esmp/css/images/head/topNav/ywbx.png"></a>
    </li>
    <li class="js-17830272 hide">
       <a href="#"><imgsrc="/views/home/esmp/css/images/head/topNav/ywjl.png"></a>
    </li>
</ul>
</div>
```
```css
    body{font-size:12px}
```
```php
    <?php
      echo "hello, world!";
    ?>
```
```python
    s = "Python syntax highlighting"
    print s
```

##<i class="icon-tint"></i>**页内导航**
###语法：
`[导航块][^导航链接标签]`

###例子：
[海康威视信息技术部][^hikvision]


##<i class="icon-tint"></i>**表格**
###语法：
Markdown使用管线图的方式实现表格，表格里面可以使用强调、链接等行内格式。同	时可以指定表格单元格的对齐方式
> **Tip：**表格列的宽度不能设置。Markdown更加关注内容，格式设置性能较弱，如	需设	          置，则可使用CSS。

###例子：
|每天 | 主食 |价格 |
|:--------|:-------------:|-------:|
|周一 |牛肉面、铁板牛柳<br>番茄鸡蛋面 |$6 |
|周二 |<i class="icon-heart"></i>__番茄炒鸡蛋__ |$8 |
|周三|干锅土豆片、![酸菜鱼](http://recipe1.hoto.cn/pic/recipe/g_75/f3/67/223219_5eb03b.jpg "酸菜鱼")|$12|
|周四 |麻辣香锅 |$10 |
|周五 |冬瓜炖排骨 |$6 |

##<i class="icon-tint"></i>**TOC生成目录结构**
> __Tip：__ `[TOC]`可以自动生成文章的目录

##<i class="icon-tint"></i>**icon图标**
icon图标链接：<http://fortawesome.github.io/Font-Awesome/3.2.1/icons/>

#**<i class="icon-sun"></i>Markdown的高级运用**
##**<i class='icon-expand'>公式**
###语法：
1. __行内公式__
	使用`$....公式内容...$`的方式来包含行内公式
2. __陈列公式/块级公式__
使用`$$...公式内容....$$`的方式来包含行内公式

> __MathJax语法要点：__
	1. 使用`\alpha`、`\beta`、`\gamma`等专门标识腊字母α、β、γ
	2. 利用{}实现优先级
	3. 数学运算符
	__具体参考：__
	(1) http://math.stackexchange.com 
    (2) http://blog.csdn.net/lanxuezaipiao/article/details/44341645
    (3) http://blog.csdn.net/whqet/article/details/44277965	

###例子：
The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

__行内公式: __
(1) 圆面积公式：

$S=\pi r^2$

__块级公式：__
(1)积分公式：
$$
S(t)=\int_a^t \sqrt {x^2(t) + y^2(t)} {\rm d}t,  
\begin{cases}
{x=x(t)}
\\[2ex]
{y=y(t)}
\end{cases}(a\leq t  \leq y)
$$
(2)求和公式:
$$
x_1^2 + x_2^2 + \cdots + x_n^2
$$
(3)矩阵：
$$
        \begin{matrix}
        1 & x & x^2 \\
        1 & y & y^2 \\
        1 & z & z^2 \\
        \end{matrix}
$$

##**<i class='icon-expand'>序列图 **
###语法：
序列图是基于js-sequence-diagrams实现的(http://bramp.github.io/js-	sequence-diagrams/)

> __序列代码3步骤：__
	1. title：message  （序列图标题）
	2. Participant
	3. 设置note
&emsp;&emsp;左侧note： note left of acotor： message
&emsp;&emsp;右侧note： note right of actor: message,
&emsp;&emsp;覆盖note： note over actor:message
	4. 设置会话
&emsp;&emsp;实线实箭头： actor->actor: message
&emsp;&emsp;虚线实箭头： actor–>actor:message
&emsp;&emsp;实线虚箭头： actor->>actor:message
&emsp;&emsp;虚线虚箭头： actor–>>actor:message
>  **Tip: ** message中使用`\n`可进行了换行。

###例子：
例1：
```sequence 
	    title:A、B、C之间的联系 
	    note left of A: A一个人在家
	    note right of B: B想去约C玩耍
 	    note over C: 不好意思，今日\n有约，改天吧！
 	    B-->A:我们出去耍呀 
	    note over A,B: AB愉快达成一致。
```
例2：
```sequence 
Title:连接建立的过程
客户主机->服务器主机: 连接请求（SYN=1,seq=client_isn） 
服务器主机->客户主机: 授予连接（SYN=1,seq=client_isn）\n ack=client_isn+1
 客户主机->服务器主机: 确认（SYN=0,seq=client_isn+1）\nack=server_isn+1 
```

##**<i class='icon-expand'>流程图 **
###语法：
基于flowchart.js实现 (http://adrai.github.io/flowchart.js/)

> **流程图要点:** 
	1. 节点定义: 节点名称=>节点类型: 提示文本
	节点类型: start、operation、condition、end等
	节点名称、提示文本自定义，中英文均可
	2. 节点连接
	&emsp;&emsp;(1)一般节点连接：节点->节点 
	&emsp;&emsp;(2)条件判断节点连接：
	&emsp;&emsp;&emsp;&emsp;条件节点(yes)->正确应答节点 
	 &emsp;&emsp;&emsp;&emsp;条件节点(no)->错误应答节点


###例子：
```flow
start=>start: 开始
isLogin=>condition: 是否已登录？
login=>operation: 登陆
selectPic=>operation: 选择一张图片
isPic=>condition: 格式是否正确？
doIt=>operation: 完成资料
isRight=>condition: 资料是否符合要求？
end=>end: 完成

start->isLogin
isLogin(yes)->selectPic
isLogin(no)->login->selectPic
selectPic->isPic
isPic(yes)->doIt->isRight
isPic(no)->selectPic
isRight(yes)->end
isRight(no)->doIt
```


#<i class="icon-sun"></i>**End**
__模板：__

![本地图片](https://github.com/hiklyTeam/markdown_team/blob/gh-pages/images/template.jpg?raw=true )

[icon]: http://fortawesome.github.io/Font-Awesome/3.2.1/icons/ "icon图标查询" 
[项目1id]: https://github.com/ "项目明细"
[^项目3id]: 项目2文档内容：规划萨达哈是大法官爱迪生噶啥地方 ，XZF是倒萨大分工。规划萨达哈是大法官爱迪生噶啥地方 ，XZF是倒萨大分工。规划萨达哈是大法官爱迪生噶啥地方 ，XZF是倒萨大分工。规划萨达哈是大法官爱迪生噶啥地方 ，XZF是倒萨大分工。规划萨达哈是大法官爱迪生噶啥地方 ，XZF是倒萨大分工。

[Google]: http://google.com/ "google默认链接"

[^hikvision]: 这是是海康威视信息技术部，包含了技术支持、研发、售前、售后论坛。