# 广州大学-学位论文Latex模板: 

本模板修改自我2019年的硕士学位论文，2020年上传于[Github](https://github.com/Ian-Jhon/GZHU_Thesis_Latex_Template), 排版基于[GZHU_Latex_Template](https://github.com/whitelok/GZHU_Latex_Template)并参考了[ucasthesis](https://github.com/mohuangrui/ucasthesis), 参考文献格式基于[gbt7714](https://github.com/CTeX-org/gbt7714-bibtex-style)宏包[v1.1.1](https://github.com/Ian-Jhon/gbt7714-bibtex-style)版，主要使用Latex生成广州大学学位论文。

## 主要功能

+ 方便毕业生生成固定格式的毕业论文，本硕博皆可用

## 文件架构

+ README.md 本说明文件

+ main.tex 主文件，用于包含其他文件如：摘要文件，章节文件等

+ paper.bib 收录参考文献

+ Tex 存放各部分的其余.tex文件

  - title.tex 填写封面信息的文件

  - copyright.tex 为版权声明

  - cabstract.tex 为中文摘要

  - ckeywords.tex 为中文关键字

  - eabstract.tex 为英文摘要

  - ekeywords.tex 为英文关键字

  - preface.tex 为前言

  - chapter*.tex 为章节正文内容

  - appendix*.tex 为附录文件

  - acknowledgement.tex 为致谢文件

+ img 存放论文正文所需图片

+ Style 存放格式文件

+ logo 存放校徽，封面等图片

## 使用说明

1. 首先安装Latex及其编译环境（推荐texlive，[Ctex套装](http://www.ctex.org/HomePage)也可以成功编译）

2. 打开main.tex编辑论文框架

3. 修改title.tex封面文件

4. 修改其他tex文件

5. 在修改引用文献的时候主要是修改paper.bib

6. 编译时使用Xelatex即可，需要经过多次编译才能消除目录乱码

## 其它模板

+ https://github.com/Yumingyuan/GZHU-Report-Latex-Version
+ https://github.com/yernhi/collection-latex-templates
