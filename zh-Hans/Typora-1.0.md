## Typora 1.0

2021年11月23日 Typora.io  

感谢 Frederick Zhang 提供的翻译

> Typora1.0终于来了！ 🎉🎉🎉🎉

- 相较于0.11(beta)版本
  - [新增项](https://support.typora.io/What's-New-1.0/#new)
    - [支持新架构](https://support.typora.io/What's-New-1.0/#new-builds)
    - [数学](https://support.typora.io/What's-New-1.0/#math)
  - [改进/修复](https://support.typora.io/What's-New-1.0/#improvement--fix)
- [相较于第一个测试版本](https://support.typora.io/What's-New-1.0/#changes-from-first-beta-)
- [软件激活](https://support.typora.io/What's-New-1.0/#purchase--activate-typora)

## 相较于0.11 (beta)版本

### 新增项

#### 支持新架构

- 在Windows&Linux上支持了ARM架构.

  ![Screen Shot 2021-11-23 at 23.42.00](https://support.typora.io/media/new-1.0/Screen%20Shot%202021-11-23%20at%2023.42.00.png)

#### 数学公式

在我们升级到MathJax 3.x之后，有一些来自MathJax的突破性变化。

Typora现在提供了两个选项来控制有关行为。

- 增加了在数学公式中自动应用`displaylines`环境的选项，更方便地使用断行。

  | auto apply `displaylines` env                                | disable auto apply `displaylines` env                        |
  | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | ![Screen Shot 2021-11-23 at 23.34.06](https://support.typora.io/media/new-1.0/Screen%20Shot%202021-11-23%20at%2023.34.06.png) 启用后，你可以使用`//`或`//newline`在数学公式中断行，就像在MathJax 2.x一样。 | ![Screen Shot 2021-11-23 at 23.34.59](https://support.typora.io/media/new-1.0/Screen%20Shot%202021-11-23%20at%2023.34.59.png) 禁用此选项后，你需要使用`\displaylines{}`，之后`\`将被视为换行，因为MathJax 3.x还不支持自动换行（[见此](https://github.com/mathjax/MathJax/issues/2312))。 |

- 允许物理包在数学中重新定义`div`宏。

  物理包总是被Typora启用，但在默认情况下，Typora不允许物理包重新定义像`\div`, `\Re`这样的命令。当启用这个选项时，Typora将采用物理包中的`\div`, `\Re`的定义。

### 改进/修复

- 新增新用户欢迎页。
- 输入时更加流畅。
- 为`htaccess`添加基本语法高亮，`js`语法高亮现在支持`ECMAScript 6`的一些新特性（如私有字段）。
- 当用户试图从备份位置编辑文件时添加警告。(Windows / Linux)
- 修复了平铺树中的新文件可能导致重复文件的问题。
- 修复了当启用忽略换行时，换行应呈现为空白的问题。

------

## 相较于第一个测试版本🕐

- 以下是自我们的第一个测试版以来，一些值得注意的特性。

  **感谢所有的测试者**，他们帮助Typora变得更好。

  和以前一样，我们期待着在公开测试后听到你们的反馈和建议 :)

  - 支持YAML前台事项（0.8.5），LaTeX数学公式（0.8.7），`[toc]`（0.9.2），许多新的代码语法亮点，下标和上标（0.9。 6），下划线（0.9.7），高亮（0.9.8.7），图表（0.9.9.7） ，本地文件链接（0.9.9.8.2），表格编辑（0.9.9.8.8），HTML（0.9.9.17），等等。

  - 改善编辑用户体验，支持自动配对（0.9.8.7），智能标点符号（0.9.9.16）。

  - 推出【主题库】（https://theme.typora.io/）（0.9.9.7.8）和【支持网站】（https://support.typora.io/）。

  - 提供大纲视图（0.9.2），字数统计（0.9.5），专注模式和打字机模式（0.9.9.6），黑暗主题（0.9.9.9.2）。

  - 提供其他语言的Typora（从0.9.9.11.2开始）和拼写检查功能。

  - 文件管理，包括 "快速打开"（0.9.9.0），文件树/列表（0.9.9.10），启动时的选项（0.9.9.15），全局搜索（0.9.9.20），等等。

  - 更好的图像管理，包括支持相对路径（0.9.4），复制图像到（0.9.9.18）和上传（0.9.9.32）。

  - 更高级的导出功能（0.10.6）。

  - 新的偏好面板设计（0.9.9.27），新的图标（0.10.6），以及许多新主题。

  - 还有很多......

![img](https://support.typora.io/media/new-1.0/CCHiRYKUAAA9LIc.png)

Typora的早期测试版本


![img](https://support.typora.io/media/new-1.0/Screen%20Shot%202021-11-23%20at%2023.30.26.png)Typora v1.0 (隐藏侧边栏和字数统计可以)

## [软件激活](https://support.typora.io/What's-New-1.0/#purchase--activate-typora)

从V1.0版开始，Typora终于结束了测试版，因此，你需要购买一个许可证代码来激活Typora。

一个许可证代码一次最多可以激活3台设备。一次性购买，不需要订阅。

Typora提供15天的免费试用，如果您已经提交接受了[翻译](https://github.com/typora/Typora-i18n)和[主题](https://github.com/typora/typora-theme-gallery)，请与我们联系以获得免费许可证。

[您可以点击此链接购买Typora](https://store.typora.io/)

关于激活/试用的问题，请[点击这里](https://support.typora.io/activation)。

关于购买/订购的问题，请[点击这里](https://support.typora.io/purchase)。