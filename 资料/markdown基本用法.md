这几天被吐槽公众号排版难看，于是想起来之前有一款markdown挺好用的。以后写公众号都会用这个，具体的语法也跟大家一起分享一下。下面我会采用语法+效果这样的格式进行展现。

>Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。Markdown可以让适用者专注文字内容而不是排版样式。对于文字工作者来说这一点极其重要。好的想法转瞬而逝，markdown可以让你迅速地把它们记录下来，不用纠结于字体字号行间距等等琐碎事项。
##标题
	###这是三级标题
	####这是四级标题
	
###这是三级标题
####这是四级标题
##字体

	**这是要加粗的标题**
	
	*这是要倾斜的标题*
	
	***这是要倾斜和加粗的标题***

>**这是要加粗的标题**

>*这是要倾斜的标题*

>***这是要倾斜和加粗的标题***
##嵌套

	>引用
	>>引用嵌套

>引用
>>引用嵌套
##分割线
	---
	***
>---
>***
##图片
	![这儿写图片标题，后面是图片地址](https://www.baidu.com/img/pc_906bd0e6235b67bd693484209bb70b29.gif "百度")
	[超链接名](www.baidu.com "超链接title，可不添加")
>![这儿写图片标题，后面是图片地址](https://www.baidu.com/img/pc_906bd0e6235b67bd693484209bb70b29.gif "百度")
>[超链接名](www.baidu.com "超链接title，可不添加")
##列表
	- 无序列表
	
	* 无序列表
	
	+ 无序列表
	
	1. 有序列表
	
	0. 有序列表
	
	1. 列表嵌套
	
	   1. 我是列表嵌套

>
>- 无序列表

>* 无序列表

>+ 无序列表

>1. 有序列表

>0. 有序列表

>1. 列表嵌套

>   1. 我是列表嵌套
 
##表格
```
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |







