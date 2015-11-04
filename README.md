# Bowtie2-Manual-CN
Brief-简介

This is the Chinese translation of [Bowtie2's Manual](http://bowtie-bio.sourceforge.net/bowtie2/manual.shtml).
[Bowtie2](http://bowtie-bio.sourceforge.net/bowtie2/index.shtml) is a very popular aligner for Next Generation Sequencing data. Since most of the Chinese tutorials are incomplete or even with errors, we create this project to put the translation of official manual here. We are tring our best to finish it as good as we can and as soon as possible. Hope more people join us to make it better. Even one sentence sometimes makes a huge difference.

这是[Bowtie2使用手册](http://bowtie-bio.sourceforge.net/bowtie2/manual.shtml)的中文翻译。
[Bowtie2](http://bowtie-bio.sourceforge.net/bowtie2/index.shtml)是常用的第二代高通量测序数据比对软件。由于大多中文教程没能给大家一个完整的说明，有的甚至有错误，我们创建了这个项目来翻译官网的使用说明。我们正在尽最大的努力翻译地更好、更快，希望更多的朋友可以加入进来。

## Translation-译文

###Other parts are being translated-其他部分正在翻译中

###Getting started with Bowtie 2: Lambda phage example-从这里开始使用Bowtie2：λ噬菌体的例子
Bowtie2自带了一些入门级的示例文件，这些示例文件并不具有科学含义，我们用[λ噬菌体](https://en.wikipedia.org/wiki/Lambda_phage)的参考基因组只是因为它很短，并且例子里面的reads是由一个电脑程序生成的而不是测序的结果。但是，这些文件能让你立即开始运行Bowtie2和下游的程序。

首先按照[获取Bowtie2](http://bowtie-bio.sourceforge.net/bowtie2/manual.shtml#obtaining-bowtie-2)的指导下载它。设置Bowtie2环境变量BT2_HOME，把它指向含有bowtie2, bowtie2-build和bowtie2-inspect二进制文件的新Bowtie2的文件夹。这一步很重要，因为在下面的命令当中，变量BT2_HOME被用来代表那个文件夹的位置。

#####Indexing a reference genome-对参考基因组建库

