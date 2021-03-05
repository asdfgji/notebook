# Latex学习

## 1. 安装

> [texlive](https://www.tug.org/texlive)
>
> texdoc lshort-zh 帮助文档
>
> texdoc ctex 帮助文档

### 1.1 vscode配置

- 安装latexworkshop

## 2.基本框架

```latex
%导言区
\documentclass{article}%/book,report,letter
\usepackage{ctex}

\title{}
\author{}
\data{\taday}

%正文区
\begin{document}%环境名称
	\section{}
	\subsection{}
	\subsubsection{}
	%内容  空行表示回车 \\换行不产生新的段落
\end{document}
```

## 3.公式

```latex
$f(x)$    %数学公式
$$f(x)$$  %行间公式

\begin{equation}
	%用于产生带标号的行间公式
\end{equation}
```

## 4.字体

```latex
%字体族
\textrm{内容} 	%罗马字体
\textsf{}  		  %无衬线
\texttt{} 	      %打字机字体

\rmfamily		  %作用于后面的部分，可以用大括号设置作用域
\sffamily
\ttfamily

%字体系列设置
\textmd{}
\textbf{}

\mdseries
\bfseries

%字体形状
\textup{}
\textit{}
\textsl{}
\textsc{}

\up(it,sl,sc)shape
```

