# CSS 杂谈

## Normal Flow 

1. 内联元素 span  从左到右排列，宽度不够就换行
2. 块级元素 div  从上到下排列，每个元素另起一行
3. inline block 
4. display table
5. display list item
6. display flex

## 宽高如何确定
```
1. 内联元素
    占地宽：内容、padding、margin
    占地高：line height、font size
2. block 元素
    内容区宽：爸爸的内容区域的宽度 - 自己的左右边框 - 自己的左右 margin   2. 可以通过 white-space 控制是否换行
    内容高度：它内部文档流中元素的高度的总和
3. inline-block 元素
   宽：1. 可以设置 width 2. 内容决定宽度 3. 可以通过 white-space 控制是否换行
   高：line height、font size  它内部文档流中元素的高度的总和
```
## 居中（水平、垂直）

文档流中的元素

### 水平
```
1. 内联：在爸爸身上加 ta:c
2. 块级：
	1. 固定宽度的div
	   1. margin-left: auto
	   2. margin-right: auto
	2. 不固定宽度的 div
	   1. margin: 0 100px;
```
### 垂直
```
1. 内联： 
	1. 在爸爸上加 line-height 
	2. 在爸爸上加 padding: 10px 0
	3. 在爸爸上加 line-height 和 padding: 10px 0
2. 块级元素
	1. 在爸爸上加 padding: 10px 0
```
### 
不在文档流中的元素

浮动元素居中？

不可能

绝对定位

```
top: 50%; left: 50%; margin-left: - 宽度的一半; margin-top: - 高度的一半
top: 50%; left: 50%; transform: translate(-50%,-50%) CSS 3
```

兼容性最好的垂直居中：table





## 布局（一栏、两栏、三栏）

IE: float

非IE： flex

面试技巧：具体化、分情况讨论
