# MARKDOWN常用語法筆記

> ## 0.檔名.MD



> ## 1.標題與字型語法

# This is  heading1 (big title)
## this is heading2 (Title)

### this is heading3 (subtitle)

This is *Italics 斜體*

This is **BOLD 粗體**

> this is a quote test 

空格 使用< br >

<br>
<br>
<br> 

this is a hr line ( 空行 --- 為HR)

> ## 2.清單


*為清單

* list1 
* list2
* list3

 
* 巢狀List Fruit
  * Apple
  * Orange
  * Banana
* Dairy
  * Milk
  * Cheese

1. order list1
2. order list2    
3. order list1


> ## 3.inline/code block



--- 
`inline code` with backticks 反括號為行內文字


Code Block 程式碼: ```+程式語言

``` bash 
    pa -aux | grep 'php';
    ls -la   
```

``` php 
this is a code block e.g. bash or php
for($i=0;$i<=10;$i++){
    print $i;
}
```

```c#
this is a code block e.g. bash or php
for(var i=0;i<=10;i++){
    Console.Write(i);
}
```

this is line 1 空行

this is a line  \ 

break


> ## 4.LINK 語法

this is link <https://html5zombo.com>

link 語法: [ likename ] ( url )

[link name](https://www.google.com)


this is image 
![](https://commonmark.org/help/images/favicon.png)



