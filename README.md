# base-demo

常用基础知识点 demo 验证

## css

z-index-demo1.html 验证 z-index 不生效是因为父元素设置了更小的 z-index

如果一个元素被设置了 z-index，但它的父元素被设置了更小的 z-index，那么无论这个元素的 z-index 有多大，它都不会显示在父元素之上。因为 z-index 属性是相对于其最近的定位祖先元素（即 position 属性为 relative、absolute、fixed 或 sticky 的元素）的。

[mdn-z-index](https://developer.mozilla.org/zh-CN/docs/Web/CSS/z-index)
盒子在当前层叠上下文的层叠等级就是 <integer> 的值。盒子还会创建一个局部层叠上下文。这意味着该元素的后代元素不会和该元素的外部元素比较 z-index。
