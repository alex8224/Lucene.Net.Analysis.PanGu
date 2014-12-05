Lucene.Net.Analysis.PanGu
=========================
fork 自 https://github.com/JimLiu/Lucene.Net.Analysis.PanGu 

主要是修改了该程序一些代码使其能够在Mono for Linux下正确运行, 做了如下修改:

1. 替换 Strings.StrConv 为 OpenCC，使用OpenCC进行简繁转换

2. 修正引用一些路径时找不到文件的问题，使其更加通用


使用说明
=========================

Lucene.Net：https://github.com/apache/lucene.net
盘古分词：http://pangusegment.codeplex.com/ 
