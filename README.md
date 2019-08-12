# FontEnd
## 前端相关知识
# HTML
#    &nbsp; &nbsp; &nbsp;   &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 第一章,常用标签


## 标题标签    

--在HTML中，一共有六级标题    h1-h6   

 在显示效果上:h1最大，h6最小    标签都是语义化标签   

 6级标题中，h1最重要，h1-h6重要性依次降低    h1标签非常重要，会影响页面在搜索引擎中的排名，页面中只能写一个h1

```html
<h1>一级标题</h1>
<h2>二级标题</h2>
<h3>三级标题</h3>
<h4>四级标题</h4>
<h5>五级标题</h5>
<h6>六级标题</h6>
```



## 段落标签

段落标签用于表示内容中的一个自然段使用p标签来表示一个段落p标签中的文字，默认会独占一行，并且段与段之间有一个间距

```html
<p>这是一个p标签，用来表示一个段落</p>
<p>这是一个p标签，用来表示一个段落</p>
<p>这是一个p标签，用来表示一个段落</p>
```



## 换行标签

换行标签,自结束<br/>

```html
 第一行换行 <br/>
 第一行换行 <br/>
 第一行换行 <br/>
 第一行换行 <br/>
```



## 水平线标签

hr标签可以在页面中生成一条水平线，自结束




# &nbsp; &nbsp; &nbsp;   &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 第二章，实体(转义字符)

在html中，一些如<>中特殊字符是不能直接使用的需要使用一些特殊的符号来表示这些特殊字符，这些特殊符号我们称为实体(转义字符)

```html
实体的语法:     
      &实体的名字;



< &lt;
> &gt;
空格 &nbsp;
```

例子:

```
这是&nbsp;一个空格&nbsp;&nbsp;两个空格&nbsp;&nbsp;&nbsp;三个空格&nbsp;&nbsp;&nbsp;&nbsp;四个空格&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;五个空格
a &lt; b &gt; c
```



# &nbsp; &nbsp; &nbsp;   &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 第三章，meta标签





## 设置关键字

设置meta标签设置网页的关键字

```html
<meta name="keywords" content="HTML5，CSS3,前端"/>
```







## 添加网页描述到搜索引擎


还可以用来指定网页的描述搜索引擎在检索时使用
```
 <meta name="description" content="发布h5，js等前端相关信息">
```





## 实现网页跳转（规定时间）

使用meta可以用来做请求的重定向

语法:

```html
   <meta http-equiv="refresh" content="秒数;url=目标地址"/>
```



实例:

​      5秒之后跳转至博客页面

```html
    <meta http-equiv="refresh" content="5;url=https://blog.csdn.net/qq_35978855/article/details/98761692"/>
```


<br/>
<br/>
<br/>



# &nbsp; &nbsp; &nbsp;   &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 第四章，XHtml语法规范

#### 1,html中不区分大小写，但是我们一般都使用小写

### 2,html中注释一般不能嵌套

### 3,html中标签必须结构完整，要么成对出现，要么自结束标签



<br><br><br>


# &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 第五章:内联框架

##### 使用内联框架可以引入一个外部的页面    <br>

##### 使用iframe来创建一个内联框架  <br>

#####  属性:        <br>

#####          src:指向一个外部页面的路径，可以使用相对路径


<br>
<br>
<br>
<br>

# CSS

#  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第一章,CSS简介

## 内联样式(不推荐使用)
可以将css样式编写到元素的style属性当中    将样式直接编写到style属性中，这种样式我们称为内联样式    内联样式只对当前的元素中的内容起作用，内联样式不方便复用    内联样式属于结构与表现耦合，不方便后期的维护，不推荐使用的





## 样式选择器(强烈推荐)
也可以将CSS样式编写到head中的style标签里将样式表编写的style标签中，然后通过css选择器选中指定元素    然后可以同时为这些元素一起设置样式，这样可以使样式进一步的复用将样式表编写到style标签中，也可以使表现和结构进一步分离，它也是我们推荐的使用方式

