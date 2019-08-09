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





