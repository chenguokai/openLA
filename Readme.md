# openLA是什么
openLA是Xim饱受线性代数老师证明过程中频繁引用前文所述定理、推论的习惯困扰而整理的中国科学院大学本科线性代数李子明班讲义中出现的定理、引理等的电子版,方便复习讲义时快速查阅.
## 目前进度(随时更新)
### 已经完成:
#### 第一册：
Chapter5部分内容
#### 第二册：
第二章SS5全部完成,SS6部分完成(即完成了LA2-12、LA2-13全部内容、LA2-14 11页之前的内容)
### 尚未完成:
剩余所有内容
## 编码规范
为保证格式前后一致性,对LaTeX符号的选取统一如下:

1. phi使用\varphi而非\phi(因为李老师原文符号更接近\varphi,使其尽可能一致)
2. 线性算子花体使用amsmath宏包中的\mathcal{}命令
3. 数域(如R、C等)使用amsmath宏包中\mathbb{}命令
4. 属于符号使用\in
5. 大的章节使用\section{},小章节使用\subsection{},再小的章节使用\subsection{},每个定理、引理、推论等使用\paragraph{}以便让主体内容不被二次编号
6. 集合中的竖线使用\arrowvert


## 需要注意的问题

1. amsmath宏包不支持中文,故公式中出现中文的位置必须单独处理,不能放在数学环境中
2. 数学环境中字母样式与外部不同,尽量避免混用
3. 文档需要以UTF8格式保存,使用XeLaTeX编译,以防止中文支持问题.
