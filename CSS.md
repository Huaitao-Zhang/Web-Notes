# CSS

CSS的三种导入方式（优先级递减）：
1. 内联样式
2. 内部样式表
3. 外部样式表
	- 导入方式：\<link rel="stylesheet" href="./styles/style.css">

## 选择器

- 元素选择器
- 类选择器（.）
- ID选择器（#）
- 通用选择器（*）
- 子元素选择器（>）
- 后代选择器（包含选择器）（空格）
- 并集选择器（兄弟选择器）（+）
- 伪类选择器（: hover, : first-child, : nth-child(), : active等）
- 伪元素选择器（::）

## 常用属性

**display**
> - inline
> - inline-block
> - block

**border**
> 顺序：上右下左
> - style
> - width
> - color  

**float**
> - left
> - right

**position**
> - relative
> - absolute

## 盒子模型

- 内容（Content）
- 内边距（Padding）：内容与边框之间的空间（padding属性）
- 边框（Border）（border属性）
- 外边距（Margin）：围绕在边框的外部，是盒子与其他元素之间的空间（margin属性）

## 网页布局方式

- 标准流：由块级元素和行内元素按照默认的方式排列
- 浮动
- 定位
- Flexbox 和 Grid（自适应布局）

### 浮动

- 右浮动
- 左浮动

### 定位

- 相对定位：相对于元素在文档流中的正常位置进行定位
- 绝对定位：相对于其最近的已定位祖先进行定位，不占据文档流
- 固定定位：相对于浏览器窗口进行定位，不占据文档流；在屏幕上的位置固定，不随滚动而移动


