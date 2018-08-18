1.$(".wrap>ul").children("li") 和 $(".wrap>ul>li") 选择器的区别？chi

jquery遍历-children()方法    语法.children(selector)

1、找到类名为 "selected" 的所有 div 的子元素，并将其设置为蓝色：

```
$("div").children(".selected").css("color", "blue");
```

2、返回的 jQuery 对象包含了所有子元素

​	$('ul.level-2').children().css('background-color', 'red');