# demo2

## 链接

### 内嵌式链接
[]放链接的文字内容
()放链接的地址
 - 外部链接：[百度](http://www.baidu.com)
 - 内部链接1，链接仓库的其他文件：[demo1](demo1.md)
 - 内部链接2，链接仓库的其他文件：[代码块 demo](demo2.md#代码块-demo)
 
### 引用式链接

 - 外部链接：[百度]
 - 外部链接：[百度][baidu]
 - 内部链接1，链接仓库的其他文件：[demo1]
 - 内部链接2，链接仓库的其他文件：[代码块]

## 图片
写法：![]()
图片的MarkDown 语法
![alt](url text)
- 外部图片 demo
![baidu](https://www.baidu.com/img/bd_logo1.png "百度网站")
- 仓库内的图片 demo
![](images/cartoon-ps.jpg)

图片的引用式链接
- 外部图片 demo
![baidu][baidu_logo]
- 仓库内的图片 demo
![][open_png]

## 引用

>这是一个引文。

--出自《处》

多重引用

>>>这是多重引文

## 代码块

- 行内代码

这个代码是用来声明变量是 `var = 10;` 打印

- 块式代码

```javascript
var a="asas";
console.log(a);
```
 与块式代码相近
 四个空格 但是无法使用语法高亮  后面不能加javascript
 
    var a="asas";
    console.log(a);

<!-- 下面是本文档中用到的链接 -->
[百度]: http://www.baidu.com
[baidu]: http://www.baidu.com
[demo1]: demo1.md
[代码块]: demo2.md#代码块
[baidu_logo]: https://www.baidu.com/img/bd_logo1.png
[open_png]: images/cartoon-ps.jpg
