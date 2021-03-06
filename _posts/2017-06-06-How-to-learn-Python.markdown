---
title:  "Python机器学习库"
date:   2017-06-06 13:55:23
categories: [jekyll]
tags: [jekyll]
---
（1）[scikit-learn]("http://scikit-learn.org/stable/")
    Python下做机器学习，首推scikit-learn。该项目文档齐全、讲解清晰，功能齐备，使用方便，而且社区活跃

（2）[Orange]("http://orange.biolab.si/")
    机器学习是其的功能之一，主要还是侧重数据挖掘，可以用可视化语言或Python进行操作，拥有机器学习组件，还具有生物信息学以及文本挖掘的插件。
	
（3）[shogun]("http://shogun-toolbox.org/")
    shogun，非日本的老外弄的一个机器学习库，还专门配了一个我们能看懂的日文名“将军”（是日本幕府时代的将军）。文档齐全，开发活跃，更新快，运算速度也很快。主攻大尺度的核函数，尤其是大尺度核函数下的SVM。具有很多SVM的高级用法，比如多核配用等。支持Python、R、C++、Matlab等语言。
	
（4）其它
     A.pyml(a python module for machine learning，支持svm/knn/k-means==)
         http://mlpy.sourceforge.net/
     B.milk(python的机器学习工具包，主要是针对监督学习，包括svm/knn/决策树)
         http://pypi.python.org/pypi/milk/

   本文参考了oschina.net及http://www.cnblogs.com/wuren/archive/2013/03/27/2985352.html


本文由 伯乐在线 - J.F. 翻译，renlytime 校稿。未经许可，禁止转载！
英文出处：lorenzibex。欢迎加入翻译组。
为了理解和应用机器学习技术，你需要学习 Python 或者 R。这两者都是与 C、Java、PHP 相类似的编程语言。但是，因为 Python 与 R 都比较年轻，而且更加“远离”CPU，所以它们显得简单一些。相对于R 只用于处理数据，使用例如机器学习、统计算法和漂亮的绘图分析数据， Pthon 的优势在于它适用于许多其他的问题。因为 Python 拥有更广阔的分布（使用 Jango 托管网站，自然语言处理 NLP，访问 Twitter、Linkedin 等网站的 API），同时类似于更多的传统语言，比如 C python 就比较流行。
在Python中学习机器学习的四个步骤

1、首先你要使用书籍、课程、视频来学习 Python 的基础知识
2、然后你必需掌握不同的模块，比如 Pandas、Numpy、Matplotlib、NLP (自然语言处理)，来处理、清理、绘图和理解数据。
3、接着你必需能够从网页抓取数据，无论是通过网站API，还是网页抓取模块Beautiful Soap。通过网页抓取可以收集数据，应用于机器学习算法。
4、最后一步，你必需学习机器学习工具，比如 Scikit-Learn，或者在抓取的数据中执行机器学习算法(ML-algorithm)。
1.Python入门指南：

有一个简单而快速学习Python的方法，是在 codecademy.com  注册，然后开始编程，并学习 Python 基础知识。另一个学习Python的经典方法是通过 learnpythonthehardway ，一个为广大 Python 编程者所推荐的网站。然后还有一个优秀的 PDF， byte of python 。python社团还为初学者准备了一个Python资源列表list of python resources。同时，还有来自 O’Reilley 的书籍 《Think Python》，也可以从这里免费下载 。最后一个资源是 Python 用于计量经济学、统计学和数据分析的介绍：《Introduction to Python for Econometrics, Statistics and Data Analysis 》，其中也包含了 Python 的基础知识。
2.机器学习的重要模块

关于机器学习最重要的模块是：NumPy, Pandas, Matplotlib 和 IPython 。有一本书涵盖了其中一些模块：《Data Analysis with Open Source Tools》 。然后来自于1.的免费书籍《Introduction to Python for Econometrics, Statistics and Data Analysis》，同时也包括 Numpy，Pandas，Matplotlib 和 IPython这几个模块。还有一个资源是 Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython，也包含了一些很重要的模块。以下是其他免费模块的相关链接： Numpy (Numerical Python, Numpy Userguide, Guide to NumPy),  Pandas (Pandas, Powerful Python Data Analysis Toolkit，Practical Business Python，Intros to Pandas Data Structure)  和  Matplotlib books。
其它资源:
10 minutes to Pandas
Pandas for machine learning
100 NumPy exercises
3.从网站通过API挖掘和抓取数据

