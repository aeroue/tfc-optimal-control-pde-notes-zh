# 《最优控制与偏微分方程》中文精校课程讲义

这是 Tohoku Forum for Creativity 2017 课程《Optimal Control and Partial Differential Equations》的十讲中文重构讲义。成品采用深色、3Blue1Brown-inspired 视觉语言，所有核心公式由 LaTeX 排版，示意图由 TikZ 矢量绘制。

**[下载完整 PDF 讲义](./最优控制与偏微分方程_十讲中文精校讲义_3Blue1Brown风格.pdf)**

## 内容

- 第 1–5 讲：平均场博弈、Wasserstein 几何、Lions 导数、主方程、特征流与势结构
- 第 6–10 讲：随机最优控制、动态规划原理、HJB 方程、验证定理、可测拼接与黏性解
- 附录：符号表、公式卡、十讲速查和学习路径

## 编译

在本目录运行：

    latexmk -xelatex -interaction=nonstopmode -halt-on-error -file-line-error -outdir=build main.tex

主要依赖 TeX Live 2025、XeLaTeX、Microsoft YaHei、TeX Gyre Pagella、TikZ 与 tcolorbox。

## 文件结构

- 最优控制与偏微分方程_十讲中文精校讲义_3Blue1Brown风格.pdf：可直接阅读的完整讲义
- main.tex：总入口与封面
- style/threeblue.sty：色彩、字体、章节、公式框和图形样式
- chapters/：课程地图、十讲正文与附录

深色版本面向屏幕阅读；若用于黑白打印，建议在样式文件中改用浅色背景与深色正文。

## 说明

本仓库为独立整理的学习资料，并非课程官方讲义。课程内容版权归原主讲人与发布机构所有；本讲义仅供课程学习与学术交流。
