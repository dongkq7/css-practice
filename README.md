本项目为css训练项目，分模块逐步实现一个完整网站布局。每个模块均包含了实现思路、技巧与注意事项。
## CSS推荐书写顺序：
1. 定位和布局
- position
- top/bottom/left/right
- z-index
- float
- flex（display: flex; flex-direction; justify-content;align-items...）
2. 展示方式和可见性
- display
- opacity
- visibility
3. 盒子模型
- width/height
- box-sizing
- margin/border/padding
- box-shadow
4. 字体、文本效果
- font-family/font-size/font-weight/font-style
- line-height
- text-align
5. 背景相关
- background
6. 其他
- transform/transition/overflow/white-space...

## 编写布局思路
布局方式：先整体后局部
- 每个模块下的img下的renderings.png为该模块需要实现的效果图
- 每个模块下的page.drawio为当前模块实现效果的思路流程图（vscode中安装Draw.io Integration即可查看）
- 公共类名用下划线连接、普通类名用中划线连接
- css/reset.css中编写的是需要重置的样式、css/common.css中编写的是需要抽离出来的公共样式
- 每个模块中的html会用注释描述出布局的思路