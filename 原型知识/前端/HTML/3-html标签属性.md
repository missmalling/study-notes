HTML 属性:

属性在HTML中起到非常重要的作用,它们用于定义元素的行为和外观,以及与其他元素的关系。

基本语法:

<开始标签 属性名="属性值">

每个HTML元素可以具有不同的属性:
< p id="describe"class="section">这是一个段落标签</p>
< a href="https://www.baidu.com">这是一个超链接</a>

属性名称不区分大小写,属性值对大小写敏感:
< img src="example.jpg" alt="">
< img SRC="example.jpg" alt="">
< img src="EXAMPLE. JPG" alt="">
< !-- 前两者相同,第三个与前两个不一样 -- >

适用于大多数HTML元素的属性

属性

class  为HTML元素定义一个或多个类名(类名从样式文件引入)

id  定义元素唯一的id

style  规定元素的行内样式

例如:
< h1 id="title"></h1>
< div class="nav-bar"></div>
< h2 class="nav-bar"></h2>