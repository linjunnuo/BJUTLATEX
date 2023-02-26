# 这是什么？

这是非官方的北京工业大学硕士研究生的学位论文$\LaTeX$模版（1.0）

制作本模版的思路是因为Office for MacOS的体验极差，加之本人又对word十分不熟练。网上目前没有现成的模版给我白嫖，本着开源精神和拙劣的$\LaTeX$ 理解，参考部分模版（见致谢）赶工出该模版的1.0版本。希望借助此模版，使用者能将本就在毕业季不多的精力专注于文字而不是行距、行高、段落等繁琐的格式上。接下来将介绍模版的使用方法。

本模版中大量格式参考《北京工业大学研究生学位论文撰写规范》和北京工业大学博士论文$\LaTeX$ 模版（见致谢）。但仍有小部分
细节格式未确认（见todo list）。

> 关于格式或修改定制问题，欢迎issue至此模版的git仓库。

# 预览

![](preview.png)

# 怎样使用？怎样修改？

## 怎样使用？

如果您只想使用本模版进行写作，请参考模版第一章。需要很微小的一部分$\LaTeX$基础。

如果您想要修改模版格式，则需要具备稍微多一点的$\LaTeX$模版写作基础。

### 这个版本是学术型硕士版本，专业型硕士能否正常使用？

个人精力有限，没有专门对专业型硕士做模版选项。但您只需要自行修改部分内容，如内封标题文字，外封颜色等。就可以改为专业型硕士模版。

### 需要用到什么工具或平台？

个人测试的操作系统为MacOS 12.3，tex版本为TeX Live 2022。编辑工具为NeoVim。

我并没有对其他操作系统，如windows或在线编辑器，如Overleaf专门适配。适配是未来计划，但据我所知，目前的版本在不同环境下的差别甚小，主要是没有做字体适配。在目前版本中，如果您在其他环境下遇到字体问题，请自行修改相应字体，该文档目录下提供了您可能需要的字体，您可以修改`bjutthesis.cls`文件中的字体为对应的字体文件名。如第33行宋体`Songt SC` 改为`SimSun.ttc`。

### 如果有其他问题怎么解决？

https://www.google.com/

## 怎样修改？

本着开源精神。您可以随意fork或自行下载后本地修改，是否要与该仓库合并，取决于您自己。

# 可能遇到的问题

收集中

# todo

- [ ] windows选项适配
- [ ] 多平台测试
- [ ] 专业型硕士选项适配
- [ ] 一些细节格式
- [ ] 还没想到

# 感谢

本模版参考了大量[该模版](https://github.com/fisherxt/bjutthesis)的格式，组织方式等。
