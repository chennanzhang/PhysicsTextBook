# 高中物理甲种本重排版
本仓库为《高中物理（甲种本）》的重排版。《高中物理（甲种本）》虽出版时间较早（在1983-1985年期间），但其内容体系安排较如今的高中教材来说更为完整且合理。这套教材影响了70后的一代学子。为向此经典教材致敬，特此采用 $\LaTeX$ 进行重排。

# 重排说明
1. 重排工作是在 [jamesfang](https://github.com/jamesfang8499) 工作的基础上完成的，特此表示谢意！
2. 对原版行文中单位和物理量的用法，以《国际单位制及其应用》（GB 3100-1993）、《有关量、单位和符号的一般原则》（GB 3101-1993）等国家标准的要求，进行了少许改动。
3. 对原版中明显的笔误文字进行了修改，一般也均以脚注形式加以说明。
4. 除部分真实照片以外，在可能的情况下，所有插图均采用 tikz 重新绘制。
5. 部分插图绘制困难的，则以真实照片替代，如第一册第九章的回音壁。
6. 由于现存电子扫描版缺少部分插页，故第一册第八章引用的部分插页图未能放入其中。

# 编译说明
1. 需要为 $\TeX$ 安装版安装 [textbook](https://github.com/chennanzhang/textbook) 文档类，这是本文档使用的文档类。
2. 文档中需要使用的中文字体为：
   + 思源宋体（[Google](https://github.com/notofonts/noto-cjk/releases) 或 [Adobe](https://github.com/adobe-fonts/source-han-serif/releases)）
   + 思源黑体（[Google](https://github.com/notofonts/noto-cjk/releases) 或 [Adobe](https://github.com/adobe-fonts/source-han-sans/releases)）
   + [霞鹜文楷](https://github.com/lxgw/LxgwWenKai)
   + [等距更纱黑体](https://github.com/laishulu/Sarasa-Term-SC-Nerd)（可能没有用到，但文档类需要。）
3. 须使用 `xelatex` 进行编译。
4. 为节省仓库空间，只将必要的图片（部分 `jpg`、`png` 格式的插图及编译需要的 `pdf` 插图）放入仓库，其余带有源代码的插图请自行编译。部分图片编译需要安装 GNU-Plot。源文件中使用中文思源字体的未能自动区分 Google 发布版或 Adobe 发布版，请自行调整。

# 其他说明
本项目的内容不可用于商业目的。