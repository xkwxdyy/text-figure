# text-figure宏包

## 编写背景

LaTeX的试卷排版中，题干和图片排版一直以来是一个比较麻烦的事情，于是想编写一个方便统一的命令用来排版这种题干和图片一起的情况。

## 宏包使用说明

提供`\textfigure[<key>=<val>]{<content>}{<pic>}`

- 由于不确定插图是以何种方式（如用`\includegraphics`或`\includesvg`等），而且插图命令可能有自己的一些参数，综合考虑还是用户自己使用插图命令

- 对于选择题的题干和图片，如果用某些方式自动给题干加括号，导致使用`\textfigure`命令使得括号位置出错的话，可以换个思路，把选项当作“题干”与图片进行排版

具体细节请用户查看用户手册。

## 仓库地址

Github：https://github.com/xkwxdyy/text-figure

Gitee：https://gitee.com/xkwxdyy/text-figure

