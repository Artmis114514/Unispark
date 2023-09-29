# MarkDown使用手册

## 标题表示


### “#”
“#”的使用，分级标题，但是要注意在“#”后要空一格否则无法生效


### “====”和“-----”
这两个符号在想要标记的文本下方写出即可

示例一
======
示例二
------


## 段落表示（两种方式）
这是第一行（在这里没有加东西）
这是第二行  

这是第一行  
这是第二行（加入两个空格即可）


## 字体表示
### 总之：一个斜，两个粗，三个又粗又斜
*斜体文本*  
_斜体文本_  
**粗体文本**  
__粗体文本__  
***粗斜体文本***  
___粗斜体文本___


## 各种线型
分割线  
连续的“---”和“***”都可以

删除线  
在文字的两端加上两个波浪线 ~~ 即可  
~~示例123456~~

下划线
使用html标签<u>  </u>  
<u>示例123456</u>

脚注（太帅了）
这样子的示例[^1]

[^1]:很麻烦注释内容必须和原文空一行

## 列表

### 以下三种都可以，注意要“空格”
- 列表一
* 列表二
+ 列表三

### 想要嵌套的话在二级标题前面加四个空格

1. 示例一
    - 示例二（这是空四格）
2. 示例三
  - 示例四（这是空两格）
    - 示例五

## 区块的使用
和标题“#”的使用方式类似，是“>”
> 示例一
>> 示例二
>>> 示例三  
>>> 大概就是这样

## 高亮代码块

### "`"这个只能分隔单句代码  
`print("suffer is solo")`  

### “```”可以分隔整块代码，还可以标记语言

```
public class HelloWorld {
    public static void main(String[] args) {
        int a = 5;
        int b = 10;
        int sum = a + b;
        System.out.println("The sum of " + a + " and " + b + " is " + sum);
    }
}
```  



```java
public class HelloWorld {
    public static void main(String[] args) {
        int a = 5;
        int b = 10;
        int sum = a + b;
        System.out.println("The sum of " + a + " and " + b + " is " + sum);
    }
}
```

```py
public class HelloWorld {
    public static void main(String[] args) {
        int a = 5;
        int b = 10;
        int sum = a + b;
        System.out.println("The sum of " + a + " and " + b + " is " + sum);
    }
}
```

## 链接表示

方法一  
(注意要加"http://"不然不会跳转)  
示例一[hhh](https://www.baidu.com)

方法二  
直接标注  
示例二<https://www.baidu.com>

方法三  
使用类似脚标的方法(也要空一行)  
示例三：这是一个常用的网站[百度][1]

[1]:https://www.baidu.com


## 表格  
### |---|必须在第二行，“-”几个都可以
|示例一123|示例二2|
|-|-|
|示例三313131231|示例四31231|

### 冒号在那边,就朝哪边对其
|示例一123|示例二2|
|:--:|:-:|
|示例三313131231|示例四31231|

## 数学公式公式
$y=ax+b$
$$y=ax+b$$

## 文字加粗以及“/”转义
示例一  
**示例一**  
/***
*** 

## 图片
![Alt text](image.png)
![WEB JPG](https://www.runoob.com/wp-content/uploads/2019/03/A042DF30-C232-46F3-8436-7D6C35351BBD.jpg)
![RUNOOB 图标](https://static.runoob.com/images/runoob-logo.png)


## 更多高级用法（流程图,UML）
<https://www.runoob.com/markdown/md-advance.html>
