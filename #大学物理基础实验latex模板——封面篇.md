#大学物理基础实验latex模板——封面篇
'''
\documentclass[UTF8]{article} #设置封面格式，编码为UTF8（中文），类型为article
\usepackage{ctex} #中文文档
#geometry包，用以编辑页面布局，[]中为变量
\usepackage[a4paper, left=2cm, right=2cm, top=2cm, bottom=2cm]{geometry}
\usepackage{graphicx} #画图的包
\usepackage{titlesec} #用于自定义文档中标题（例如章节、子章节等）的格式和样式
'''
'''
#开始正文

	 \begin{document}

 #开始编辑标题页
 
 	\begin{titlepage}

#插入图片

		\vspace*{-7cm} #编辑垂直于顶部距离
		\hspace{-4cm} #编辑水平间距
    \includegraphics[width=1.4\linewidth]{C:/file/to/path/南开大学.png}  #插入图片logo调整大小宽度


		\begin{center}	
			\vspace*{-8.5cm}
			\Huge{\textbf{基础物理实验报告}} \\ #换行
			\Large{XXXXXXXXX} #\Large设计字号大小，根据需要调整
		\end{center}
  
		\vspace*{1cm}

			\begin{Large} #字号
			\begin{center}
				\begin{tabular}{ll} #插入表格
					姓\qquad 名: & XXX \\\hline #\\换行并用\hline插入横线
					学\qquad 院: & XXX \\\hline
					学\qquad 号: & XXXXXXX \\\hline
					分\qquad 组: & X组 \\\hline
					日\qquad 期: & XXXX年X月XX日 \\\hline
				\end{tabular}
    	\end{center}
		\end{Large}

       #插入摘要
	\vspace{2cm}
	\hspace{2cm}
	\textbf{\Large 摘要}：这是一篇物理实验报告
	\end{titlepage}
     \end{document} 


#注：原图放在photo里
#URL：https://github.com/YJ-Flibbertigibbet/NKU_framework/blob/Photo/%E5%8D%97%E5%BC%80%E5%A4%A7%E5%AD%A6.png

![实验报告logo](Flibbertigibbet/NKU_framework/blob/Photo/%E5%9F%BA%E7%89%A9%E5%AE%9E%E9%AA%8C%E6%8A%A5%E5%91%8A%E5%B0%81%E9%9D%A2%E6%A0%B7%E7%A8%BF.png))
