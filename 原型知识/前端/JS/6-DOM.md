DOM：
在Web开发中,DOM通常与JavaScript一起使用。
当网页被加载时,浏览器会创建页面的文档对象模型,也就是DOM(Document Object Model)。
每个HTML或XML文档都可以被视为一个文档树,文档树是整个文档的层次结构表示。
文档节点是整个文档树的根节点。
DOM为这个文档树提供了一个编程接口,开发者可以使用JavaScript来操作这个树状结构。
[[文档树.png]]
文档树是整个文档的层次结构的表示。
每个节点都有父节点、子节点和同级节点。
文档节点也就是DOM节点是整个文档树的根节点，
其他节点分布在树的不同层次上。
DOM的作用是给文档树提供一个编程的接口，即DOM API。开发者就可以通过JS来操作这个树状的结构。
DOM中的一切都是节点，文档的本身也是一个文档节点。文档中的元素都可以称为元素节点。各个元素的属性可以被称为属性节点。元素的文本内容可以称为文本节点。

在JS中获取元素节点需要使用DOM API提供的方法来获取文档中的元素。
五种方法：
getElementById
getElementsByClassName
getElementsByName
getElementsByTagName
getElementsByTagNameNS

DOM对象常用方法:

| 方法                | 描述                |
| ----------------- | ----------------- |
| appendChild()     | 把新的子节点添加到指定节点。    |
| removeChild()     | 删除子节点。            |
| replaceChild()    | 替换子节点。            |
| insertBefore()    | 在指定的子节点前面插入新的子节点。 |
| createAttribute() | 创建属性节点。           |
| createElement ()  | 创建元素节点。           |
| createTextNode () | 创建文本节点。           |
| getAttribute()    | 返回指定的属性值。         |
