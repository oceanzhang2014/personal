# 西安工程大学本科学位论文 LaTeX 模板


本项目是基于中国科学技术大学的学位论文 LaTeX 模板 ustcthesis修改而来，
按照西安工程大学本科论文要求修改
可能存在偏差，大家按需下载使用

注意：
1. 使用说明文档 `ustcthesis-doc.pdf` 在发布版中附带，用户也可自行编译；**使用模板前应仔细阅读**。
2. 本模板要求 TeX Live、MacTeX、MiKTeX 不低于 2017 年的发行版，
并且尽可能升级到最新。

## 编译文档

- 编译模板的使用说明文档 `ustcthesis-doc.pdf`：
   ```
   latexmk -xelatex ustcthesis-doc.tex
   ```
- 编译论文 `main.pdf`：
   ```
   latexmk -xelatex main.tex
   ```
- 如需清理论文编译过程中的临时文件，可以：
   ```
   latexmk -c
   ```
# 论文效果
![image](https://github.com/oceanzhang2014/personal/blob/main/fig/1.png)
![image](https://github.com/oceanzhang2014/personal/blob/main/fig/2.png)
![image](https://github.com/oceanzhang2014/personal/blob/main/fig/3.png)
![image](https://github.com/oceanzhang2014/personal/blob/main/fig/4.png)
![image](https://github.com/oceanzhang2014/personal/blob/main/fig/5.png)
![image](https://github.com/oceanzhang2014/personal/blob/main/fig/6.png)

