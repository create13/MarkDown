# demo3

## 水平分隔线 demo (三种写法)

	<hr>  horizontal rule
	
---

	<hr>  horizontal rule
	
***

	<hr>  horizontal rule
	
___
## 流程图
```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
## html 代码 demo

<p align='center'>hello world!</p>
<p align='center'>
<img src="https://www.baidu.com/img/bd_logo1.png" />
</p>
<!--
块注释 
 -->

## 表格demo
   <!-- 横线不要少于3个  |---|    -->

|   这    |   是    | 表头    |
|-----  |:-------:|-------:|
| cell1asas | cell2asas | cell3asas |
| **row 2** | row 2 | row 2 |
| image | [baidu] | ![][baidu_logo] |
精简表格(去掉左右边框线)：

   这    |   是    | 表头    
-----  |:-------:|-------:
 cell1asas | cell2asas | cell3asas 
 row 2 | row 2 | row 2 


  <!-- 表格默认是左对齐的  如果想要左对齐  左侧加入冒号 |:---| 右对齐  右侧加入: 居中对齐两端加入:  | :--- :|    -->

##GFM

github flvored markdown

task list
<!--
checkbox效果  [ ]  里面加入x是勾选 放空格是没有勾选
 -->
- [x] item1
- [ ] item2
- [ ] item3

emoji 表情符号
	:emoji code:
 	:dog:
 	:horse:
 	:smile:
 	:rainbow:
<!--下面是本文中用到的链接引用 -->
[baidu_logo]: https://www.baidu.com/img/bd_logo1.png
[baidu]: http://www.baidu.com
