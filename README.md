# 西北工业大学研究生选题报告表 \LaTeX 模板

## 如何使用

如何使用请参考文件 =npu-report-sample.tex=. 文件使用 UTF-8 编码, XeLaTeX 编译.

## 已知问题

1. 使用浮动体会编译失败 "". 因为 `table` 和 `figure` 不能出现在 `tcolorbox` 中,
   所以添加图表时不要使用 `table` 和 `figure`. 去掉最外层的`table`和`figure` 环境即可.
2. 在 TeXLive2018上, 使用 `hyperref` 包可能会出错报类似
   "\HyperFirstAtBeginDocument {\ifx\hyper@anchor\@undefined" 的错误. 请尝试
    <https://tex.stackexchange.com/a/309895> 给出的方案, 或不要使用该宏包.
