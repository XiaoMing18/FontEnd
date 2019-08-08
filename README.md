# FontEnd
## 前端相关知识
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







