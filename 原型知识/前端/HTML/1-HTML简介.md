（注：为了方便显示该笔记中!使用的是中文输入法，并且在标签里加上了不必要的空格）
HTML标签：
HTML全称是 Hypertext Markup Language(超文本标记语言)
HTML通过一系列的标签(也称为元素)、来定义文本、图像、链接等等。HTML标签是由尖括号包围的关键字。
标签通常成对出现,包括开始标签和结束标签(也称为双标签),内容位于这两个标签之间,例如:
< p>这是一个段落。< /p>
< h1>这是一个标题。< /h1>
< a href="#">这是一个超链接。< /a>
除了双标签,也存在单标签,例如:
< input type="text">
< br>
< hr>
区别:单标签用于没有内容的元素,双标签用于有内容的元素

HTML文件结构：
<！-- 这里放置文档的元信息 -- >
<！DOCTYPE html>  `作用：告诉浏览器这是一个HTML文档`
`HTML标签对，也是该HTML文档的根元素，意思是它是该HTML文档的起始点，也是这个文档的最外层容器，包含了整个文档的结构`
body标签对包含了实际显示在浏览器中的页面
<html> 
    <head>  `head 标签对表示文档的头部，包含了文件的一些原信息`
		<！-- 这里放置文档的元信息 -- >
		< title>文档标题< /title>
		< meta charset="UTF-8">  ：文档编码格式
		<！-- 连接外部样式表或脚本文件等 -- > 
		< link rel="stylesheet" type="text/css" href="styles.css">  ：外部样式表
		< script src="script.js">< /script>
	< /head>
	< body>
		<！-- 这里放置页面内容 -- >
		< h1>这是一个标题< /h1>
		< p>这是一个段落。< /p>
		< a href="https://www.example.com">这是一个链接< /a>
		<！-- 其他内容 -- >
		< /body>
< /html>

