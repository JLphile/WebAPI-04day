

# WebAPI-04day

1.以下关于查询节点语法，错误的是：（D）
A. 元素.parentNode 是获取父元素
B. 元素.previousElementSibling 是获取上一个元素
C. 元素.nextElementSibling 是获取下一个元素
D. 元素.childNodes 是获取所有子元素
2.以下关于新增节点，错误的是：（D）
A. document.createElement() 创建的是空标签
B. 元素.appendChild(子元素) 会将子元素添加到最后面
C. 元素.insertBefore(A元素,B元素) 是将A元素新增到B元素前面
D. document.createElement() 会将元素添加到DOM树并渲染
3.以下关于节点操作，错误的是? （CD） 【多选题】
A. 父元素.removeChild(子元素) 作用是删除子元素
B. 元素.innerHTML = '' 可以实现清空该元素的所有内容
C. 父元素.removeChild(子元素) 也可以删除其他元素的子元素
D. 元素.cloneNode() 不仅会复制自己,也会复制自己所有的后代元素

4.在JavaScript，可以使用Date对象的哪个方法返回一个月中的某一天（A）
A. getDate()
B. getYear()
C. getMonth()
D.getTime()
5.关于获得时间戳的方法下列那些正确的? （ABC） 【多选题】
A. new Date().getTime()
B. +new Date()
C. Date.now()
D.getTime()

6.关于重绘和回流说法正确的是? （ABCD） 【多选题】
A. 由于节点(元素)的样式的改变并不影响它在文档流中的位置和文档布局时, 则是重绘
B. 元素的尺寸、结构、布局等发生改变时，浏览器就会重新渲染部分或全部文档的过程称为
回流
C. 重绘不一定引起回流，而回流一定会引起重绘
D.简单理解影响到布局了，就会有回流

7.关于时间戳的说明说法正确的是? （ABCD） 【多选题】
A. 比如计算倒计时效果，时间不方便直接进行相减，需要借助于时间戳完成
B. 时间戳是指1970年01月01日00时00分00秒起至现在的毫秒数，它是一种特殊的计量时间的方式
C. 倒计时的算法是： 将来的时间戳 - 现在的时间戳 = 剩余时间毫秒数 ，之后转换为时分秒
D. 时间戳需要借助于日期对象