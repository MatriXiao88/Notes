---
typora-root-url: ..\Images
typora-copy-images-to: ..\Images
---

## 我不知道的CSS

1. 默认情况下background-color/background-image 延伸到了边界的边沿（the edge of the border）。但可以通过[background-clip ](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background-clip)属性来改变。
2. 应该注意的是框的总宽度是width, padding-right, padding-left, border-right, 以及 border-left 属性之和。在一些情况下比较恼人（例如，假使你想要一个框占窗口宽度的50%，但边界和内边距是用像素来表示时该怎么办？），为了避免这种问题，有可能使用属性[box-sizing](https://developer.mozilla.org/zh-CN/docs/Web/CSS/box-sizing)来调整框模型。使用值border-box，它将框模型更改成这个新的模型：
   ![1518507285946](/1518507285946.png)
3. ​