一旦理解了Python的基础知识和最重要的模块，你必需要学习如何从不同的源收集数据。这个技术也被称作网页抓取。传统的源是网站文本，通过API进入twitter或linkedin一类网站得到的文本数据。网页抓取方面的优秀书籍包括：《 Mining the Social Web》 （免费书籍），《Web Scraping with Python》 和《 Web Scraping with Python: Collecting Data from the Modern Web》。
最后这个文本数据必须要转换为数值数据，通过自然语言处理（NLP）技术完成， Natural language processing with Python 和 Natural Language Annotation for Machine Learning 上面有相应的资料。其它的数据包括图片和视频，可以使用计算机图像技术分析： Programming Computer Vision with Python，Programming Computer Vision with Python: Tools and algorithms for analyzing images  和  Practical Python and OpenCV ，这些是图片分析方面的典型资源。
以下例子中包括可以用基本的Python命令行实现，有教育意义，而且有趣的例子，以及网页抓取技术。
Mini-Tutorial: Saving Tweets to a Database with Python （微型教程：使用Python保存推文到数据库）
Web Scraping Indeed for Key Data Science Job Skills （网页抓取关键数据科学工作技巧）
Case Study: Sentiment Analysis On Movie Reviews （案例学习：电影评论中的情感分析）
First Web Scraper （第一网页抓取）
Sentiment Analysis of Emails （邮件的情感分析）
Simple Text Classification （简单文本分类）
Basic Sentiment Analysis with Python （Python基础情感分析）
Twitter sentiment analysis using Python and NLTK （使用Python和NLTK 做Twitter情感分析）
Second Try: Sentiment Analysis in Python （第二个尝试：Python情感分析）
Natural Language Processing in a Kaggle Competition for Movie Reviews  （电影评论相关Kaggle Competition中的NLP自然语言处理）
4. Python 中的机器学习
机器学习可以分为四组：分类，聚类，回归和降维。
drop_shadows_background2
“分类”也可以称作监督学习，有助于分类图片，用来识别图片中的特征或脸型，或者通过用户外形来分类用户，并给他赋不同的分数值。“聚类”发生在无监督学习的情况，允许用户在数据中识别组/集群。“回归”允许通过参数集估算一个值，可以应用于预测住宅、公寓或汽车的最优价格。
modules, packages and techniques 罗列了 Python、C、Scala、Java、Julia、MATLAB、Go、R 和 Ruby等语言中所有学习机器学习的重要模块、包和技巧。有关Python机器学习的书籍，我特别推荐《Machine learning in action》。尽管有点短，但它很可能是机器学习中的经典，因为它提到了“集体智慧编程时代”：Programming Collective Intelligence。这两本书帮助你通过抓取数据建立机器学习。最近关于机器学习的出版物大多都是基于模块 scikit-learn 。由于所有的算法在模块中都已实现，使得机器学习非常简单。你唯一要做的事就是告诉 Python ，应该使用哪一个机器学习技巧 (ML-technique) 来分析数据。
免费的 scikit-learn教程 可以在 scikit-learn 官方网站上找到。其他的帖子可以通过以下链接获取：
Introduction to Machine Learning with Python and Scikit-Learn （机器学习中 Python 和 Scikit-Learn 的介绍）
Data Science in Python （Python 中的数据科学）
Machine Learning for Predicting Bad Loans （用机器学习来预测坏账）
A Generic Architecture for Text Classification with Machine Learning     （通过机器学习来分类文本的通用架构）
Using Python and AI to predict types of wine  （利用 Python 和 AI 人工智能来预测酒的品种）
Advice for applying Machine Learning  （应用机器学习的建议）
Predicting customer churn with scikit-learn  （使用 scikit-learn 预测用户流失）
Mapping Your Music Collection  （映射你的音乐收藏）
Data Science in Python  （Python 中的数据科学）
Case Study: Sentiment Analysis on Movie Reviews  （案例学习：电影评论中的情感分析）
Document Clustering with Python  （Python中的文档聚类）
Five most popular similarity measures implementation in python  （5 个最流行的Python相似度测量的实现）
Case Study: Sentiment Analysis on Movie Reviews  （案例学习：电影评论中的情感分析）
Will it Python?  （将会是 Python 么？）
Text Processing in Machine Learning  （机器学习中的文本处理）
Hacking an epic NHL goal celebration with a hue light show and real-time machine learning   （使用色彩灯光秀和实时机器学习黑入史诗级 NHL（北美冰球联赛）进球庆祝）
Vancouver Room Prices （温哥华房间价格）
Exploring and Predicting University Faculty Salaries （探索和预测大学教师工资）
Predicting Airline Delays  （预测航班延误）
关于机器学习和 Python 中模块 scikit-learn 的书籍：
Collection of books on reddit  （收集 reddit 新闻网站上的书籍）
Building Machine Learning Systems with Python （用 Python 建立机器学习系统）
Building Machine Learning Systems with Python, 2nd Edition （用 Python 建立机器学习系统，第二版）
Learning scikit-learn: Machine Learning in Python  （学习 scikit-learn:Python 中的机器学习）
Machine Learning Algorithmic Perspective   (透视机器学习算法)
Data Science from Scratch – First Principles with Python  (抓取的数据科学——关于 Python 的首要原则)
Machine Learning in Python   （Python 中的机器学习）
接下来数月将要发行的书籍包括：
《Introduction to Machine Learning with Python》 （Python 机器学习的介绍）
《Thoughtful Machine Learning with Python: A Test-Driven Approach》 （思考 Python 机器学习：接近测试驱动）
机器学习相关的课程和博客

你想要得到一个学位，加入在线课程，或者参加线下讲习班、大本营或大学课程么？这里有一些关于逻辑分析、大数据、数据挖掘和数据科学的在线教育站点链接：Collection of links 。另外推荐一些在线课程–来自Udacity的Coursera 课程：machine learning  和 Data Analyst Nanodegree。还有一些关于机器学习的博客列表：List of frequently updated blogs。
最后是来自 Jake Vanderplas 和 Olivier Grisel，关于探索机器学习的优秀 youtube 视频课程。
机器学习理论

想要学习机器学习的理论？那么，《The Elements of statistical Learning》和《 Introduction to Statistical Learning》 是常常被引用的经典。然后还有另外两本书籍：《Introduction to machine learning 》和《 A Course in Machine Learning》。这些链接包括免费的PDF，你不需要付费！如果不想阅读这些书籍，请观看视频：15 hours theory of machine learning！