<br>
<br>
<br>

#  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第二章，外部样式表

还可以将样式表编写到外部的css文件中,然后通过link标签来将外部的css文件引入到当前页面中，这样外部文件中的css样式表将会应用到当前页面中。<br>

将css样式统一编写到外部的样式表中，完全结构和表现分离,可以使样式表可以在不同的页面中使用，最大限度的使样式可以进行复用，将样式统一写在样式表中，然后通过link标签引入，可以利用浏览器的缓存加快用户访问的速度提高了用户体验,所以在开发中我们最推荐使用的方式就是外部的css文件

<br>

语法:<br>

```html
<link rel="stylesheet" type="text/css" href="style.css">
```


<br>
<br>
<br>

#  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第三章,CSS基本语法

css的注释，作用和HTML注释类似，只不过它必须编写在style标签中，或者是css文件中<br>
css语法:   <br>

 选择器 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 声明块<br>

选择器:   <br> 

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;通过选择器可以选中页面中的指定元素，<br>

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;并且将声明块中的样式应用到选择器对应的元素上<br>

声明块:   <br>

 &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;生命块紧跟在选择器的后面，使用一对{}括起来，<br>

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;声明块中实际上就是一组一组的名值对结构，<br>

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;这一组一组的名值对我们称为声明     <br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在一个声明块中可以写多个声明，多个声明之间使用;隔开    <br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;声明的样式名和样式值之间使用:来连接<br>


<br>
<br>
<br>


#  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第四章,内联和块元素

块元素和内联元素
		
		div就是一个块元素
		   所谓的块元素就是会独占一行的元素,无论他的内容有多少，都会独占一整行
		   p,h1-h6,br都属于块元素
		   div这个标签没有任何语义，就是一个纯粹的块元素，并且不会为它里面的元素设置任何默认的样式
		   div元素主要用来对页面进行布局


​		   
​		   
​	    内联元素:
​		span是一个内联元素(行内元素)
​		     所谓行内元素，指的是只占自身大小的元素，不会占用一行
​			 常见内联元素:
​			 a img iframe span
​			 span没有任何的语义，span标签专门用来选中文字，然后为文字来设置样式


​			 
​			 
​			 
​			 
​	    块元素主要用来做页面的布局，内联元素主要用来选中文本设置样式
​		    一般情况下只使用块元素去包含内联元素，而不会使用内联元素包含块元素
​			a可以包含任何元素，除了其本身
​			p元素不可以包含其他的块元素



<br>
<br>
<br>
# &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第五章,Css常用选择器

#### CssCommonSelector:Css常用选择器


​			
​			
​			为页面中所有的P元素，设置一个字体颜色为红色
​			元素选择器
​			作用:通过元素选择器可以选择页面中所有指定的元素
​			语法:
​			    标签名{}




```
id选择器
			-通过元素的id属性值选中唯一的一个元素
			-语法:
			     #id属性值{}
```







```
 类选择器
		   -通过元素的class属性值选中一组元素
		   -语法:
		         .class属性值{}
```



```
 选择器分组(并集选择器)
		 -通过选择器分组可以同时选中多个选择器对应的元素
		 -语法:选择器1，选择器2，选择器N{}
```



```
通配选择器
		-可以用来选中页面中所有的元素
		语法:
		*{}
```





```
为拥有class p3 span元素设置一个背景颜色为黄色的颜色
	   复合选择器(交集选择器)
	      -作用:
		  -可以选中同时满足多个选择器的元素
		  -语法
		       -选择器1选择器2选择器N{}
```



```
我们可以为元素设置class属性
		         class属性和id属性类似，只不过class属性可以重复
		         拥有class属性值的元素，我们说他们是一组元素
				 可以同时为一个元素设置多个class属性值，多个值之间用空格隔开
```




