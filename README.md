## 一些常用css基础
虽然以前并不怎么用过
不过还是很实用的
### li:first-child ~ li(除了第一个li 其他都加一个左边框)
这个属性做导航再适合不过了~
### li:not(:last-child)(除了最后一个li 其他都加下边框)
比较常见于一些列表，展示列表，适合子元素和父元素不等宽的情况
### nth-child(-n+4)（只显示前四条数据(事实上有6条数据)）
布局方面，不用考虑也不用设置父元素的高度，父元素不用设置overflow：hidden；真是省了好多代码哦~