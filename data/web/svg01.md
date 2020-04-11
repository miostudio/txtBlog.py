# SVG 入门到精通

SVG 意为可缩放矢量图形（Scalable Vector Graphics）。
SVG 使用 XML 格式定义图像。
SVG 文件是纯粹的 XML。

SVG 的主要竞争者是 Flash。

与 Flash 相比，SVG 最大的优势是与其他标准（比如 XSL 和 DOM）相兼容。而 Flash 则是未开源的私有技术。


## 常用工具列表
- [SVG 实例](https://www.runoob.com/svg/svg-examples.html)
- [SVG 参考手册](https://www.runoob.com/svg/svg-reference.html)
- [SVG 在线编辑器](https://c.runoob.com/more/svgeditor/)
- [菜鸟教程](https://www.runoob.com/svg/svg-inhtml.html)


## 如何在html中使用svg

SVG 文件可通过以下标签嵌入 HTML 文档：<embed>、<object> 或者 <iframe>。
SVG的代码可以直接嵌入到HTML页面中，或您可以直接链接到SVG文件。





## 创建 SVG 示例1： 一个红心黑边的圆形


<svg xmlns="http://www.w3.org/2000/svg" version="1.1">
   <circle cx="100" cy="50" r="40" stroke="black" stroke-width="2" fill="red" />
</svg> 

```
<!DOCTYPE html>
<html>
<body>
<h1>My first SVG</h1>

<svg xmlns="http://www.w3.org/2000/svg" version="1.1">
   <circle cx="100" cy="50" r="40" stroke="black" stroke-width="2" fill="red" />
</svg> 
 
</body>
</html>
```




