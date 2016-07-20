# html相关实例记录

**01 插入背景图片：利用background=代码**      

```   
<html>
	<body background="/i/eg_background.jpg">  
		<h3>图像背景</h3>
		<p>gif 和 jpg 文件均可用作 HTML 背景。</p>
		<p>如果图像小于页面，图像会进行重复。</p>
	</body>
</html>
```
***

**02 插入浮动在左右的图片，利用align="right"代码**   

```   
<html>
	<body>
	<p>
	<img src ="/i/eg_cute.gif" align ="left"> 
	带有图像的一个段落。图像的 align 属性设置为 "left"。图像将浮动到文本的左侧。
	</p>

	<p>
	<img src ="/i/eg_cute.gif" align ="right"> 
	带有图像的一个段落。图像的 align 属性设置为 "right"。图像将浮动到文本的右侧。
	</p>
</body>
</html>

```

***
**03 如何插入表格**   

```
<html>

<body>

<h4>带有普通的边框：</h4>  
<table border="1">
<tr>
  <td>First</td>
  <td>Row</td>
</tr>   
<tr>
  <td>Second</td>
  <td>Row</td>
</tr>
</table>

<h4>带有粗的边框：</h4>  
<table border="8">
<tr>
  <td>First</td>
  <td>Row</td>
</tr>   
<tr>
  <td>Second</td>
  <td>Row</td>
</tr>
</table>

<h4>带有很粗的边框：</h4>  
<table border="15">
<tr>
  <td>First</td>
  <td>Row</td>
</tr>   
<tr>
  <td>Second</td>
  <td>Row</td>
</tr>
</table>

</body>
</html>
```
***

**04 表格中空占位符的使用**   

```
<table border="1">
<tr>
<td>row 1, cell 1</td>
<td>row 1, cell 2</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>row 2, cell 2</td>
</tr>
</table>
```

** 05 无序列表与有序列表**

```
<ul>
<li>Coffee</li>
<li>Milk</li>
</ul>
```

```
<ol>
<li>Coffee</li>
<li>Milk</li>
</ol>
```
***


