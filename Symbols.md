# Symbols

## Overview

​		大多数情况下，文件路径都使用用 **斜杠 /** 表示层次关系，而使用 **反斜杠 \ ** 作为转义符。



## Slash and Backslash

### **特殊情况**：

- Windows 系统中使用 **反斜杠 \ ** 于文件路径中，例如： `T:\SteamLibrary\steamapps\common\Mirror 2 Project X`

- Markdown 中，插入图片使用 **反斜杠 \ ** 表示路径，例如： `![](.\example_image.png)`

> 值得一提的是，为了使.md文件在不同电脑上能够顺利显示插入的图片，一般使用相对路径使其更具通用性：
>
> > `./Images/` 表示，当前目录中的Images文件夹
> > `../Images/` 表示，当前目录的上一层目录中的Images文件夹
> > `/Images/` 表示，项目根目录（可以指磁盘根目录，也可以指项目根目录，据实际情况而定）

- 

### 一般情况：

**1. 网址**

例如： `https://markdown.com.cn/basic-syntax/`

**2. Escape**

转义符一般使用 Backslash.

- Markdown、Word等中编写数学公式时都采用LaTeX语法，例如：

```latex
\lambda = c\times T
```

- C, C++, Python 等编程语言中使用 backslash 作为转义符：

```python
print('Marisa\n １３枚\n 私は和食ですわ')
```



## Annotation

- Matlab %

```matlab
% Annotation
%{
	Annotation para.
}%
```

- C & Cpp //

```cpp
// Hello.
/*
	Fine.
*/
```

- Python #

```pyt
# Denote A as the point where they first met.
'''
	Long time ago.
'''
```



