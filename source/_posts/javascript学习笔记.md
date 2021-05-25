---
title: javascript学习笔记
date: 2019-01-21 16:28:38
tags:
---
参考菜鸟教程进行学习
  <!-- more -->
# javascript
## 用法：
HTML 中的脚本必须位于 <script> 与 </script> 标签之间。脚本可被放置在 HTML 页面的 <body> 和 <head> 部分中，也可以保存在外部文件中（则不需要加标签）。
## 输出：
* 使用 window.alert() 弹出警告框。
* 使用 document.write() 方法将内容写到 HTML 文档中。
* 使用 innerHTML 写入到 HTML 元素。
* 使用 console.log() 写入到浏览器的控制台。  

<script>
	var y;
	var z;
	var d;
x=document.getElementsByClassName("Barrage-listItem");
y=document.getElementById(x[0].id);
d=y.getElementsByTagName("div");
var reg = /Barrage-userEnter/i;	
console.log(reg.test(d[0].className)); 
console.log(d[0].className);
if(reg.test(d[0].className))
{
z=y.getElementsByTagName("span");
console.log(z[2].title);
d[0].className="b";
}
</script>

