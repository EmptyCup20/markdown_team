#目录结构：
[toc]
#**markdown示例演示**
---
##**标题**
1级标题1
=====
2级标题
-------
---
##**段落**
&nbsp;&nbsp;&nbsp;&nbsp;哈哈啊啊啊啊啊哈哈哈哈哈啊啊啊啊啊哈哈哈哈哈**哈啊啊啊啊强调**啊哈哈哈哈哈哈啊啊啊啊啊哈哈哈哈哈哈***啊啊斜体***啊啊啊哈
&emsp;&emsp;哈哈哈哈<i class="icon-money">**Money图标**</i>哈啊啊啊<i class="icon-file"></i>**文件图标**啊啊哈哈哈哈哈哈啊啊啊啊啊哈哈哈哈哈

   ---
##**引号或引文**
下面是一段引用内容
>引用***的内容1***
>>引用的内容2
>>引用的内容3
    
  ---
**强调**
*啊啊斜体*
***斜体+强调***
~~删除线的文字~~

---
##**列表**
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
1. 有序列表1
90. 有序列表2
4767. 有序列表3
a. agadg
a. asfdaf
4. 有序列表4
     4.1 **有序列表4.1**
     4.2 ~~有序列表4.1~~
5. 有序列表5
+ 无序列表1
+ 无序列表2
+ 无序列表3
     * 无序列表1
     * 无序列表２
     * 无序列表３


项目1
项目2
: 内容2.1
: 内容2.2
项目3？？？？？？？？？？？？？？？？

---
##**链接**
这是[必应](http://bing.com.cn "必应搜索" )

这儿有[icon查询入口][icon]

   
  ---------
##**图片**
![我的图像](http://pic1.nipic.com/2009-02-20/2009220135032130_2.jpg "旭日阳光")

![专家图标](http://c.csdnimg.cn/jifen/images/xunzhang/xunzhang/bokezhuanjiamiddle.png "专家图标")    
  [![专栏图标](http://avatar.csdn.net/blogpic/20150309232245583.jpg)](http://blog.csdn.net/column/details/markdown.html "CSDN-Markdown专栏")

  ----
 
##**代码**
js代码：`alert("内嵌代码");`  阿凡达时代啊发顺丰

---

	阿三；反思；肯尼迪啊发了吗多少了；烦恼啊；是的风景阿拉斯加发那女女女反思反思发生的反思
	烦恼啊；是的风景阿拉斯加发那女女女反思反思发生的反思

---

 ```javascript
var oldUnload = window.onbeforeunload;
window.onbeforeunload = function() {
    saveCoverage();
    if (oldUnload) {
        return oldUnload.apply(this, arguments);
    }
};
 ``` 

---
##**页内导航**
[海康威视信息技术部][^hikvision]


   ---
##**表格**
|每天 | 主食 |价格 |
|:--------|:-------------:|-------:|
|周一 |牛肉面<br>番茄鸡蛋面 |$6 |
|周二 |<i class="icon-heart"></i>##番茄炒鸡蛋## |$8 |
|周三|干锅土豆片、![酸菜鱼](http://recipe1.hoto.cn/pic/recipe/g_75/f3/67/223219_5eb03b.jpg)|$12|
|周四 |麻辣香锅 |$10 |
|周五 |冬瓜炖排骨 |$6 |

  ---
##**公式**
(1)行内公式：

$S=\pi r^2$

(2)块级公式：
  积分公式：
$$
S(t)=\int_a^t \sqrt {x^2(t) + y^2(t)} {\rm d}t,  
\begin{cases}
{x=x(t)}
\\[2ex]
{y=y(t)}
\end{cases}(a\leq t  \leq y)
$$
求和公式:
$$
x_1^2 + x_2^2 + \cdots + x_n^2
$$
矩阵：
$$
        \begin{matrix}
        1 & x & x^2 \\
        1 & y & y^2 \\
        1 & z & z^2 \\
        \end{matrix}
$$

   ---
##**序列图 **
```sequence 
	    title:A、B、C之间的联系 
	    note left of A: A一个人在家
	    note right of B: B想去约C玩耍
 	    note over C: 不好意思，今日有约，改天吧！
 	    B-->A:我们出去耍呀 
	    note over A,B: AB愉快达成一致。
```

```sequence 
Title:连接建立的过程
客户主机->服务器主机: 连接请求（SYN=1,seq=client_isn） 
服务器主机->客户主机: 授予连接（SYN=1,seq=client_isn）\n ack=client_isn+1
 客户主机->服务器主机: 确认（SYN=0,seq=client_isn+1）\nack=server_isn+1 
```
   ---
##**流程图 **
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

##**UML的用例**

```flow
@startuml
left to right direction
skinparam packageStyle rect
actor customer
actor clerk
rectangle checkout {
  customer -- (checkout)
  (checkout) .> (payment) : include
  (help) .> (checkout) : extends
  (checkout) -- clerk
}
@enduml
```

```flow
<img src='http://g.gravizo.com/g?
@startuml
left to right direction;
skinparam packageStyle rect;
actor customer;
actor clerk;
rectangle checkout {
  customer -- (checkout);
  (checkout) .> (payment) : include;
  (help) .> (checkout) : extends;
  (checkout) -- clerk;
}
@enduml'>
```
[icon]: http://fortawesome.github.io/Font-Awesome/3.2.1/icons/ "icon图标查询" 
[^hikvision]: 这是是海康威视信息技术部，包含了技术支持、研发、售前、售后论坛。
