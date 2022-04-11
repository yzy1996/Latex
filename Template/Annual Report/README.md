# <p align=center>`Report Template`</p>



本项目为Latex日常报告模板（Mainly for Qualifying & Annual Report）。

追求在满足需求的同时，尽可能简洁！

远不完善，还望提出宝贵建议，也欢迎自己DIY。



## Release

- v0.1 实现基本模板

- v0.2 14/8/2021

  修改封面标题为正体，添加\paragraph最小标题用法，修改双向引用颜色BUG，合并目录页到\beforemain，添加引用图片时路径自动索引。
  
- V0.3 15/4/2022

  推荐使用一个文档进行文章撰写，添加一系列方便使用的符号标记策略。



## Todo List

- [ ] 增加可选择的多种样式封面



## Usage

推荐使用 Overleaf 作为 Latex 编译器，直接 Upload 我这个 zip 文件即可。

包含文件由一下几个部分构成：

```sh
# 文件树

├── figures # 里面放图片
├── sections # 按章节单独文件写文章
├── style
│   ├── myreport.sty # 模板定义文件
├── main.tex # 加载模板
├── paper.tex # 不按章节单独文件写文章
├── ref.bib # 参考文献
```

你只需要做如下几步：

1. 打开 `main.tex`，修改 title, author, advisor, data 信息；如果不需要附录，则注释掉。
2. 打开 `paper.tex`，写文章咯；如果想分 章节文件写，just do it.
3. 如果需要额外的 package，既可以添加到 `main.text` 里，也可以添加到 `myreport.sty` 里。
4. 如果想修改模板，同样 just do it.



## Latex Treasures

to do
