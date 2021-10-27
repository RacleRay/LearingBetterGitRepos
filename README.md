# Title: GitHub收集项目维护

<!-- TOC -->

- [Title: GitHub收集项目维护](#title-github收集项目维护)
  - [1 编程语言](#1-编程语言)
    - [Python](#python)
      - [编程经验](#编程经验)
      - [开源项目](#开源项目)
        - [爬虫](#爬虫)
        - [其他](#其他)
        - [异步](#异步)
        - [字符串搜索](#字符串搜索)
        - [工具API](#工具api)
        - [工具库](#工具库)
    - [C++](#c)
      - [编程书籍](#编程书籍)
      - [开源项目](#开源项目-1)
    - [Julia](#julia)
    - [Java](#java)
    - [GO](#go)
    - [数据结构与算法](#数据结构与算法)
    - [计算机科学基础](#计算机科学基础)
      - [CSAPP](#csapp)
      - [系统设计](#系统设计)
      - [架构技能树](#架构技能树)
    - [自己动手写项目](#自己动手写项目)
    - [其他语言](#其他语言)
  - [2 深度学习](#2-深度学习)
    - [Colab神器](#colab神器)
    - [损失函数](#损失函数)
    - [算法实现](#算法实现)
      - [NLP](#nlp)
        - [Transformer](#transformer)
        - [2 预训练模型](#2-预训练模型)
        - [* 其他语言模型](#-其他语言模型)
        - [3 CRF、LAN](#3-crflan)
        - [* CLUE项目合辑（NLP）](#-clue项目合辑nlp)
        - [* BERT Applications](#-bert-applications)
        - [* NER](#-ner)
        - [* ELMo](#-elmo)
        - [4 相似度匹配](#4-相似度匹配)
        - [* 文本分类](#-文本分类)
        - [*  Aspect Based Sentiment Analysis](#--aspect-based-sentiment-analysis)
        - [5 文本摘要](#5-文本摘要)
        - [6 seq2seq](#6-seq2seq)
        - [* QA](#-qa)
        - [7 ModelZoo](#7-modelzoo)
        - [8 开源包](#8-开源包)
        - [9 其他model](#9-其他model)
        - [10 Book代码](#10-book代码)
        - [11 可视化](#11-可视化)
        - [12 最新研究进展](#12-最新研究进展)
        - [13 关系抽取](#13-关系抽取)
        - [14 蒸馏](#14-蒸馏)
        - [15 对话](#15-对话)
        - [16 指代消解](#16-指代消解)
        - [17 主题](#17-主题)
        - [18 自动机](#18-自动机)
        - [19 阅读理解](#19-阅读理解)
      - [推荐系统](#推荐系统)
      - [相似性](#相似性)
      - [语音](#语音)
      - [GAN](#gan)
      - [CV](#cv)
        - [图像识别与分类](#图像识别与分类)
        - [opencv](#opencv)
        - [目标检测](#目标检测)
        - [医疗](#医疗)
        - [多模态](#多模态)
        - [图像高清化/风格转换/老化照片处理](#图像高清化风格转换老化照片处理)
        - [数据增强](#数据增强)
      - [Reinforcement Learning](#reinforcement-learning)
      - [知识图谱](#知识图谱)
      - [深度贝叶斯/概率](#深度贝叶斯概率)
      - [Capsule Net](#capsule-net)
      - [自动驾驶](#自动驾驶)
      - [机器人](#机器人)
      - [Contrastive Learning](#contrastive-learning)
      - [Adversarial Attack](#adversarial-attack)
      - [Multi-Task Learning](#multi-task-learning)
      - [联邦学习](#联邦学习)
      - [图网络](#图网络)
    - [框架实践](#框架实践)
      - [Tensorflow](#tensorflow)
        - [C++](#c-1)
      - [Pytorch](#pytorch)
      - [MxNet](#mxnet)
      - [Spark](#spark)
      - [Ray](#ray)
      - [Lasagne](#lasagne)
      - [MindSpore](#mindspore)
      - [MegEngine](#megengine)
      - [基础](#基础)
    - [模型优化](#模型优化)
    - [模型训练部署](#模型训练部署)
      - [部署](#部署)
      - [训练](#训练)
    - [Transfer Learning](#transfer-learning)
    - [多任务](#多任务)
    - [偏向研究](#偏向研究)
      - [NLP](#nlp-1)
      - [CV](#cv-1)
      - [图网络](#图网络-1)
      - [GAN](#gan-1)
      - [优化算法](#优化算法)
      - [Trading](#trading)
    - [Awesome](#awesome)
    - [会议资源](#会议资源)
    - [项目idea](#项目idea)
  - [3 机器学习](#3-机器学习)
    - [开源工具](#开源工具)
      - [算法包](#算法包)
      - [聚类](#聚类)
      - [特征](#特征)
      - [科学计算](#科学计算)
    - [GPU加速](#gpu加速)
    - [算法实现](#算法实现-1)
    - [安全机器学习](#安全机器学习)
    - [AutoML](#automl)
    - [可解释机器学习](#可解释机器学习)
    - [实用资料/调参工具](#实用资料调参工具)
  - [4 比赛方案](#4-比赛方案)
    - [比赛信息](#比赛信息)
  - [5 开源工具](#5-开源工具)
    - [可视化](#可视化)
    - [系统工具](#系统工具)
    - [小项目](#小项目)
    - [底层编译架构](#底层编译架构)
    - [并行计算](#并行计算)
    - [测试工具](#测试工具)
  - [6 数据集](#6-数据集)
    - [工具包](#工具包)
    - [NLP](#nlp-2)
    - [标注工具](#标注工具)
    - [图书](#图书)
  - [7 Blogs + 面经](#7-blogs--面经)

<!-- /TOC -->

---

## 1 编程语言

### Python

#### 编程经验

1. [one-python-craftsman](https://github.com/piglei/one-python-craftsman)：python

2. [PySnooper](https://github.com/cool-RR/PySnooper)：Never use print for debugging again，debug tools

3. [The Flask Mega-Tutorial](https://github.com/luhuisicnu/The-Flask-Mega-Tutorial-zh)：Flask教程

4. [微软教程](https://docs.microsoft.com/zh-cn/windows/python/)：在 Windows 上使用 Python 进行开发

5. [realpython -- python-guide](https://github.com/realpython/python-guide)

6. [pipreqs](https://github.com/bndr/pipreqs)：依赖包建立工具 

7. [starlette ：The little ASGI framework that shines](https://github.com/encode/starlette)

8. [fastapi](https://github.com/tiangolo/fastapi)

9. [python-small-examples](https://github.com/jackzhenguo/python-small-examples)

10. [pytudes](https://github.com/norvig/pytudes)：Python programs to practice or demonstrate skills.

11. [python-patterns](https://github.com/faif/python-patterns)：A collection of design patterns/idioms in Python

12. [python并行编程](https://python-parallel-programmning-cookbook.readthedocs.io/zh_CN/latest/)

13. [C++联合编程 [微软Doc](https://docs.microsoft.com/en-us/visualstudio/python/working-with-c-cpp-python-in-visual-studio?view=vs-2019)] 

    - [cppyy: Automatic Python-C++ bindings](https://cppyy.readthedocs.io/en/latest/); 

    - [SWIG](http://www.swig.org/);   
    - [PyBind11](https://github.com/pybind/pybind11); 
    - [ctypes](https://docs.python.org/3/library/ctypes.html#module-ctypes)

14. [scalene](https://github.com/emeryberger/scalene)：Scalene: a high-performance, high-precision CPU and memory profiler for Python

#### 开源项目

##### 爬虫

1. [收集各种爬虫 （默认爬虫语言为 python）](https://github.com/facert/awesome-spider)
2. [lazynlp](https://github.com/chiphuyen/lazynlp)：Library to scrape and clean web pages to create massive datasets.
3. [WeiboSpider](https://github.com/nghuyong/WeiboSpider): This is a sina weibo spider built by scrapy
4. [ weibospider](https://github.com/SpiderClub/weibospider)：A distributed crawler for weibo, building with celery and requests.
5. [webspider](https://github.com/JustForFunnnn/webspider)：数据库用的是`MySQL`, 主要用到的库是`celery`和`requests`，并实现了定时任务，出错重试，日志记录，自动更改`Cookies`等的功能
6. [scrapyscript](https://github.com/jschnurr/scrapyscript)：Run a Scrapy spider programmatically from a script or a Celery task
7. [pspider](https://github.com/zhao94254/pspider)：一个简单的分布式爬虫框架
8. [taoyoulue_spider](https://github.com/runtangr/taoyoulue_spider)：基于mongodb存储，redis缓存，celery 实现的分布式爬虫。
9. [DeadPool](https://github.com/Ryuchen/DeadPool)：使用celery作为主体框架的爬虫应用，能够灵活的添加爬虫任务，并且同时运行多站点的爬虫工作
10. [python-bloomfilter](https://github.com/jaybaird/python-bloomfilter)：Scalable Bloom Filter implemented in Python
11. [learn_python3_spider](https://github.com/wistbean/learn_python3_spider)：python爬虫教程系列、从0到1学习python爬虫，包括浏览器抓包，手机APP抓包
12. [pyspider](https://github.com/binux/pyspider)：A Powerful Spider(Web Crawler) System in Python.
13. [examples-of-web-crawlers](https://github.com/shengqiangzhang/examples-of-web-crawlers)：一些非常有趣的python爬虫例子,对新手比较友好,主要爬取淘宝、天猫、微信、豆瓣、QQ等网站
14. [PythonCrawler](https://github.com/yhangf/PythonCrawler)：用python编写的爬虫项目集合
15. [crawler-py](https://github.com/abbeyokgo/crawler-py)：分享一些爬虫脚本
16. [playwright-python](https://github.com/microsoft/playwright-python)：Python version of the Playwright testing and automation library.
17. [python-cheatsheet](https://github.com/gto76/python-cheatsheet)

##### 其他

1. [python-goose](https://github.com/grangier/python-goose)：Goose 用于文章提取器
2. [python-gems](https://github.com/RealHacker/python-gems)：有趣的 Pyhton 代码片段集合
3. [listen1](https://github.com/listen1)：Listen 1 让你用一个网页就能听到多个网站的在线音乐，支持各种平台
4. [beijing_bus](https://github.com/wong2/beijing_bus)：北京实时公交，可以显示查询的公交到达某站还需多久
5. [tushare](https://github.com/waditu/tushare)：TuShare 是一个免费、开源的 Python 财经数据接口包，[TuShare 文档](http://tushare.org/index.html) 
6. [Supervisor](https://github.com/Supervisor/supervisor)：是实际企业常用的一款 Linux/Unix 系统下的一个进程管理工具
7. [**pyecharts**](https://github.com/pyecharts/pyecharts)：pyecharts是一个由 Echarts+Python 实现的一个用于生成 Echarts 图表的类库
8. [FeelUOwn](https://github.com/cosven/FeelUOwn)：FeelUOwn 是一个用Python写的，面向Linux/macOS平台的开源音乐播放器
9. [**superset**](https://github.com/apache/incubator-superset)：superset是一个实际企业级开发项目，由 airbnb用 Python开发的数据探索
10. [**Spug**](https://github.com/openspug/spug)：Spug 是一款使用 Python+Flask+Vue+Element 组件开发的开源运维管理系统
11. [manim](https://github.com/3b1b/manim)：Animation engine for explanatory math videos
12. [bandit](https://github.com/PyCQA/bandit)：Bandit is a tool designed to find common security issues in Python code.
13. [gopup](https://github.com/justinzm/gopup)：数据接口：百度、谷歌、头条、微博指数,宏观数据，利率数据，货币汇率，千里马、独角兽公司，新闻联播文字稿，影视票房数据，高校名单，疫情数据...
14. [playwright-python](https://github.com/microsoft/playwright-python): python操作浏览器
15. [loguru](https://github.com/Delgan/loguru): 更简洁的python log工具

##### 异步

1. [celery](https://github.com/celery/celery)：Distributed Task Queue (development branch)【master-worker模式】【轻量级】

##### 字符串搜索

1. [pyahocorasick](https://github.com/WojciechMula/pyahocorasick)：**pyahocorasick** is a fast and memory efficient library for exact or approximate multi-pattern string search meaning that you can find multiple key strings occurrences at once in some input text. 
   - AC自动机：[link](https://xueyouluo.github.io/Aho-Corasick-algorithm/) [link](https://racleray.github.io/2021/02/27/%E5%AD%97%E7%AC%A6%E4%B8%B2%E5%8C%B9%E9%85%8D%E4%BB%8EKMP%E5%88%B0AC%E8%87%AA%E5%8A%A8%E6%9C%BA/)
2. [ahocorasick-python](https://github.com/xizhicode/ahocorasick-python)：AC自动机python的实现，并进行了优化
3. [ahocorapy](https://github.com/abusix/ahocorapy): Pure python Aho-Corasick library.
4. [acora](https://github.com/scoder/acora): Fast multi-keyword search engine for text strings.
5. [datrie](https://github.com/pytries/datrie)：Fast, efficiently stored Trie for Python. Uses libdatrie. [pypi](http://pypi.python.org/pypi/datrie/)

##### 工具API

1. [python-wechaty-getting-started](https://github.com/wechaty/python-wechaty-getting-started)：Python Wechaty Starter Project Template that Works Out-of-the-Box。Wechaty is a RPA SDK for Wechat **Individual** Account that can help you create a chatbot in 9 lines of Python.
2. [python-wechaty](https://github.com/wechaty/python-wechaty)

##### 工具库

1. [rich](https://github.com/willmcgugan/rich)：Rich is a Python library for rich text and beautiful formatting in the terminal.
2. [apscheduler](https://github.com/agronholm/apscheduler)：Task scheduling library for Python
3. [jupytext](https://github.com/mwouts/jupytext)：Jupyter Notebooks as Markdown Documents, Julia, Python or R scripts
4. [nbdev](https://github.com/fastai/nbdev)：Create delightful python projects using Jupyter Notebooks

---

### C++

#### 编程书籍

1. Essential C++ (有c基础）
2. C++ Primer第四版 (内容很全）
3. Effective C++
4. More Effective C++(较深一些)
5. C++ 标准程序库
6. 深入探索C++对象模型
7. [CPlusPlusThings](https://github.com/Light-City/CPlusPlusThings)：C++那些事

   

#### 开源项目

1. [cjson](https://sourceforge.net/projects/cjson/)
   [MyTinySTL](https://github.com/Alinshans/MyTinySTL )： stl
   [oatpp](https://github.com/oatpp/oatpp)： web框架
   [Tinyhttpd](https://github.com/EZLippi/Tinyhttpd/blob/master/httpd.c)： http server
   [nginx](http://nginx.org/)： 静态服务器
   [Redis](https://redis.io/download)： redis高速缓存  较难
2. [json](https://github.com/nlohmann/json)：C++ 的 JSON 库
3. [awesome-c-cn](https://github.com/jobbole/awesome-c-cn)：C 资源大全中文版，包括构建系统、编译器、数据库、加密、初中高的教程/指南、书籍、库
4. [fast-cpp-csv-parser](https://github.com/ben-strasser/fast-cpp-csv-parser)
5. [godot](https://github.com/godotengine/godot)：Godot Engine – Multi-platform 2D and 3D game engine
6. [simhash](https://github.com/yanyiwu/simhash)：中文文档计算出对应的 simhash 值。simhash 是谷歌用来进行文本去重的算法（[详见 simhash 算法原理及实现](http://yanyiwu.com/work/2014/01/30/simhash-shi-xian-xiang-jie.html)）
7. [ltp](https://github.com/HIT-SCIR/ltp)：语言技术平台（Language Technology Platform，LTP）是哈工大社会计算与信息检索研究中心历时十年开发的一整套中文语言处理系统
8. [Snake](https://github.com/stevennl/Snake)：贪吃蛇游戏 AI 版
9. [vnote](https://github.com/tamlok/vnote)：Markdown 编辑软件
11. [taichi](https://github.com/taichi-dev/taichi)：太极是一种用于计算机图形应用的高性能编程语言
12. [Sourcetrail](https://github.com/CoatiSoftware/Sourcetrail)：Sourcetrail - free and open-source interactive source explorer，代码结构可视化
13. [keepassx](https://github.com/keepassx/keepassx)： a cross platform port of the windows application “Keepass Password Safe”.
14. [wwsearch](https://github.com/Tencent/wwsearch)：腾讯全文搜索引擎
15. [workflow](https://github.com/sogou/workflow): C++ Parallel Computing and Asynchronous Networking Engine
16. [drogon](https://github.com/an-tao/drogon)：Drogon: A C++14/17 based HTTP web application framework running on Linux/macOS/Unix/Windows
17. [openFrameworks](https://github.com/openframeworks/openFrameworks)：openFrameworks is a community-developed cross platform toolkit for creative coding in C++.
18. [TinyML](https://github.com/BurnellLiu/TinyML)：精简的C++ 机器学习库
19. [Catch2](https://github.com/catchorg/Catch2)：A modern, C++-native, header-only, test framework for unit-tests
20. [flashlight](https://github.com/flashlight/flashlight): A C++ standalone library for machine learning
20. [mlibc](https://github.com/managarm/mlibc): 可移植的C标准库
21. [uthash](https://github.com/troydhanson/uthash)：C macros for hash tables and more
22. [WindowsAppSDK](https://github.com/microsoft/WindowsAppSDK)：[FOR Using, NOT Reading] Windows App SDK empowers all Windows Desktop apps with modern Windows UI, APIs, and platform features, including back-compat support, shipped via NuGet. 

---

### Julia

1. [ julia_notebooks](https://github.com/ageron/julia_notebooks)：Julia Jupyter/Colab Notebooks
2. [julia](https://github.com/JuliaLang/julia)：The Julia Language: A fresh approach to technical computing.

---

### Java

1. [SpringAll](https://github.com/wuyouzhuguli/SpringAll)：循序渐进，学习Spring Boot、Spring Boot & Shiro、Spring Batch、Spring Cloud、Spring Cloud Alibaba、Spring Security & Spring Security OAuth2

***

### GO

1. [7days-golang](https://github.com/geektutu/7days-golang)：7 days golang apps from scratch、
2. [GoSpark](https://github.com/zhoubolei/GoSpark)
3. [golearn](https://github.com/sjwhitworth/golearn)：Machine Learning for Go

---

### 数据结构与算法

1. [数据结构和算法必知必会的50个代码实现](https://github.com/wangzheng0822/algo)
2. [Python算法实现-轻量级](https://github.com/qiwsir/algorithm)   [用动画的形式呈现解LeetCode题目的思路-轻量级](https://github.com/MisterBooo/LeetCodeAnimation)
3. [All Algorithms implemented in Python](https://github.com/TheAlgorithms/Python)
4. [algorithms](https://github.com/keon/algorithms)：Minimal examples of data structures and algorithms in Python
5. [Algorithms implemented in C++：For education](https://github.com/TheAlgorithms/C-Plus-Plus)
6. [awesome-algorithms](https://github.com/tayllan/awesome-algorithms)：精选的学习和/或练习算法的资源列表
7. [fucking-algorithm](https://github.com/labuladong/fucking-algorithm)：刷算法全靠套路，labuladong
8. [leetcode_company_wise_questions](https://github.com/MysteryVaibhav/leetcode_company_wise_questions) ：按公司分类的题目列表
9. [ands](https://github.com/nbro/ands)：Algorithms and data structures for educational, demonstrational and experimental purposes.
10. [Algorithms_in_C](https://thealgorithms.github.io/C/)

### 计算机科学基础

1. [计算机速成课](https://github.com/1c7/Crash-Course-Computer-Science-Chinese)
2. [TeachYourselfCS-CN](https://github.com/keithnull/TeachYourselfCS-CN)
3. [computer-science](https://github.com/ossu/computer-science)：🎓 Path to a free self-taught education in Computer Science!
4. [University-Courses-China](https://github.com/deepwzh/University-Courses-China): 中国几所大学课程资料整理，里面有的课程资料带有习题答案，这点很nice
5. [REKCARC-TSC-UHT](https://github.com/PKUanonym/REKCARC-TSC-UHT)：清华大学计算机系课程攻略
6. [zju-icicles](https://github.com/QSCTech/zju-icicles)：浙江大学课程攻略共享计划 [web page](https://qsctech.github.io/zju-icicles/)
7. [CS-Xmind-Note](https://github.com/SSHeRun/CS-Xmind-Note)：计算机专业课（408）思维导图和笔记：计算机组成原理（第五版 王爱英），数据结构（王道），计算机网络（第七版 谢希仁），操作系统（第四版 汤小丹）
8. [awesome-courses](https://github.com/prakhar1989/awesome-courses)：List of awesome university courses for learning Computer Science!
9. [Computer-Networking-A-Top-Down-Approach-NOTES](https://github.com/moranzcw/Computer-Networking-A-Top-Down-Approach-NOTES)：《计算机网络－自顶向下方法(原书第6版)》编程作业，Wireshark实验文档的翻译和解答
10. [dragon-book-exercise-answers](https://github.com/fool2fish/dragon-book-exercise-answers)：编译原理（紫龙书）第2版习题答案

#### CSAPP

深入理解计算机系统：[videos&lectures](https://www.cs.cmu.edu/afs/cs/academic/class/15213-f15/www/schedule.html)

1. labs： https://github.com/Exely/CSAPP-Labs

#### 系统设计

- **[system-design-primer](https://github.com/donnemartin/system-design-primer)**： Learn how to design large-scale systems.

- [Distributed system resources](https://github.com/ty4z2008/Qix/blob/master/ds.md)：分布式资料列表
- [Database system resources](https://github.com/ty4z2008/Qix/blob/master/db.md)：数据库系统资料列表

#### 架构技能树

**[architect-awesome](https://github.com/xingshaocheng/architect-awesome)**



***

### 自己动手写项目

1. [danistefanovic / build-your-own-x](https://github.com/danistefanovic/build-your-own-x)：Build your own (insert technology here) 
2. [bregman-arie / devops-exercises](https://github.com/bregman-arie/devops-exercises)：Linux, Jenkins, AWS, SRE, Prometheus, Docker, Python, Ansible, Git, Kubernetes, Terraform, OpenStack, SQL, NoSQL, Azure, GCP, DNS, Elastic, Network, Virtualization
3. [PlayWithCompiler](https://github.com/RichardGong/PlayWithCompiler)：A GeekTime course about constructing a compiler
4. [15-minute-apps](https://github.com/learnpyqt/15-minute-apps)：15 minute (small) desktop apps built with PyQt

### 其他语言

1. [purr-data](https://github.com/agraef/purr-data)：Pure Data (aka Pd) is a visual programming language.

---

## 2 深度学习

### Colab神器

1. [colabcode](https://github.com/abhishekkrthakur/colabcode): Run VSCode (codeserver) on Google Colab or Kaggle Notebooks.  !!! 注意 访问时，使用 https 协议 ！！！ python extention 使用 2020.5.86806 版本，最新版本不能debug 和 选择 解释器。

### 损失函数

1. [self-adj-dice](https://github.com/fursovia/self-adj-dice)：Implementation of Self-adjusting Dice Loss from "Dice Loss for Data-imbalanced NLP Tasks" paper
2. [pytorch-loss](https://github.com/CoinCheung/pytorch-loss)：label-smooth, amsoftmax, focal-loss, triplet-loss, lovasz-softmax ...

### 算法实现

- [annotated_deep_learning_paper_implementations](https://github.com/labmlai/annotated_deep_learning_paper_implementations) ：Implementations/tutorials of deep learning papers with side-by-side notes; including transformers (original, xl, switch, feedback), optimizers(adam, radam, adabelief), gans(dcgan, cyclegan, stylegan2), reinforcement learning (ppo, dqn), capsnet, sketch-rnn, etc.



#### NLP

- [nlp-recipes](https://github.com/microsoft/nlp-recipes)：Natural Language Processing Best Practices & Examples
- [checklist](https://github.com/marcotcr/checklist)：多种方法评测NLP/NLG任务，颠覆多种SOTA模型在传统评测指标下的结论。
- [NLP-pretrained-model](https://github.com/balavenkatesh3322/NLP-pretrained-model)：A collection of Natural language processing pre-trained models.
- [EasyTransfer](https://github.com/alibaba/EasyTransfer)：EasyTransfer is designed to make the development of transfer learning in NLP applications easier.
- [google-research / language](https://github.com/google-research/language)：Shared repository for open-sourced projects from the Google AI Language team.
- [HuggingFace Bert Model Download Site](https://huggingface.co/models?filter=zh)



##### Transformer

1. [delight](https://github.com/sacmehta/delight)：DeLighT: Very Deep and Light-Weight Transformers. [DeFINE (ICLR'20)](https://openreview.net/pdf?id=rJeXS04FPH) and [DeLighT (preprint)](https://arxiv.org/pdf/2008.00623.pdf).
2. [Transformer-Clinic](https://github.com/LiyuanLucasLiu/Transformer-Clinic)：Understanding the Difficulty of Training Transformers
3. [rezero](https://github.com/majumderb/rezero)：This repository contains the ReZero-Transformer implementation from the paper. It matches Pytorch's Transformer and can be easily used as a drop-in replacement. [**ReZero is All You Need: Fast Convergence at Large Depth**](https://arxiv.org/abs/2003.04887); *ArXiv, March 2020*. 
4. [collaborative-attention](https://github.com/epfml/collaborative-attention)：Code for Multi-Head Attention: Collaborate Instead of Concatenate
5. [sentence_transformer_zh](https://github.com/zhangyi24/sentence_transformer_zh)
6. [Transformer-Transducer](https://github.com/okkteam/Transformer-Transducer)：A streamable speech recognition model。
7. [Informer2020](https://github.com/zhouhaoyi/Informer2020)：the origin Pytorch implementation of Informer in the following paper: [Informer: Beyond Efficient Transformer for Long Sequence Time-Series Forecasting](https://arxiv.org/abs/2012.07436).
8. [linformer-pytorch](https://github.com/tatp22/linformer-pytorch): implementation of Linformer for Pytorch.
9. [awesome-fast-attention](https://github.com/Separius/awesome-fast-attention): list of efficient attention modules
10. [Synthesizer-Rethinking-Self-Attention-Transformer-Models](https://github.com/leaderj1001/Synthesizer-Rethinking-Self-Attention-Transformer-Models)  + [Synthesizer](https://github.com/10-zin/Synthesizer): Implementing SYNTHESIZER
11. [aft-pytorch](https://github.com/rish-16/aft-pytorch)：Unofficial PyTorch implementation of the Attention Free Transformer's AFT-Full layer by Apple Inc



##### 2 预训练模型  

- [awesome-pretrained-chinese-nlp-models](https://github.com/lonePatient/awesome-pretrained-chinese-nlp-models)：高质量中文预训练模型下载链接集合

- [awesome-bert](https://github.com/Jiakui/awesome-bert): BERT、XLNet 相关论文和 github 项目

- [TensorFlow 官方 code and pre-trained models for BERT](https://github.com/facebookresearch/fastText)

- [UER-py](https://github.com/dbiir/UER-py)：Open Source Pre-training Model Framework in PyTorch & Pre-trained Model Zoo

- huggingface [transformers](https://github.com/huggingface/transformers)：Transformers: State-of-the-art Natural Language Processing for Pytorch and TensorFlow 2.0.

- [ERINE](https://github.com/PaddlePaddle/ERNIE)：An Implementation of ERNIE For Language Understanding (including Pre-training models and Fine-tuning tools)

- [ERNIE-Pytorch](https://github.com/nghuyong/ERNIE-Pytorch)

- [五行代码玩转GPT-2Easy-to-use Wrapper for GPT-2](https://github.com/rish-16/gpt2client)

- [ Facebook AI ](https://ai.facebook.com/)

- [google-research / text-to-text-transfer-transformer](https://github.com/google-research/text-to-text-transfer-transformer)

- [bert-as-service](https://github.com/hanxiao/bert-as-service)：Mapping a variable-length sentence to a fixed-length vector using BERT model

- [Chinese-BERT-wwm](https://github.com/ymcui/Chinese-BERT-wwm): Pre-Training with Whole Word Masking for Chinese BERT（中文BERT-wwm系列模型）

- [Chinese-ELECTRA](https://github.com/ymcui/Chinese-ELECTRA)：Pre-trained Chinese ELECTRA（中文ELECTRA预训练模型）

- [bert-for-tf2](https://github.com/kpe/bert-for-tf2)：A Keras TensorFlow 2.0 implementation of BERT, ALBERT and adapter-BERT.

- [bert4keras](https://github.com/bojone/bert4keras)：keras implement of transformers for humans

- [ERNIE-Pytorch](https://github.com/nghuyong/ERNIE-Pytorch): This project is to convert [ERNIE](https://github.com/PaddlePaddle/ERNIE) to [huggingface's](https://github.com/huggingface/pytorch-transformers) format.

- [unilm](https://github.com/microsoft/unilm)：UniLM - Unified Language Model Pre-training / Pre-trained models for natural language understanding (NLU) and generation (NLG) tasks

- #####  XLnet

  - https://github.com/zihangdai/xlnet
  - https://github.com/graykode/xlnet-Pytorch

- [marge-pytorch](https://github.com/lucidrains/marge-pytorch)：Implementation of Marge, **Pre-training via Paraphrasing**, in Pytorch

- [BERT-CCPoem](https://github.com/THUNLP-AIPoet/BERT-CCPoem)：BERT-CCPoem is an BERT-based pre-trained model particularly for Chinese classical poetry

- [microsoft](https://github.com/microsoft)/**[Unicoder](https://github.com/microsoft/Unicoder)** : Unicoder model for understanding and generation. This repo provides the code for reproducing the experiments in [XGLUE: A New Benchmark Dataset for Cross-lingual Pre-training, Understanding and Generation](https://arxiv.org/abs/2004.01401) ([`leaderboard`](https://microsoft.github.io/XGLUE/)).

- [CPM-Generate](https://github.com/TsinghuaAI/CPM-Generate)：Chinese Pre-Trained Language Models (CPM-LM) Version-I

- [CPM-LM-TF2](https://github.com/qhduan/CPM-LM-TF2)：TensorFlow 2.x CPM-Generate

- [BERT-whitening](https://github.com/bojone/BERT-whitening)：简单的向量白化就可以媲美BERT flow

- [OptiPrompt](https://github.com/princeton-nlp/OptiPrompt)：NAACL'2021: Factual Probing Is [MASK]: Learning vs. Learning to Recall



##### * 其他语言模型

- T5： https://github.com/google-research/text-to-text-transfer-transformer   [中文博客](https://mp.weixin.qq.com/s?__biz=MjM5ODkzMzMwMQ==&mid=2650411701&idx=2&sn=f253b2cde92e0be27e4cdb010f8f957a&chksm=becd94ef89ba1df9c417810e83fe2b06686b5f43f550d9335e7b4ebcccb99678d0fbe7b90910&scene=21#wechat_redirect)

- google-research https://github.com/google-research/google-research 

- [ELECTRA: 超越BERT, 19年最佳NLP预训练模型]( https://zhuanlan.zhihu.com/p/89763176 )

- ZEN中文预训练语言模型： https://github.com/sinovation/ZEN 

- [albert](https://github.com/google-research/albert)：ALBERT: A Lite BERT for Self-supervised Learning of Language Representations

- [GPT2-Chinese](https://github.com/Morizeyao/GPT2-Chinese)

- [gpt2-ml](https://github.com/imcaspar/gpt2-ml)：GPT2 for Multiple Languages, including pretrained models. GPT2 多语言支持, 15亿参数中文预训练模型

- [Decoders-Chinese-TF2.0](https://github.com/Morizeyao/Decoders-Chinese-TF2.0)：GPT2 training script for Chinese in Tensorflow 2.0

- [MetaAdapter](https://github.com/iedwardwangi/MetaAdapter)：Specific Layers in Multilingual Language Models

- [BERT-flow](https://github.com/bohanli/BERT-flow)：TensorFlow implementation of On the Sentence Embeddings from Pre-trained Language Models (EMNLP 2020)

- [gpt-2](https://github.com/openai/gpt-2)：Code for the paper "Language Models are Unsupervised Multitask Learners"

- [NeZha_Chinese_PyTorch](https://github.com/lonePatient/NeZha_Chinese_PyTorch)：pytorch版NEZHA，适配transformers

  

##### 3 CRF、LAN

- label-attention inference  https://github.com/oxford-cs-deepnlp-2017/lectures/blob/master/README.md 
-   https://arxiv.org/abs/1908.08676 
-   [pytorch-struct](https://github.com/harvardnlp/pytorch-struct)：A library of tested, GPU implementations of core structured prediction algorithms for deep learning applications. [概率图模型]



##### * CLUE项目合辑（NLP）

CLUE：Organization of Language Understanding Evaluation benchmark for Chinese

1. [CLUEPretrainedModels：高质量中文预训练模型集合：最先进大模型、最快小模型、相似度专门模型](https://github.com/CLUEbenchmark/CLUEPretrainedModels)
2. [CLUECorpus2020：Large-scale Pre-training Corpus for Chinese 100G 中文预训练语料](https://github.com/CLUEbenchmark/CLUECorpus2020)
3. [CLUEDatasetSearch：搜索所有中文NLP数据集](https://github.com/CLUEbenchmark/CLUEDatasetSearch)
4. [CLUE：中文任务基准测评结果](https://github.com/CLUEbenchmark/CLUE)
5. [CLGE：中文生成任务基准测评结果](https://github.com/CLUEbenchmark/CLGE)
6. [ELECTRA：中文 预训练 ELECTRA 模型: 基于对抗学习](https://github.com/CLUEbenchmark/ELECTRA)
7. [CLUENER2020：中文细粒度命名实体识别](https://github.com/CLUEbenchmark/CLUENER2020)
8. [CLUEmotionAnalysis2020：细粒度情感分析数据集](https://github.com/CLUEbenchmark/CLUEmotionAnalysis2020)
9. [DistilBert： 海量中文预训练蒸馏bert模型](https://github.com/CLUEbenchmark/DistilBert)
10. [MobileQA: 离线端阅读理解应用 QA for mobile, Android](https://github.com/CLUEbenchmark/MobileQA)



##### * BERT Applications

- [rasa_chatbot_cn](https://github.com/GaoQ1/rasa_chatbot_cn):基于最新版本rasa搭建的对话系统
- [Bert-Chinese-Text-Classification-Pytorch](https://github.com/649453932/Bert-Chinese-Text-Classification-Pytorch):使用Bert，ERNIE，进行中文文本分类
- [BERT-train2deploy](https://github.com/xmxoxo/BERT-train2deploy)：BERT模型从训练到部署
- [rasa-tutorial](https://github.com/terrifyzhao/rasa-tutorial)：Rasa中文demo与指南
- [rasa-ui](https://github.com/paschmann/rasa-ui): Rasa UI is a frontend for the Rasa Framework
- [text_matching](https://github.com/terrifyzhao/text_matching)：常用文本匹配模型tf版本，数据集为QA_corpus
- [sentence-transformers](https://github.com/UKPLab/sentence-transformers)：Sentence Embeddings with BERT & XLNet, https://arxiv.org/abs/1908.10084
- [labse](https://github.com/bojone/labse)：Language-agnostic BERT Sentence Embedding (LaBSE)
- [BERTopic](https://github.com/MaartenGr/BERTopic)：BERTopic is a topic modeling technique that leverages BERT embeddings and c-TF-IDF to create dense clusters allowing for easily interpretable topics whilst keeping important words in the topic descriptions.
- [Top2Vec](https://github.com/ddangelov/Top2Vec)：Top2Vec is an algorithm for **topic modeling** and **semantic search**. It automatically detects topics present in text and generates jointly embedded topic, document and word vectors.
- [EssayKiller_V2](https://github.com/EssayKillerBrain/EssayKiller_V2)：基于开源GPT2.0的初代创作型人工智能 | 可扩展、可进化
- [Guyu](https://github.com/lipiji/Guyu)：pre-training and fine-tuning framework for text generation
- [LM-BFF](https://github.com/princeton-nlp/LM-BFF)：ACL'2021: LM-BFF: Better Few-shot Fine-tuning of Language Models
- [AliceMind](https://github.com/alibaba/AliceMind)：pre-trained encoder-decoder models and its related optimization techniques developed by Alibaba's MinD



##### * NER

- [spert](https://github.com/markus-eberts/spert)：PyTorch code for SpERT: "Span-based Entity and Relation Transformer". For a description of the model and experiments, see our paper: https://arxiv.org/abs/1909.07755 (accepted at ECAI 2020).
- [mrc-for-flat-nested-ner](https://github.com/pranciskus/mrc-for-flat-nested-ner)：The code for "A Unified MRC Framework for Named Entity Recognition"
- [AutoNER](https://github.com/shangjingbo1226/AutoNER): Learning Named Entity Tagger from Domain-Specific Dictionary. [远程监督方法](https://www.cnblogs.com/Luv-GEM/p/11598294.html)训练，利用无标注数据。

> - Inference:
>   - **[LightNER](https://github.com/LiyuanLucasLiu/LightNER)**: inference w. models pre-trained / trained w. *any* following tools, *efficiently*.
> - Training:
>   - **[LD-Net](https://github.com/LiyuanLucasLiu/LD-Net)**: train NER models w. efficient contextualized representations.
>   - **[VanillaNER](https://github.com/LiyuanLucasLiu/Vanilla_NER)**: train vanilla NER models w. pre-trained embedding.
> - Distant Training:
>   - **[AutoNER](https://shangjingbo1226.github.io/AutoNER/)**: train NER models w.o. line-by-line annotations and get competitive performance.



##### * ELMo

- [bilm-tf](https://github.com/allenai/bilm-tf)：Tensorflow implementation，allen ai
- [预训练模型](https://allennlp.org/elmo)
- [ELMoForManyLangs](https://github.com/HIT-SCIR/ELMoForManyLangs): 中文模型



##### 4 相似度匹配

- [cail2019](https://github.com/padeoe/cail2019)：法研杯2019相似案例匹配第二名解决方案（附数据集和文档）
- [StarSpace](https://github.com/facebookresearch/StarSpace)：Learning embeddings for classification, retrieval and ranking.
- [DSSM](https://github.com/airalcorn2/Deep-Semantic-Similarity-Model)
- [Chinese-sentence-similarity-task](https://github.com/ShuaichiLi/Chinese-sentence-similarity-task)：中文问题句子相似度计算比赛及方案汇总
- [Question-Answering-Albert-Electra](https://github.com/renatoviolin/Question-Answering-Albert-Electra) : Question Answering using Albert and Electra
- [simbert](https://github.com/ZhuiyiTechnology/simbert)：a bert for retrieval and generation
- [haystack](https://github.com/deepset-ai/haystack)： Transformers at scale for question answering & search
- [epidemic-sentence-pair](https://github.com/zzy99/epidemic-sentence-pair)：天池 疫情相似句对判定大赛 线上第一名方案
- [deep_text_matching](https://github.com/wangle1218/deep_text_matching): implementation several deep text match (text similarly) models for keras . cdssm, arc-ii,match_pyramid, mvlstm ,esim, drcn ,bimpm, bert, albert, roberta
- [attention-feature-distillation](https://github.com/clovaai/attention-feature-distillation)：Official implementation for (Show, Attend and Distill: Knowledge Distillation via Attention-based Feature Matching, AAAI-2021)



##### * 文本分类

- [text_classification](https://github.com/brightmart/text_classification)：all kinds of text classification models and more with deep learning
- [Chinese-Text-Classification-Pytorch](https://github.com/649453932/Chinese-Text-Classification-Pytorch)：中文文本分类，TextCNN，TextRNN，FastText，TextRCNN，BiLSTM_Attention，DPCNN，Transformer，基于pytorch，开箱即用
- [TextClassificationBenchmark](https://github.com/wabyking/TextClassificationBenchmark)：A Benchmark of Text Classification in PyTorch
- [Bert-Chinese-Text-Classification-Pytorch](https://github.com/649453932/Bert-Chinese-Text-Classification-Pytorch)：使用Bert，ERNIE，进行中文文本分类
- [multi-class-text-classification-cnn](https://github.com/jiegzhan/multi-class-text-classification-cnn)：Classify Kaggle Consumer Finance Complaints into 11 classes. Build the model with CNN (Convolutional Neural Network) and Word Embeddings on Tensorflow.
- [deep-text-classifier-mtl](https://github.com/dhwajraj/deep-text-classifier-mtl)：tensorflow script for multi-task learning implementation of Kim's paper : Convolutional Neural Networks for Sentence Classification.
- [multi_task-nlp-bert](https://github.com/ZagHe568/multi_task-nlp-bert)： NLP multi-task learning, which includes single-sentence classification, pairwise text similarity, pairwise text classification, and relevance ranking.
- [TextFooler](https://github.com/jind11/TextFooler)：A Model for Natural Language Attack on Text Classification and Inference【对抗攻击】
- [lightning-text-classification](https://github.com/minimalist-nlp/lightning-text-classification)：Minimalist implementation of a BERT Sentence Classifier with PyTorch Lightning, Transformers and PyTorch-NLP.
- [Sequence Projection Models](https://github.com/tensorflow/models/tree/master/research/sequence_projection) >> [**PRADO**]：A family of models that projects sequence to fixed sized features. The idea behind is to build embedding-free models that minimize the model size. Instead of using embedding table to lookup embeddings, sequence projection models computes them on the fly.
- [pytorch-sentiment-analysis](https://github.com/bentrevett/pytorch-sentiment-analysis)：Tutorials on getting started with PyTorch and TorchText for sentiment analysis.
- [BertGCN](https://github.com/ZeroRin/BertGCN)
- [detext](https://github.com/linkedin/detext)：DeText: A Deep Neural Text Understanding Framework for Ranking and Classification Tasks
- [LTP](https://github.com/kssteven418/LTP)：Learned Token Pruning for Transformers
- [regularized-embeddings](https://github.com/MIR-MU/regularized-embeddings)：code for the “Text classification with word embedding regularization and soft similarity measure” (Novotný et al., 2020) paper



##### *  Aspect Based Sentiment Analysis

- [ABSA-PyTorch](https://github.com/songyouwei/ABSA-PyTorch)：基于方面的情感分析，使用PyTorch实现。
- [BERT-for-RRC-ABSA](https://github.com/howardhsu/BERT-for-RRC-ABSA)：code for our NAACL 2019 paper: "BERT Post-Training for Review Reading Comprehension and Aspect-based Sentiment Analysis"
- [Aspect-Based-Sentiment-Analysis](https://github.com/ScalaConsultants/Aspect-Based-Sentiment-Analysis)：Aspect-Based-Sentiment-Analysis: Transformer & Explainable ML (TensorFlow)
- [torchMoji](https://github.com/huggingface/torchMoji)：A pyTorch implementation of the DeepMoji model: state-of-the-art deep learning model for analyzing sentiment, emotion



##### 5 文本摘要

- [**textsum**](https://github.com/tensorflow/models/tree/master/research/textsum)：Sequence-to-Sequence with Attention Model for Text Summarization.
- [sumy](https://github.com/miso-belica/sumy)：Module for automatic summarization of text documents and HTML pages.
- [pointer_summarizer](https://github.com/atulkum/pointer_summarizer)：pytorch implementation of "Get To The Point: Summarization with Pointer-Generator Networks"
- [pointer-generator](https://github.com/abisee/pointer-generator)：Code for the ACL 2017 paper "Get To The Point: Summarization with Pointer-Generator Networks"
- [transformer-pointer-generator](https://github.com/policeme/transformer-pointer-generator)： Transformer and Pointer-generator
- [BertSum](https://github.com/nlpyang/BertSum)：Code for paper Fine-tune BERT for Extractive Summarization
- [hiersumm](https://github.com/nlpyang/hiersumm)：Code for paper Hierarchical Transformers for Multi-Document Summarization in ACL2019
- [**rouge**](https://github.com/google-research/google-research/tree/master/rouge)
- [pegasus](https://github.com/google-research/pegasus)：Pre-training with Extracted Gap-sentences for Abstractive SUmmarization Sequence-to-sequence models, or PEGASUS, uses self-supervised objective Gap Sentences Generation (GSG) to train a transformer encoder-decoder model.
- [awesome-text-summarization](https://github.com/icoxfog417/awesome-text-summarization)：The guide to tackle with the Text Summarization
- [SPACES](https://github.com/bojone/SPACES)：端到端的长本文摘要模型（法研杯2020司法摘要赛道）
- [GPT2-NewsTitle](https://github.com/liucongg/GPT2-NewsTitle)：中文GPT2新闻标题生成项目。
- [Texygen](https://github.com/geek-ai/Texygen)：A text generation benchmarking platform
- [summarize-from-feedback](https://github.com/openai/summarize-from-feedback)：基于强化学习的SOTA



##### 6 seq2seq

- [OpenSeq2Seq](https://github.com/NVIDIA/OpenSeq2Seq)：Toolkit for efficient experimentation with Speech Recognition, Text2Speech and NLP
- [Magenta: Music and Art Generation with Machine Intelligence](https://github.com/tensorflow/magenta)：involves developing new deep learning and reinforcement learning algorithms for generating songs, images, drawings, and other materials.
- [exdeep-nmt](https://github.com/namisan/exdeep-nmt)：代码审核中
- [EmbeddinglessNMT](https://github.com/UriSha/EmbeddinglessNMT)：The implementation of "Neural Machine Translation without Embeddings"
- [TransCoder](https://github.com/facebookresearch/TransCoder)：Pytorch original implementation of TransCoder in [Unsupervised Translation of Programming Languages](https://arxiv.org/pdf/2006.03511.pdf)
- [Sentence-VAE](https://github.com/timbmg/Sentence-VAE)：PyTorch Re-Implementation of "Generating Sentences from a Continuous Space" by Bowman et al 2015 https://arxiv.org/abs/1511.06349



##### * QA

- **[qa_match](https://github.com/wuba/qa_match)**：A simple effective ToolKit for short text matching
- [QA-Survey](https://github.com/BDBC-KG-NLP/QA-Survey)：对问答系统的调研。
- [QueryGeneration](https://github.com/YunwenTechnology/QueryGeneration)：Conversational Standard Meta Language
- [acl2020-openqa-tutorial](https://github.com/danqi/acl2020-openqa-tutorial)：ACL2020 Tutorial: Open-Domain Question Answering
- [ccf_2020_qa_match](https://github.com/xv44586/ccf_2020_qa_match): ccf 2020 qa match competition top1



##### 7 ModelZoo

- [***Gathers machine learning and Tensorflow deep learning models for NLP problems](https://github.com/huseinzol05/NLP-Models-Tensorflow)
- [MatchZoo 是一个通用的文本匹配工具包](https://github.com/NTMC-Community/MatchZoo): deep text matching models
- [awesome-sentence-embedding](https://github.com/Separius/awesome-sentence-embedding)
- [Awesome-Chinese-NLP](https://github.com/crownpku/Awesome-Chinese-NLP)：中文自然语言处理相关资料



##### 8 开源包

- [Open-Source Neural Machine Translation in Tensorflow](https://github.com/EdinburghNLP/nematus)
- [Gluon-NLP made easy](https://github.com/dmlc/gluon-nlp)
- [SnowNLP：Python library for processing Chinese text](https://github.com/isnowfy/snownlp)
- [gensim – Topic Modelling in Python](https://github.com/RaRe-Technologies/gensim)
- [PyText](https://github.com/facebookresearch/pytext)：A natural language modeling framework based on PyTorch，is a deep-learning based NLP modeling framework built on PyTorch.
- [allennlp：An open-source NLP research library, built on PyTorch](https://github.com/allenai/allennlp)
- [结巴中文分词](https://github.com/fxsjy/jieba)
- [lda2vec: Tools for interpreting natural language](https://github.com/cemoody/lda2vec)
- [复旦 fastNLP](https://github.com/fastnlp/fastNLP)：: A Modularized and Extensible NLP Framework. Currently still in incubation.
- [fast text： representation and classification.](https://github.com/facebookresearch/fastText)
- [autotuning for fastText](https://ai.facebook.com/blog/fasttext-blog-post-open-source-in-brief/)
- [HanLP](https://github.com/hankcs/HanLP)
- [pkuseg多领域中文分词工具](https://github.com/lancopku/pkuseg-python)：pkuseg简单易用，支持细分领域分词，有效提升了分词准确度
- [ An open-source neural machine translation toolkit 清华](https://github.com/THUNLP-MT/THUMT/tree/d4cb62c215d846093e5357aa17b286506b2df1af)
- [Neural Modules: a toolkit for conversational AI](https://github.com/NVIDIA/NeMo)
- [stanza](https://github.com/stanfordnlp/stanza)  [Doc](https://readthedocs.org/projects/stanza/)： Official Stanford NLP Python Library for Many Human Languages
- [StarSpace](https://github.com/facebookresearch/StarSpace)：Learning embeddings for classification, retrieval and ranking.
- [BigARTM](http://docs.bigartm.org/en/stable/index.html)：topic model
- [tkitMarker_bert](https://github.com/napoler/tkitMarker_bert)：使用bert微调提取实体，描述
- [fastHan](https://github.com/fastnlp/fastHan)：fastHan是基于fastNLP与pytorch实现的中文自然语言处理工具，像spacy一样调用方便。
- [Jiagu](https://github.com/ownthink/Jiagu)：Jiagu深度学习自然语言处理工具 知识图谱关系抽取 中文分词 词性标注 命名实体识别 情感分析 新词发现 关键词 文本摘要 文本聚类
- [KILT](https://github.com/facebookresearch/KILT)：A Benchmark for Knowledge Intensive Language Tasks。
- [AutoPhrase](https://github.com/shangjingbo1226/AutoPhrase)：Automated Phrase Mining from Massive Text Corpora
- [Kashgari-doc-zh](https://github.com/BrikerMan/Kashgari-doc-zh) [Kashgari](https://github.com/BrikerMan/Kashgari)：Kashgari 是一个极简且强大的 NLP 框架，可用于文本分类和标注的学习，研究及部署上线
- [Senta](https://github.com/baidu/Senta)：Baidu's open-source Sentiment Analysis System.
- [DDParser](https://github.com/baidu/DDParser)：百度开源的依存句法分析系统
- [FastBERT](https://github.com/autoliuweijie/FastBERT)
- [OpenMatch](https://github.com/thunlp/OpenMatch)：An Open-Source Package for Information Retrieval.
- [robustness-gym](https://github.com/robustness-gym/robustness-gym)：Evaluation Toolkit for NLP
- [elasticsearch-py](https://github.com/elastic/elasticsearch-py)：Official Python low-level client for Elasticsearch
- [py-googletrans](https://github.com/ssut/py-googletrans)：Free and Unlimited Google translate API for Python. 
- [UDA_pytorch](https://github.com/SanghunYun/UDA_pytorch)：UDA(Unsupervised Data Augmentation) implemented by pytorch
- [PaddleNLP](https://github.com/PaddlePaddle/PaddleNLP)：An NLP library with Awesome pre-trained Transformer models
- [mars](https://github.com/mars-project/mars)：a tensor-based unified framework for large-scale data computation which scales Numpy, pandas, Scikit-learn and Python functions.
- [TextBlob](https://github.com/sloria/TextBlob): Simple, Pythonic, text processing--Sentiment analysis, part-of-speech tagging, noun phrase extraction, translation...
- [knlp](https://github.com/DukeEnglish/knlp)：类似 snownlp 和 textblob，调用方便，提供基础算法的训练和推理的脚本，各种nlp任务的评估方法以及评估数据集，提供深度学习，面向中文开发，且功能很基础，适合于二次改造。
- [skweak](https://github.com/NorskRegnesentral/skweak):   A software toolkit for weak supervision applied to NLP tasks
- [pytorch-metric-learning](https://github.com/KevinMusgrave/pytorch-metric-learning): The easiest way to use deep metric learning in your application. 可直接使用的 NTXENT loss (InfoNCE) ，SupContrast loss等对比学习损失。
- [dice_loss_for_NLP](https://github.com/ShannonAI/dice_loss_for_NLP)：ACL2020 paper `Dice Loss for Data-imbalanced NLP Tasks`
- [TextBlob](https://github.com/sloria/TextBlob)：Simple, Pythonic, text processing--Sentiment analysis, part-of-speech tagging, noun phrase extraction, translation, and more.



##### 9 其他model

- [show-attend-and-tell](https://github.com/yunjey/show-attend-and-tell)
- [Retrieval-Based Conversational Model in Tensorflow](https://github.com/dennybritz/chatbot-retrieval)
- [sru](https://github.com/asappresearch/sru)：Training RNNs as Fast as CNNs
- [Self_Explaining_Structures_Improve_NLP_Models](https://github.com/ShannonAI/Self_Explaining_Structures_Improve_NLP_Models): BERT输出特征交叉的一种尝试，自定义模型层维度不要太大。依赖调参，效果说好一点就好一点吧。

#####  10 Book代码

   - [Natural Language Processing with PyTorch](https://github.com/joosthub/PyTorchNLPBook)
##### 11 可视化

- [**Text Visualization Browser**](https://textvis.lnu.se/)

##### 12 最新研究进展

   - [track the progress in Natural Language Processing (NLP)](https://github.com/sebastianruder/NLP-progress)
   - [Repository to show how NLP can tacke real problem.](https://github.com/makcedward/nlp)

##### 13 关系抽取

- [Snowball](https://github.com/davidsbatista/Snowball)：Snowball: Extracting Relations from Large Plain-Text Collections
- [OpenNRE](https://github.com/thunlp/OpenNRE)： relation extraction models.
- [MRC4ERE_plus](https://github.com/TanyaZhao/MRC4ERE_plus)：Implementation for Paper "Asking Effective and Diverse Questions: A Machine Reading Comprehension based Framework for Joint Entity-Relation Extraction"
- [AlpacaTag](https://github.com/INK-USC/AlpacaTag)：AlpacaTag: An **Active Learning**-based Crowd Annotation Framework for Sequence Tagging (ACL 2019 Demo)
- [Distant-Supervised-Chinese-Relation-Extraction](https://github.com/xiaolalala/Distant-Supervised-Chinese-Relation-Extraction)：基于远监督的中文关系抽取
- [Entity-Relation-Extraction](https://github.com/yuanxiaosc/Entity-Relation-Extraction)：Entity and Relation Extraction Based on TensorFlow and BERT.
- [Information-Extraction-Chinese](https://github.com/crownpku/Information-Extraction-Chinese)：Chinese Named Entity Recognition with IDCNN/biLSTM+CRF, and Relation Extraction with biGRU+2ATT
- [pytorch-relation-extraction](https://github.com/ShomyLiu/pytorch-relation-extraction)：distant supervised relation extraction models: PCNN MIL (Zeng 2015), PCNN+ATT(Lin 2016).
- [USC-DS-RelationExtraction](https://github.com/INK-USC/USC-DS-RelationExtraction)：Distantly Supervised Relation Extraction
- [open-entity-relation-extraction](https://github.com/lemonhu/open-entity-relation-extraction)：Knowledge triples extraction and knowledge base construction based on dependency syntax for open domain text.
- [BERT-Relation-Extraction](https://github.com/plkmo/BERT-Relation-Extraction)：PyTorch implementation for "Matching the Blanks: Distributional Similarity for Relation Learning" paper
- [PersonRelationKnowledgeGraph](https://github.com/liuhuanyong/PersonRelationKnowledgeGraph)：bootstrapping方法的人物关系抽取,基于知识图谱的知识问答等应用
- [OpenKE](https://github.com/thunlp/OpenKE)：An Open-Source Package for Knowledge Embedding (KE)
- [deepke](https://github.com/zjunlp/deepke)：基于 Pytorch 的深度学习中文关系抽取处理套件
- [DeepIE](https://github.com/loujie0822/DeepIE)：DeepIE: Deep Learning for Information Extraction
- [CasRel](https://github.com/weizhepei/CasRel)：A Novel Cascade Binary Tagging Framework for Relational Triple Extraction
- [CasRel-pytorch-reimplement](https://github.com/longlongman/CasRel-pytorch-reimplement)
- [two-are-better-than-one](https://github.com/LorrinWWW/two-are-better-than-one)：Code associated with the paper **Two are Better Than One: Joint Entity and Relation Extraction with Table-Sequence Encoders**, at EMNLP 2020
- [TPlinker-joint-extraction](https://github.com/131250208/TPlinker-joint-extraction)：TPLinker: Single-stage Joint Extraction of Entities and Relations Through Token Pair Linking
- [PURE](https://github.com/princeton-nlp/PURE)：NAACL'2021: A Frustratingly Easy Approach for Entity and Relation Extraction



##### 14 蒸馏

- [TextBrewer](https://github.com/airaria/TextBrewer)：A PyTorch-based knowledge distillation toolkit for natural language processing
- [KD_Lib](https://github.com/SforAiDl/KD_Lib)：A Pytorch Knowledge Distillation library for benchmarking and extending works in the domains of Knowledge Distillation, Pruning, and Quantization.
- [RepDistiller](https://github.com/HobbitLong/RepDistiller)：[ICLR 2020] Contrastive Representation Distillation (CRD), and benchmark of recent knowledge distillation methods
- [KD_SRRL](https://github.com/jingyang2017/KD_SRRL)：Paper. Knowledge distillation via softmax regression representation learning



##### 15 对话

- [DeepPavlov](https://github.com/deepmipt/DeepPavlov)：An open source library for deep learning end-to-end dialog systems and chatbots.
- [ConvLab-2](https://github.com/thu-coai/ConvLab-2)：ConvLab-2: An Open-Source Toolkit for Building, Evaluating, and Diagnosing Dialogue Systems
- [rasa-chatbot](https://github.com/samik-saha/rasa-chatbot)：Sample chatbot with rasa stack
- [nezha_gpt_dialog](https://github.com/bojone/nezha_gpt_dialog)
- [DialoGPT](https://github.com/microsoft/DialoGPT)：Large-scale pretraining for dialogue
- [CDial-GPT](https://github.com/thu-coai/CDial-GPT)：A Large-scale Chinese Short-Text Conversation Dataset and Chinese pre-training dialog models
- 【工具】[mirai](https://github.com/mamoe/mirai)：高效率 QQ 机器人框架 / High-performance bot framework for Tencent QQ
- [unit-dmkit](https://github.com/baidu/unit-dmkit): DMKit作为UNIT的开源对话管理模块，可以无缝对接UNIT的理解能力，并赋予开发者多状态的复杂对话流程管理能力，还可以低成本对接外部知识库，迅速丰富话术信息量
- [chat](https://github.com/Decalogue/chat)：基于自然语言理解与机器学习的聊天机器人，支持多用户并发及自定义多轮对话。对知识图谱以及 KBQA 感兴趣，想从0开始构建自己的知识图谱
- [SMP2018](https://github.com/wangle1218/SMP2018)：SMP2018中文人机对话技术评测（ECDT）
- [ GPT2-chitchat](https://github.com/yangjianxin1/GPT2-chitchat)：GPT2 for Chinese chitchat/用于中文闲聊的GPT2模型(实现了DialoGPT的MMI思想)



##### 16 指代消解

- [hobbs](https://github.com/cmward/hobbs)：Implementation of Hobbs' algorithm for coreference resolution in python

##### 17 主题

- [microsoft / LightLDA](https://github.com/microsoft/LightLDA)

##### 18 自动机

- [automata](https://github.com/caleb531/automata)：A Python library for simulating finite automata, pushdown automata, and Turing machines

##### 19 阅读理解

- [SDNet](https://github.com/microsoft/SDNet)
- [luke](https://github.com/studio-ousia/luke)：LUKE -- Language Understanding with Knowledge-based Embeddings
- [SogouMRCToolkit](https://github.com/sogou/SogouMRCToolkit)： fast and efficient development of modern machine comprehension models, including both published models and original prototypes

##### 20 数据增强

- [Cutoff](https://github.com/dinghanshen/Cutoff)：Cutoff data augmentation approach for NLP

##### 21 Prompt

- [PromptPapers](https://github.com/thunlp/PromptPapers)：Must-read papers on prompt-based tuning for pre-trained language models.
- [autoprompt](https://github.com/ucinlp/autoprompt)：AutoPrompt: Automatic Prompt Construction for Masked Language Models.
- 

---

#### 推荐系统

1. **[faiss](https://github.com/facebookresearch/faiss)**：A library for efficient similarity search and clustering of dense vectors.  -- Linux
2. [StarSpace](https://github.com/facebookresearch/StarSpace)：Learning embeddings for classification, retrieval and ranking.
3. [pytorch-fm](https://github.com/rixwew/pytorch-fm)：Factorization Machine models in PyTorch
4. [tensorflow](https://github.com/tensorflow)/**[recommenders](https://github.com/tensorflow/recommenders)**: TensorFlow Recommenders is a library for building recommender system models using TensorFlow.
5. [NEWS-RECOMMENDATION](https://github.com/wj19971997/NEWS-RECOMMENDATION)：简单demo
6. [GrowNet](https://github.com/sbadirli/GrowNet)：Gradient Boosting Neural Networks: GrowNet

---

#### 相似性

1. [milvus](https://github.com/milvus-io/milvus)：An open source vector similarity search engine -- Linux
2. [faiss](https://github.com/facebookresearch/faiss)：A library for efficient similarity search and clustering of dense vectors.  -- Linux
3. [annoy](https://github.com/spotify/annoy):  Approximate Nearest Neighbors in C++/Python optimized for memory usage and loading/saving to disk
4. [Scann](https://github.com/google-research/google-research/tree/master/scann)：ScaNN (Scalable Nearest Neighbors) is a method for efficient vector similarity search at scale. [lecture](https://slideslive.com/38928419/accelerating-largescale-inference-with-anisotropic-vector-quantization)

---

#### 语音

1. [ASRT_SpeechRecognition](https://github.com/nl8590687/ASRT_SpeechRecognition)：A Deep-Learning-Based Chinese Speech Recognition System 基于深度学习的中文语音识别系统
2. [speechT](https://github.com/timediv/speechT): An opensource speech-to-text software written in tensorflow
3. [TensorflowTTS](https://github.com/dathudeptrai/TensorflowTTS)：TensorflowTTS: Real-Time State-of-the-art Speech Synthesis for Tensorflow 2
4. [DeepSpeechRecognition](https://github.com/audier/DeepSpeechRecognition)：A Chinese Deep Speech Recognition System 包括基于深度学习的声学模型和基于深度学习的语言模型
5. [audio-pretrained-model](https://github.com/balavenkatesh3322/audio-pretrained-model)：A collection of Audio and Speech pre-trained models.
6. [pyannote-audio](https://github.com/pyannote/pyannote-audio)：Neural building blocks for speaker diarization: speech activity detection, speaker change detection, overlapped speech detection, speaker embedding
7. [Kersa-Speaker-Recognition](https://github.com/yeyupiaoling/Kersa-Speaker-Recognition)：基于Kersa实现的声纹识别模型
8. [Transformer-TTS](https://github.com/Deepest-Project/Transformer-TTS)：Implementation of "FastSpeech: Fast, Robust and Controllable Text to Speech"
9. [kaldi](https://github.com/kaldi-asr/kaldi)：kaldi-asr/kaldi is the official location of the Kaldi project.
10. [espnet](https://github.com/espnet/espnet)：End-to-End Speech Processing Toolkit
11. [MockingBird](https://github.com/babysor/MockingBird): AI拟声: 5秒内克隆您的声音并生成任意语音内容

---

#### GAN

1. [GAN-ZOO：A list of all named GANs!](https://github.com/hindupuravinash/the-gan-zoo)
2. [StarGAN](https://github.com/yunjey/stargan)
3. [iGAN: Interactive Image Generation via Generative Adversarial Networks](https://github.com/junyanz/iGAN)
4. [CycleGAN and pix2pix in PyTorch image-to-image translation](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)
5. [U-GAT-IT用小姐姐自拍，生成二次元萌妹子，神情高度还原，反过来也可以](https://github.com/znxlwm/UGATIT-pytorch  https://github.com/taki0112/UGATIT)
6. [SeqGAN](https://github.com/LantaoYu/SeqGAN)： https://github.com/suragnair/seqGAN      https://github.com/ChenChengKuan/SeqGAN_tensorflow 
7. [deepgenerativemodels / notes](https://github.com/deepgenerativemodels/notes)
8. [sngan_projection](https://github.com/pfnet-research/sngan_projection)：GANs with spectral normalization and projection discriminator
9. [gan](https://github.com/tensorflow/gan)：Tooling for GANs in TensorFlow
10. [AnimeGAN](https://github.com/TachibanaYoshino/AnimeGAN)： AnimeGAN for fast photo animation ! 
11. [BigGAN](https://github.com/ajbrock/biggan-pytorch)
12. [first-order-model](https://github.com/AliaksandrSiarohin/first-order-model)：图片动画化
13. [stargan-v2](https://github.com/clovaai/stargan-v2)：StarGAN v2 - Official PyTorch Implementation (CVPR 2020)
14. [UGATIT-pytorch](https://github.com/znxlwm/UGATIT-pytorch)：风格转换. Official PyTorch implementation of U-GAT-IT: Unsupervised Generative Attentional Networks with Adaptive Layer-Instance Normalization for Image-to-Image Translation

---

#### CV

[CV-pretrained-model](https://github.com/balavenkatesh3322/CV-pretrained-model)：A collection of computer vision pre-trained models.

[腾讯优图开源项目](https://github.com/TencentYoutuResearch)

[Dlib](https://github.com/davisking/dlib)：making real world machine learning and data analysis applications in C++



##### 图像识别与分类

1. [图片搜索和分析](https://github.com/AKSHAYUBHAT/DeepVideoAnalytics)

2. [DBoW2](https://github.com/dorian3d/DBoW2)：Enhanced hierarchical bag-of-word library for C++

3. [Real-time face detection and emotion/gender classification ](https://github.com/oarriaga/face_classification)

4. [人脸识别：The world's simplest facial recognition api for Python and the command line](https://github.com/ageitgey/face_recognition)

5. [TF_FLAME](https://github.com/TimoBolkart/TF_FLAME)：Example Tensorflow code for the FLAME face model 

6. [DeepFaceLab_Colab](https://github.com/dream80/DeepFaceLab_Colab)：[https://www.deepfaker.xyz](https://www.deepfaker.xyz/) -- NOTE：With colab you can use tesla P100 for free. Of course there are some restrictions

7. [EasyOCR](https://github.com/JaidedAI/EasyOCR)：Ready-to-use OCR with 80+ supported languages and all popular writing scripts including Latin, Chinese, Arabic, Devanagari, Cyrillic and etc.

8. **[libfacedetection](https://github.com/ShiqiYu/libfacedetection)**：: face detection in images. The face detection speed can reach 1000FPS.

9. [抠图：PyMatting: A Python Library for Alpha Matting](https://github.com/pymatting/pymatting)

10. [TransFG](https://github.com/TACJu/TransFG)：A Transformer Architecture for Fine-grained Recognition

11. [bottleneck-transformer-pytorch](https://github.com/lucidrains/bottleneck-transformer-pytorch)：SotA visual recognition model with convolution + attention that outperforms EfficientNet and DeiT in terms of performance-computes trade-off, in Pytorch

12. [deep-learning-for-image-processing](https://github.com/WZMIAOMIAO/deep-learning-for-image-processing)：deep learning for image processing including classification and object-detection etc.

13. [DEKR](https://github.com/HRNet/DEKR)：This is an official implementation of our CVPR 2021 paper "Bottom-Up Human Pose Estimation Via Disentangled Keypoint Regression" (https://arxiv.org/abs/2104.02300)

14. [mmpose](https://github.com/open-mmlab/mmpose)：OpenMMLab Pose Estimation Toolbox and Benchmark.

    

##### opencv

1. [learnopencv](https://github.com/spmallick/learnopencv): Learn OpenCV : C++ and Python Examples



openvino

1. [openvino_tensorflow](https://github.com/openvinotoolkit/openvino_tensorflow): OpenVINO™ integration with TensorFlow. [简短介绍](https://mp.weixin.qq.com/s?__biz=MzI5MDUyMDIxNA%3D%3D&abtest_cookie=AAACAA%3D%3D&ascene=56&chksm=ec1d37d5db6abec3d18567a2e43d53746fb88c73cd9d0182ff2791e193027e17a434b208f28a&clicktime=1630216035&devicetype=android-29&enterid=1630216035&exportkey=AyFWfNneyqVjLYNxYGEFiWI%3D&idx=1&lang=en&mid=2247572012&nettype=WIFI&pass_ticket=33lev6IS81X7EXB%2FIB4rKQ%2BaTeByxSTzjvfjcyi1NJRH8mbaydx4Y%2Bem%2BmoWOn1r&scene=90&sessionid=1630215765&sn=d685084cc88c0a6d8afeb7b168ed68b0&subscene=93&utm_source=pocket_mylist&version=28000a3d&wx_header=1)



##### 目标检测

1. [pytorch-YOLOv4](https://github.com/Tianxiaomo/pytorch-YOLOv4)：PyTorch ,ONNX and TensorRT implementation of YOLOv4
2. [yolov5](https://github.com/ultralytics/yolov5)：YOLOv5 in PyTorch > ONNX > CoreML > iOS
3. [deep_learning_object_detection](https://github.com/hoya012/deep_learning_object_detection)：A paper list of object detection using deep learning.
4. [deepdetect](https://github.com/jolibrain/deepdetect)：Deep Learning API and Server in C++11 support for Caffe, Caffe2, PyTorch,TensorRT, Dlib, NCNN, Tensorflow, XGBoost and TSNE
5. [ mmdetection](https://github.com/open-mmlab/mmdetection)：OpenMMLab Detection Toolbox and Benchmark
6. [FaceBoxes.PyTorch](https://github.com/zisianw/FaceBoxes.PyTorch)：A PyTorch Implementation of FaceBoxes
7. [openpose](https://github.com/CMU-Perceptual-Computing-Lab/openpose)：OpenPose: Real-time multi-person keypoint detection library for body, face, hands, and foot estimation
8. [ Surface-Defect-Detection](https://github.com/Charmve/Surface-Defect-Detection)：open source dataset and important critical papers in the field of surface defect research
9. [ViT-pytorch](https://github.com/jeonsworld/ViT-pytorch): Pytorch reimplementation of the Vision Transformer (An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale)
10. [efficientnet-pytorch](https://github.com/katsura-jp/efficientnet-pytorch): PyTorch implementation of "EfficientNet", ICML 2019
11. [efficientnet](https://github.com/qubvel/efficientnet): Implementation of EfficientNet model. Keras and TensorFlow Keras.
12. [目标检测FCOS: Fully Convolutional One-Stage Object Detection (ICCV'19) ](https://github.com/tianzhi0549/FCOS)
13. [image-segmentation-keras](https://github.com/divamgupta/image-segmentation-keras)：Implementation of Segnet, FCN, UNet , PSPNet and other models in Keras
14. [YOLOF](https://github.com/chensnathan/YOLOF)：You Only Look One-level Feature (YOLOF), CVPR2021, Detectron2
15. [Ultra-Fast-Lane-Detection](https://github.com/cfzd/Ultra-Fast-Lane-Detection)：Ultra Fast Structure-aware Deep Lane Detection (ECCV 2020)
16. [LSPS](https://github.com/masabdi/LSPS)：Source code for "3D Hand Pose Estimation using Simulation and Partial-Supervision with a Shared Latent Space"
17. [nanodet](https://github.com/RangiLyu/nanodet): ⚡Super fast and lightweight anchor-free object detection model. 🔥Only 980 KB(int8) / 1.8MB (fp16) and run 97FPS on cellphone🔥
18. [U-2-Net](https://github.com/xuebinqin/U-2-Net)：paper in Pattern Recognition 2020: "U^2-Net: Going Deeper with Nested U-Structure for Salient Object Detection."



##### 医疗

1. [InnerEye-DeepLearning](https://github.com/microsoft/InnerEye-DeepLearning): Medical Imaging Deep Learning library to train and deploy models on Azure Machine Learning and Azure Stack. [intro](https://mp.weixin.qq.com/s/F8BPVfLAknAJI6vAcEtNNw)

##### 多模态

1. [microsoft](https://github.com/microsoft)/[psi](https://github.com/microsoft/psi)：an open, extensible framework for development and research of multimodal, integrative-AI systems.  【C#】
2. [ClipBERT](https://github.com/jayleicn/ClipBERT)：an efficient framework for end-to-end learning for image-text and video-text tasks.



##### 图像高清化/风格转换/老化照片处理

1. [pulse](https://github.com/adamian98/pulse)：Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models
2. [FastPhotoStyle](https://github.com/NVIDIA/FastPhotoStyle)：分割不同部分的转换，Nice output
3. [DeOldify](https://github.com/jantic/DeOldify)：A Deep Learning based project for colorizing and restoring old images
4. [图片修复](https://github.com/DmitryUlyanov/deep-image-prior)
5. [Code and data for paper "Deep Photo Style Transfer"](https://github.com/luanfujun/deep-photo-styletransfer)
6. [TensorFlow CNN for fast style transfer](https://github.com/lengstrom/fast-style-transfer)
7. [ALAE](https://github.com/podgorskiy/ALAE):  Adversarial Latent Autoencoders
8. [deep-daze](https://github.com/lucidrains/deep-daze)：Simple command line tool for text to image generation using OpenAI's CLIP and Siren



##### 数据增强

1. [fast-autoaugment](https://github.com/kakaobrain/fast-autoaugment)：Official Implementation of 'Fast AutoAugment' in PyTorch.
2. [zao-](https://github.com/qiucheng025/zao-)：AI技术换脸源码
3. [AutoAugment](https://github.com/DeepVoltaire/AutoAugment)：Unofficial implementation of the ImageNet, CIFAR 10 and SVHN Augmentation Policies learned by AutoAugment using pillow
4. [albumentations](https://github.com/albumentations-team/albumentations): Fast image augmentation library and easy to use wrapper around other libraries
5. [imgaug](https://github.com/aleju/imgaug)：Image augmentation for machine learning experiments.
6. [AugLy](https://github.com/facebookresearch/AugLy)：A data augmentations library for audio, image, text, and video.



---

#### Reinforcement Learning

1. [算法、讲义、练习](https://github.com/dennybritz/reinforcement-learning)：Implementation of Reinforcement Learning Algorithms
2. [RLexample](https://github.com/cuhkrlcourse/RLexample)：basic examples of playing with RL
3. [DeepRL-Tutorials](https://github.com/cuhkrlcourse/DeepRL-Tutorials)：Contains high quality implementations of Deep Reinforcement Learning algorithms written in PyTorch
4. [ierg5350-assignment](https://github.com/cuhkrlcourse/ierg5350-assignment)：assignments of our reinforcement learning (RL) course.
5. [TD3](https://github.com/sfujim/TD3)：Author's PyTorch implementation of TD3 for OpenAI gym tasks. Nice code style and quality👍
6. [baby-a3c](https://github.com/greydanus/baby-a3c): A high-performance Atari A3C agent in 180 lines of PyTorch
7. [pytorch-a2c-ppo-acktr-gail](https://github.com/ikostrikov/pytorch-a2c-ppo-acktr-gail): PyTorch implementation of Advantage Actor Critic (A2C), Proximal Policy Optimization (PPO), Scalable trust-region method for deep reinforcement learning using Kronecker-factored approximation (ACKTR) and Generative Adversarial Imitation Learning (GAIL).
8. [NeuronDance / DeepRL: Deep Reinforcement Learning Lab](https://github.com/NeuronDance/DeepRL)
9. [awesome-monte-carlo-tree-search-papers](https://github.com/benedekrozemberczki/awesome-monte-carlo-tree-search-papers)
10. [advanced-deep-learning-and-reinforcement-learning-deepmind](https://github.com/Zhenye-Na/advanced-deep-learning-and-reinforcement-learning-deepmind)：UCL & DeepMind | YouTube videos 👉 [https://www.youtube.com/playlist?list…](https://www.youtube.com/playlist?list=PLqYmG7hTraZDNJre23vqCGIVpfZ_K2RZs)
11. [ AlphaZero_Gomoku](https://github.com/junxiaosong/AlphaZero_Gomoku)：An implementation of the AlphaZero algorithm for Gomoku (also called Gobang or Five in a Row)
12. [reinforcement-learning-an-introduction](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction)：强化学习导论配套代码库
13. [PARL](https://github.com/PaddlePaddle/PARL)：PARL A high-performance distributed training framework for Reinforcement Learning
14. [trfl](https://github.com/deepmind/trfl)：TensorFlow Reinforcement Learning
15. [tianshou](https://github.com/thu-ml/tianshou)：An elegant PyTorch deep reinforcement learning library.

---

#### 知识图谱

1. [农业知识图谱(AgriKG) ](https://github.com/qq547276542/Agriculture_KnowledgeGraph)
2. [KGQA-Based-On-medicine](https://github.com/YeYzheng/KGQA-Based-On-medicine)
3. [KEQA_WSDM19](https://github.com/xhuang31/KEQA_WSDM19)
4. [transE](https://github.com/wuxiyu/transE)
5. [KB2E：thunlp](https://github.com/thunlp/KB2E)
6. [tianchi_nl2sql: 首届中文NL2SQL挑战赛决赛第3名方案+代码](https://github.com/beader/tianchi_nl2sql)
7. [CCKS 2019 中文知识图谱问答数据集](https://biendata.com/competition/ccks_2019_6/data/)
8. [knowledge-graph](https://github.com/kyzhouhzau/knowledge-graph)： a QA Demo based on KG! use scrapy and jena.
9. [ONEPIECE-KG](https://github.com/mrbulb/ONEPIECE-KG)： a knowledge graph project for ONEPIECE /《海贼王》知识图谱
10. [K-BERT](https://github.com/autoliuweijie/K-BERT)：Sorce code and datasets for ["K-BERT: Enabling Language Representation with Knowledge Graph"](https://aaai.org/Papers/AAAI/2020GB/AAAI-LiuW.5594.pdf)
11. [scikit-kge](https://github.com/mnick/scikit-kge)：Python library to compute knowledge graph embeddings
12. [Financial-Knowledge-Graphs](https://github.com/jm199504/Financial-Knowledge-Graphs)：小型金融知识图谱构建流程
13. [KG-demo-for-movie](https://github.com/SimmerChan/KG-demo-for-movie)：从无到有构建一个电影知识图谱，并基于该KG，开发一个简易的KBQA程序
14. [pykg2vec](https://github.com/Sujit-O/pykg2vec)：Python library for knowledge graph embedding and representation learning.
15. [text_to_knowledge](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/examples/text_to_knowledge): 解语（Text to Knowledge）是首个覆盖中文全词类的知识库（百科知识树）及知识标注框架，拥有可描述所有中文词汇的词类体系、中文知识标注工具集，以及更适用于中文挖掘任务的预训练语言模型。paddlenlp子项目，没有开源。



---

#### 深度贝叶斯/概率

1. [Deep universal probabilistic programming with Python and PyTorch](https://github.com/pyro-ppl/pyro)
2. [ Python library for probabilistic modeling, inference, and criticism ](http://edwardlib.org/)
3. [ A Library for Bayesian Deep Learning, Generative Models, Based on Tensorflow ](https://github.com/thu-ml/zhusuan)

---

#### Capsule Net

1. [CapsNet-Tensorflow](https://github.com/naturomics/CapsNet-Tensorflow)
2. [CapsNet-resource](https://github.com/XifengGuo/CapsNet-Keras)

---

#### 自动驾驶

1. [ Udacity Self-Driving Car Engineer Nanodegree projects. ](https://github.com/ndrplz/self-driving-car)
2. [MIT Deep Self Driving](https://www.youtube.com/watch?v=-6INDaLcuJY&list=PLrAXtmErZgOeiKm4sgNOknGvNjby9efdf)

---

#### 机器人

1. [AtsushiSakai / PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics)

---

#### Contrastive Learning

1. [PyContrast](https://github.com/HobbitLong/PyContrast)：PyTorch implementation of Contrastive Learning methods; List of awesome-contrastive-learning papers
2. [SimCSE](https://github.com/princeton-nlp/SimCSE)：SimCSE: Simple Contrastive Learning of Sentence Embeddings
3. [ConSERT](https://github.com/yym6472/ConSERT): ACL 2021 paper - ConSERT: A Contrastive Framework for Self-Supervised Sentence Representation Transfer
4. [pytorch-metric-learning](https://github.com/KevinMusgrave/pytorch-metric-learning): The easiest way to use deep metric learning in your application. 可直接使用的 NTXENT loss (InfoNCE) ，SupContrast loss等对比学习损失。



#### Adversarial Attack

1. [adversarial-robustness-toolbox](https://github.com/IBM/adversarial-robustness-toolbox)
2. [foolbox](https://github.com/bethgelab/foolbox)：fool neural networks
3. [cleverhans](https://github.com/tensorflow/cleverhans)：constructing attacks, building defenses, and benchmarking both
4. [FreeLB](https://github.com/zhuchen03/FreeLB)：Adversarial Training for Natural Language Understanding
5. [DefenseByAttack](https://github.com/a554b554/DefenseByAttack): Code for paper "One Man's Trash is Another Man's Treasure"



#### Multi-Task Learning

1. [fudan_mtl_reviews](https://github.com/FrankWork/fudan_mtl_reviews)：TensorFlow implementation of the paper `Adversarial Multi-task Learning for Text Classification`
2. https://decanlp.com/： The Natural Language Decathlon (decaNLP) is a new benchmark for studying general NLP models that can perform a variety of complex, natural language tasks. [decaNLP](https://github.com/salesforce/decaNLP)



#### 联邦学习

1. [ FedML-AI](https://github.com/FedML-AI)/**[FedML](https://github.com/FedML-AI/FedML)**：(PyTorch > 1.0) A Research-Oriented Federated Learning Library. Supporting distributed computing, mobile/IoT on-device training, and standalone simulation. [Intro](https://mp.weixin.qq.com/s/gPBK551W2lgX3gm7SUgH3Q)

#### 图网络

1. **[dgl](https://github.com/dmlc/dgl)**：Python package built to ease deep learning on graph, on top of existing DL frameworks.
2. [AutoGL](https://github.com/THUMNLab/AutoGL)：An autoML framework & toolkit for machine learning on graphs.
3. [graph_nets](https://github.com/deepmind/graph_nets)：Build Graph Nets in Tensorflow

---

### 框架实践

1. [DeepLearningExamples](https://github.com/NVIDIA/DeepLearningExamples)：Deep Learning Examples
2. [jax](https://github.com/google/jax)：Composable transformations of Python+NumPy programs: differentiate, vectorize, JIT to GPU/TPU
3. **[PyCandle](https://github.com/johnny-richards/PyCandle)**：A numpy and cpu based neural network tool. For those who intend to learn more about the details of how a neural network works.
4. 【\**】**[einops](https://github.com/arogozhnikov/einops)**：Deep learning operations reinvented (for pytorch, tensorflow, chainer, gluon and others)。还在为tensor维度变化操作的语法发愁吗？试试这个说人话的package
5. [tinygrad](https://github.com/geohot/tinygrad)：You like pytorch? You like micrograd? You love tinygrad! ❤️
6. [MatrixSlow](https://github.com/zackchen/MatrixSlow)：A simple deep learning framework in pure python for purpose of learning in DL
7. [best-of-ml-python](https://github.com/ml-tooling/best-of-ml-python)：🏆 A ranked list of awesome machine learning Python libraries.
8. [pytorch-loss](https://github.com/CoinCheung/pytorch-loss)：label-smooth, amsoftmax, focal-loss, triplet-loss, lovasz-softmax ...
9. [pytorch-optimizer](https://github.com/jettify/pytorch-optimizer)：torch-optimizer -- collection of optimizers for Pytorch

#### Tensorflow

1. [Effective TensorFlow](https://github.com/vahidk/EffectiveTensorflow)
2. [简明TF2](https://tf.wiki/zh_hans/)   [tensorflow2中文教程](https://github.com/czy36mengfei/tensorflow2_tutorials_chinese)
3. [eat_tensorflow2_in_30_days](https://github.com/lyhue1991/eat_tensorflow2_in_30_days)
4. [various deep learning architectures, models, and tips](https://github.com/rasbt/deeplearning-models)
5. [TensorFlow实战书codes](https://github.com/caicloud/tensorflow-tutorial)
6. [Deep Learning with Python Keras](https://github.com/fchollet/deep-learning-with-python-notebooks)
7. [Hands-on Machine Learning with Scikit-Learn and TensorFlow](https://github.com/ageron/handson-ml)
8. [Neural Machine Translation (seq2seq) Tutorial](https://github.com/tensorflow/nmt)
9. [TFLearn: Deep learning library featuring a higher-level API for TensorFlow.](https://github.com/tflearn/tflearn)
10. [Tensor2Tensor：deep learning models and datasets designed to make deep learning more accessible and accelerate ML research](https://github.com/tensorflow/tensor2tensor)
11. [Sonnet： is a library built on top of TensorFlow for building complex neural networks.](https://github.com/deepmind/sonnet)
12. [KDD2019 Deep Learning for NLP with Tensorflow hands-on](https://github.com/tensorflow/workshops/tree/master/kdd2019)
13. [TensorFlow Tutorial and Examples for Beginners (support TF v1 & v2)](https://github.com/aymericdamien/TensorFlow-Examples)
14. [简单粗暴 TensorFlow 2.0](https://github.com/snowkylin/tensorflow-handbook)
15. [ TensorFlow for Deep Learning Research. ](https://github.com/chiphuyen/stanford-tensorflow-tutorials)  [课件](https://web.stanford.edu/class/cs20si/2017/syllabus.html)
16. **[ tensor2tensor](https://github.com/tensorflow/tensor2tensor)**
17. [tensorpack](https://github.com/tensorpack/tensorpack)：A Neural Net Training Interface on TensorFlow, with focus on speed + flexibility
18. [larq](https://github.com/larq/larq)：An Open-Source Library for Training Binarized Neural Networks
19. [keras-cosine-annealing](https://github.com/4uiiurz1/keras-cosine-annealing)

##### C++

1. [hello_tf_c_api](https://github.com/Neargye/hello_tf_c_api)：Neural Network TensorFlow C API
2. [tensorflow_cc](https://github.com/FloopCZ/tensorflow_cc)：Build and install TensorFlow C++ API library.
3. [tiny-dnn](https://github.com/tiny-dnn/tiny-dnn)：header only, dependency-free deep learning framework in C++14

#### Pytorch

1. [Fairseq(-py) is a sequence modeling toolkit](https://github.com/pytorch/fairseq)
2. [A practical approach to machine learning pytorch](https://github.com/GokuMohandas/practicalAI)
3. [**pix2pixHD**](https://github.com/NVIDIA/pix2pixHD)
4. [实战Deep Architectures PyTorch：ppt](https://docs.google.com/presentation/d/1MFhet5q-SIPqc_54CXWiBvlT9OdSi6P8kpkm6IxuyEM/edit#slide=id.g5540a1077d_0_502)
5. [动手学深度学习Pytorch版](https://github.com/dsgiitr/d2l-pytorch)
6. [A very simple framework for state-of-the-art Natural Language Processing (NLP)](https://github.com/zalandoresearch/flair)
7. [pytorch-lightning：pytorch + TPU](https://github.com/PyTorchLightning/pytorch-lightning)
8. [Awesome-pytorch-list](https://github.com/bharathgs/Awesome-pytorch-list)：A comprehensive list of pytorch related content on github,such as different models,implementations,helper libraries,tutorials etc.
9. [DeepNLP-models-Pytorch](https://github.com/DSKSD/DeepNLP-models-Pytorch)：Pytorch implementations of various Deep NLP models in cs-224n(Standford Univ)
10. [pytorch-Deep-Learning](https://github.com/Atcold/pytorch-Deep-Learning): Deep Learning (with PyTorch)
11. [serve](https://github.com/pytorch/serve)：Model Serving on PyTorch
12. [pytorch-seq2seq](https://github.com/bentrevett/pytorch-seq2seq)：Tutorials on implementing a few sequence-to-sequence (seq2seq) models with PyTorch and TorchText.
13. [pycandle](https://github.com/cschoeller/pycandle)：PyCandle is a lightweight library for pytorch that makes running experiments easy, structured, repeatable and avoids boilerplate code.
14. [AI-Art](https://github.com/Adi-iitd/AI-Art)：PyTorch implementation of Neural Style Transfer, Pix2Pix, CycleGAN, and Deep Dream!
15. [entmax](https://github.com/deep-spin/entmax)：The entmax mapping and its loss, a family of sparse softmax alternatives.
16. [Adabelief-Optimizer](https://github.com/juntang-zhuang/Adabelief-Optimizer)：NeurIPS 2020 Spotlight "AdaBelief Optimizer: Adapting stepsizes by the belief in observed gradients"
17. [pytorch-optimizer](https://github.com/jettify/pytorch-optimizer)：torch-optimizer -- collection of optimizers for Pytorch
18. [examples](https://github.com/pytorch/examples): A set of examples around pytorch in Vision, Text, Reinforcement Learning, etc.
19. [computervision-recipes](https://github.com/microsoft/computervision-recipes)：Best Practices, code samples, and documentation for Computer Vision.
20. [nlp-recipes](https://github.com/microsoft/nlp-recipes)：Natural Language Processing Best Practices & Examples
21. [pymde](https://github.com/cvxgrp/pymde)：Python library for computing vector embeddings for finite sets of items, such as images, biological cells, nodes in a network
22. [mmf](https://github.com/facebookresearch/mmf)：MMF is a modular framework for vision and language multimodal research from Facebook AI Research.
23. [examples](https://github.com/pytorch/examples): A set of examples around pytorch in Vision, Text, Reinforcement Learning, etc.
24. [pytorch-image-models](https://github.com/rwightman/pytorch-image-models): PyTorch image models, scripts, pretrained weights -- (SE)ResNet/ResNeXT, DPN, EfficientNet, MixNet, MobileNet-V3/V2, MNASNet, Single-Path NAS, FBNet, and more
25. [pytorch-cosine-annealing-with-warmup](https://github.com/katsura-jp/pytorch-cosine-annealing-with-warmup)
26. [fastmoe](https://github.com/laekov/fastmoe)：A fast Mixture of Experts（MoE） impl for PyTorch
27. [annotated_deep_learning_paper_implementations](https://github.com/labmlai/annotated_deep_learning_paper_implementations)
28. [External-Attention-pytorch](https://github.com/xmu-xiaoma666/External-Attention-pytorch)：🍀 Pytorch implementation of various Attention Mechanisms, MLP, Re-parameter, Convolution, which is helpful to further understand papers.
29. [torch-toolbox](https://github.com/PistonY/torch-toolbox)：ToolBox to make using Pytorch much easier. Mainly for CV.
30. [tianshou](https://github.com/thu-ml/tianshou)：An elegant PyTorch deep reinforcement learning library.

#### MxNet

1. [动手学深度学习](https://github.com/d2l-ai/d2l-zh)
2. [autogluon](https://github.com/awslabs/autogluon)：AutoGluon: AutoML for Text, Image, and Tabular Data

#### Spark

1. [sparkflow：Easy to use library to bring Tensorflow on Apache Spark](https://github.com/lifeomic/sparkflow)
2. [spark-nlp：State of the Art Natural Language Processing](https://github.com/JohnSnowLabs/spark-nlp)
3. [spark-deep-learning：Deep Learning Pipelines for Apache Spark](https://github.com/databricks/spark-deep-learning)
4. [Data-Science-with-Spark](https://github.com/anindya-saha/Data-Science-with-Spark)

#### Ray

1. [ray](https://github.com/ray-project/ray)：A fast and simple framework for building and running distributed applications. Ray is packaged with RLlib, a scalable reinforcement learning library, and Tune, a scalable hyperparameter tuning library. 【actor模式】

#### Lasagne

1. [Lasagne](http://lasagne.readthedocs.io/)：Lasagne is a lightweight library to build and train neural networks in Theano.

#### MindSpore

1. [mindspore](https://github.com/mindspore-ai/mindspore)： https://www.mindspore.cn/docs/zh-CN/master/architecture.html

#### MegEngine

1. [MegEngine](https://github.com/MegEngine/MegEngine): https://megengine.org.cn/quick-start/

#### 基础

1. [fastAI作业](https://github.com/msatlihan/fast-ai-assignments)

---

### 模型优化

1. [NVIDIA TensorRT doc](https://developer.nvidia.com/tensorrt) [GitHub](https://github.com/NVIDIA/TensorRT)
2. [hyperopt / hyperopt](https://github.com/hyperopt/hyperopt)：超参数调整
3. [hyperparameter_hunter](https://github.com/HunterMcGushion/hyperparameter_hunter)：Automatically save and learn from Experiment results, leading to long-term, persistent optimization that remembers all your tests.
4. [microsoft / DeepSpeed](https://github.com/microsoft/DeepSpeed)：library that makes distributed training easy, efficient, and effective.
5. [apex](https://github.com/NVIDIA/apex)：A PyTorch Extension: Tools for easy mixed precision and distributed training in Pytorch
6. [model-optimization](https://github.com/tensorflow/model-optimization)：A toolkit to optimize ML models for deployment for Keras and TensorFlow, including quantization and pruning.
7. [keras-tuner](https://github.com/keras-team/keras-tuner)：Hyperparameter tuning for humans
8. [optuna](https://github.com/optuna/optuna)：A hyperparameter optimization framework

### 模型训练部署

[机器学习系统设计](https://github.com/chiphuyen/machine-learning-systems-design)

#### 部署

1. [BentoML](https://github.com/bentoml/BentoML)：Model Serving Made Easy 

1. [Turi Create simplifies the development of custom machine learning models](https://github.com/apple/turicreate)

2. [cortexlabs / cortex](https://github.com/cortexlabs/cortex)：模型部署 【相关项目：[cortex: A horizontally scalable, highly available, multi-tenant, long term Prometheus. ](https://github.com/cortexproject/cortex)】

3. [bert-classification-tf-serving](https://github.com/nghuyong/bert-classification-tf-serving)

4. [Deep-Learning-in-Production](https://github.com/ahkarami/Deep-Learning-in-Production)：deploying deep learning-based models in production.

5. [***ray](https://github.com/ray-project/ray)：A fast and simple framework for building and running distributed applications. Ray is packaged with RLlib, a scalable reinforcement learning library, and Tune, a scalable hyperparameter tuning library. [Serve Video](https://www.youtube.com/watch?v=rFZhwsSxZ_Q&list=PLYx7XA2nY5GejOB1lsvriFeMytD1-VS1B&index=7) [Documents](https://docs.ray.io/en/master/serve/#installation)<img src="pic/GitHub收集项目维护_pic/image-20200707121042390.png" alt="image-20200707121042390 " style="zoom:50%;" />

   <img src="pic/GitHub收集项目维护_pic/image-20200707122147905.png" alt="image-20200707122147905" style="zoom:67%;" /> process to process 跳过调度，增加性能
   
7. [fiber](https://github.com/uber/fiber)：Distributed Computing for AI Made Simple

8. [model_deployment](https://github.com/balavenkatesh3322/model_deployment)：A collection of model deployment library and technique.

9. [jina](https://github.com/jina-ai/jina)：An easier way to build **neural search** in the cloud

10. [plaidml](https://github.com/plaidml/plaidml)：PlaidML is a framework for making deep learning work everywhere.

11. [streamlit](https://github.com/streamlit/streamlit)：Streamlit — The fastest way to build data apps in Python

12. [kubeflow](https://github.com/kubeflow/kubeflow): Machine Learning Toolkit for Kubernetes

13. [waitress](https://github.com/Pylons/waitress)：Waitress - A WSGI server for Python 2 and 3

14. [mlflow](https://github.com/mlflow/mlflow): Open source platform for the machine learning lifecycle

15. [zenml](https://github.com/maiot-io/zenml)：Bring Zen to your ML with reproducible pipelines

16. [cs329s-ml-deployment-tutorial](https://github.com/mrdbourke/cs329s-ml-deployment-tutorial)：Code and files to go along with CS329s machine learning model deployment tutorial.

17. [nboost](https://github.com/koursaros-ai/nboost)：deploying transformer models to improve the relevance of search results on different platforms (i.e. Elasticsearch)

18. [object_detector_app](https://github.com/datitran/object_detector_app)：Real-Time Object Recognition App with Tensorflow and OpenCV

19. [uwsgi-nginx-flask-docker](https://github.com/tiangolo/uwsgi-nginx-flask-docker)：Docker image with uWSGI and Nginx for Flask applications in Python running in a single container. Optionally with Alpine Linux.

20. [Modin: Speed up your Pandas workflows by changing a single line of code](https://github.com/modin-project/modin)

21. [nameko](https://github.com/nameko/nameko)：Python framework for building microservices

22. [metaflow](https://github.com/Netflix/metaflow)：Build and manage real-life data science projects with ease.

23. [NLPStreamlit](https://github.com/RamVegiraju/NLPStreamlit)：简易部署 Sentiment Analysis, Named Entity Recognition (NER), and Text Summarization 等网页应用。

#### 训练

1. [BytePS：A high performance and general PS framework for distributed training](https://github.com/bytedance/byteps)
2. [分布式训练框架：The goal of Horovod is to make distributed Deep Learning fast and easy to use](https://github.com/horovod/horovod)
3. [Unity Machine Learning Agents Toolkit 训练游戏AI](https://github.com/Unity-Technologies/ml-agents)
4. [***ray](https://github.com/ray-project/ray)：A fast and simple framework for building and running distributed applications. Ray is packaged with RLlib, a scalable reinforcement learning library, and Tune, a scalable hyperparameter tuning library
5. [cml](https://github.com/iterative/cml)：Continuous Machine Learning | CI/CD for ML，结果组织成网页分析
6. [fairscale](https://github.com/facebookresearch/fairscale)：PyTorch extensions for high performance and large scale training.
7. [replicate](https://github.com/replicate/replicate)：Version control for machine learning
8. [orchest](https://github.com/orchest/orchest)：Orchest is a tool for creating data science pipelines.
9. [trains](https://github.com/allegroai/trains)：Auto-Magical Experiment Manager & Version Control for AI 
10. [cleverhans](https://github.com/cleverhans-lab/cleverhans)：An adversarial example library for constructing attacks, building defenses, and benchmarking both
11. [docker-python](https://github.com/Kaggle/docker-python)：Kaggle Python docker image
12. [distribuuuu](https://github.com/BIGBALLON/distribuuuu)：The pure and clear PyTorch Distributed Training Framework.
13. [maggot](https://github.com/ex4sperans/maggot)：A lightweight python library that helps to keep track of numerical experiments
14. [rigl](https://github.com/google-research/rigl)：End-to-end training of sparse deep neural networks with little-to-no performance loss.  "Making All Tickets Winners"
15. [skweak](https://github.com/NorskRegnesentral/skweak):   A software toolkit for weak supervision applied to NLP tasks



### Transfer Learning

1. [Hands-On Transfer Learning with Python](https://github.com/dipanjanS/hands-on-transfer-learning-with-python)



### 多任务

1. [multi-task-learning-example](https://github.com/yaringal/multi-task-learning-example)
2. [mt-dnn](https://github.com/namisan/mt-dnn)：Multi-Task Deep Neural Networks for Natural Language Understanding



### 偏向研究

#### NLP

1. [awesome-nlp：研究进展、guides、工具包等](https://github.com/keon/awesome-nlp)
2. [track the progress in Natural Language Processing (NLP)]((https://github.com/sebastianruder/NLP-progress))
3. [中文自然语言处理 Chinese NLP：各种任务sota baseline](https://chinesenlp.xyz/#/docs/co-reference_resolution)
4. [funNLP：相关资源合集](https://github.com/fighting41love/funNLP)
5. [*sentence embeddings*: InferSent](https://github.com/facebookresearch/InferSent)
6. [nlg-eval: 评测指标](https://github.com/Maluuba/nlg-eval)
7. [百度对话系统](https://github.com/baidu/Dialogue)
8. [**AnyQ(ANswer Your Questions)**](https://github.com/baidu/AnyQ)： 开源项目主要包含面向FAQ集合的问答系统框架、文本语义匹配工具SimNet
9. [Rasa开源机器学习框架，用于自动化基于文本和语音的对话](https://github.com/RasaHQ/rasa)
10. [对话系统：sharing, training and evaluating dialogue models across many tasks.](https://github.com/facebookresearch/ParlAI)
11. [ Deep Generative Models for Natural Language Processing  Papers](https://github.com/FranxYao/Deep-Generative-Models-for-Natural-Language-Processing)
12. [Course materials for Georgia Tech CS 4650 and 7650, "Natural Language"](https://github.com/jacobeisenstein/gt-nlp-class)
13. [NLP-BERT--ChineseVersion](https://github.com/Y1ran/NLP-BERT--ChineseVersion): 谷歌自然语言处理模型BERT：论文解析与python代码
14. [MTBook](https://github.com/NiuTrans/MTBook)：《机器翻译：统计建模与深度学习方法》肖桐 朱靖波 著
15. [Leaderboards-for-Multi-Turn-Response-Selection](https://github.com/JasonForJoy/Leaderboards-for-Multi-Turn-Response-Selection)：provide the reader with a quick overview of benchmark datasets and the state-of-the-art studies on this task, which serves as a stepping stone for further research.
16. [BERT-Tickets](https://github.com/VITA-Group/BERT-Tickets)：BERT的进一步探究
17. **[awesome-papers](https://github.com/huggingface/awesome-papers)**：Papers & presentation materials from Hugging Face's internal science day

#### CV

1. [Convolution arithmetic卷积算法可视化解释](https://github.com/vdumoulin/conv_arithmetic)
2. [Recent Advances in Deep Learning for Object Detection](https://arxiv.org/abs/1908.03673v1)
3. [cnn-explainer](https://github.com/poloclub/cnn-explainer)：可视化cnn训练学习

#### 图网络

1. [A collection of important graph(Code)](https://github.com/benedekrozemberczki/awesome-graph-classification)
3. [Must-read papers on graph neural networks (GNN)](https://github.com/thunlp/GNNPapers)
3.  https://github.com/microsoft/tf-gnn-samples 
4. [spektral](https://github.com/danielegrattarola/spektral)：Graph Neural Networks with Keras and Tensorflow 2. 
5. [ littleballoffur](https://github.com/benedekrozemberczki/littleballoffur)：A NetworkX extension library for graph subsampling. 
6. [awesome-gcn](https://github.com/Jiakui/awesome-gcn)： resources for graph convolutional networks （图卷积神经网络相关资源）
7. [pytorch_geometric](https://github.com/rusty1s/pytorch_geometric)：Geometric Deep Learning Extension Library for PyTorch [https://pytorch-geometric.readthedocs…](https://pytorch-geometric.readthedocs.io/)

#### GAN

1. [Curated list of awesome GAN applications and demo](https://github.com/nashory/gans-awesome-applications)
2. 【book】[O'Reilly book 'Generative Deep Learning'](https://github.com/davidADSP/GDL_code)
3. [The classical paper list with code about generative adversarial nets](https://github.com/zhangqianhui/AdversarialNetsPapers)
4. [SeqGAN](https://github.com/LantaoYu/SeqGAN)  [seqGAN-Simplified](https://github.com/suragnair/seqGAN)
5. [super-resolution](https://github.com/krasserm/super-resolution): Tensorflow 2.x based implementation of EDSR, WDSR and SRGAN for single image super-resolution

#### 优化算法

1. [RAdam](https://github.com/LiyuanLucasLiu/RAdam)

#### Trading

1. [awesome-deep-trading](https://github.com/cbailes/awesome-deep-trading)

---

### Awesome

1. [awesome](https://github.com/sindresorhus/awesome): 全，Awesome lists about all kinds of interesting topics
2. [Awesome-win](https://github.com/Awesome-Windows/Awesome):  An awesome & curated list of best applications and tools for Windows.
3. [awesome-tensorflow](https://github.com/jtoy/awesome-tensorflow)：TensorFlow - A curated list of dedicated resources
4. [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning)：A curated list of awesome Deep Learning tutorials, projects and communities.
5. [awesome-nlp](https://github.com/keon/awesome-nlp)：A curated list of resources dedicated to Natural Language Processing (NLP)
6. [awesome-docker](https://github.com/veggiemonk/awesome-docker)：A curated list of Docker resources and projects
7. [Awesome-pytorch-list](https://github.com/bharathgs/Awesome-pytorch-list)：A comprehensive list of pytorch related content on github,such as different models,implementations,helper libraries,tutorials etc.
8. [Awesome-Chinese-NLP](https://github.com/crownpku/Awesome-Chinese-NLP)：中文自然语言处理相关资料
9. [open_model_zoo](https://github.com/openvinotoolkit/open_model_zoo)：Pre-trained Deep Learning models and demos (high quality and extremely fast)
10. https://modelzoo.co/
11. [awesome-bots](https://github.com/invocable/awesome-bots)：The most awesome list about bots
12. [Awesome-Chatbot](https://github.com/fendouai/Awesome-Chatbot)：Awesome Chatbot Projects,Corpus,Papers,Tutorials.Chinese Chatbot =>:
13. [awesome-mlops](https://github.com/visenger/awesome-mlops): A curated list of references for MLOps, 机器学习开发周期教程、视频、博客
14. [google-research / language](https://github.com/google-research/language)：Shared repository for open-sourced projects from the Google AI Language team.
15. [awesome-relation-extraction](https://github.com/roomylee/awesome-relation-extraction)：A curated list of awesome resources dedicated to Relation Extraction
16. [awesome-grounding](https://github.com/TheShadow29/awesome-grounding)：A curated list of research papers in grounding.

---

### 会议资源

1. [KDD2019 Hands-on Tutorials](https://www.kdd.org/kdd2019/hands-on-tutorials)

### 项目idea

1. [ Machine Learning, NLP, Vision, Recommender Systems Project Ideas](https://github.com/NirantK/awesome-project-ideas#text)
2. [数据竞赛Top解决方案开源整理](https://github.com/Smilexuhc/Data-Competition-TopSolution)
3. [Voice Conversion with Non-Parallel Data](https://github.com/andabi/deep-voice-conversion)
4. [语音转文字wave-net](https://github.com/buriburisuri/speech-to-text-wavenet)
5. [A TensorFlow implementation of Baidu's DeepSpeech architecture](https://github.com/mozilla/DeepSpeech)
6. [industry-machine-learning](https://github.com/firmai/industry-machine-learning)：A curated list of applied machine learning and data science notebooks and libraries across different industries.
7. [news-search-engine](https://github.com/01joy/news-search-engine)：新闻搜索引擎



---

## 3 机器学习

1. [awesome-mlops](https://github.com/visenger/awesome-mlops): A curated list of references for MLOps, 机器学习开发周期教程、视频、博客

   

### 开源工具

#### 算法包

1. [H2O documentation](http://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science.html)：H2O is an open source, in-memory, distributed, fast, and scalable machine learning and predictive analytics platform that allows you to build machine learning models on big data and provides easy productionalization of those models in an enterprise environment.
2. [vowpal_wabbit](https://github.com/VowpalWabbit/vowpal_wabbit)：a machine learning system which pushes the frontier of machine learning with techniques such as online, hashing, allreduce, reductions, learning2search, active, and interactive learning.
3. [XGBoost](https://github.com/dmlc/xgboost) repository
4. [LightGBM](https://github.com/Microsoft/LightGBM) repository
5. [cvxpy](https://github.com/cvxgrp/cvxpy)：A Python-embedded modeling language for convex optimization problems. 
6. [tpot](https://github.com/EpistasisLab/tpot)：A Python Automated Machine Learning tool that optimizes machine learning pipelines using genetic programming.
7. [production-tools](https://github.com/thuijskens/production-tools)：演示如何为数据科学项目设置工具的基本存储库，这些工具将帮助您编写更高质量的代码。
11. [scikit-multiflow](https://github.com/scikit-multiflow/scikit-multiflow)：A machine learning package for streaming data in Python. 流式数据输入进行训练
12. [igel](https://github.com/nidhaloff/igel)：a delightful machine learning tool that allows to train, test and use models without writing code.
13. [creme](https://github.com/creme-ml/creme)：Online machine learning in Python
15. [statsmodels](https://github.com/statsmodels/statsmodels)：statistical modeling and econometrics in Python
16. [xlearn](https://github.com/aksnzhy/xlearn)：High performance, easy-to-use, and scalable machine learning (ML) package, including linear model (LR), factorization machines (FM), and field-aware factorization machines (FFM) for Python and CLI
18. [GPy](https://github.com/SheffieldML/GPy)：Gaussian processes framework in python
19. [mlens](https://github.com/flennerhag/mlens)：ML-Ensemble – high performance ensemble learning
21. [Kats](https://github.com/facebookresearch/Kats)：[时序]analyze time series data, a lightweight, easy-to-use, generalizable, and extendable framework to perform time series analysis

#### 聚类

1. [spherecluster](https://github.com/jasonlaska/spherecluster)：Clustering routines for the unit sphere [blog](https://medium.com/@jaska_at_clara/simple-datetime-disambiguation-fd2374ce664a)
2. [brown-clustering](https://github.com/yangyuan/brown-clustering)：Brown clustering in Python. 词聚类
3. [lsystem_optimization](https://github.com/mzucker/lsystem_optimization)：Socially isolating through obsessive micro-optimization.

#### 特征

1. [cleanlab](https://github.com/cgnorthcutt/cleanlab)：Find label errors in datasets, weak supervision, and learning with noisy labels.
2. [boruta_py](https://github.com/scikit-learn-contrib/boruta_py)：Python implementations of the Boruta all-relevant feature selection method.
3. [*dabl](https://github.com/dabl/dabl)：Data Analysis Baseline Library ！[Document](https://dabl.github.io/dev/user_guide.html#philosophy) 
4. [mglearn](https://github.com/amueller/introduction_to_ml_with_python/tree/master/mglearn)：绘图函数包
5. [umap](https://github.com/lmcinnes/umap)：Uniform Manifold Approximation and Projection，like t-sne
6. [geomstats](https://github.com/geomstats/geomstats)：About Computations and statistics on manifolds with geometric structures.
7. [FEATHER](https://github.com/benedekrozemberczki/FEATHER)
8. [Mito](https://docs.trymito.io/getting-started/installing-mito)：像Excel一些样操作 pandas dataframe
9. [Pandas Profiling](https://pandas-profiling.github.io/pandas-profiling/docs/master/rtd/)：一键分析中小型 pandas dataframe
10. [Lux](https://github.com/lux-org/lux)：自动推荐探索性数据分析的图表选择。
11. [pycaret](https://github.com/pycaret/pycaret)：An open-source, low-code machine learning library in Python. 快速搭建基础模型，筛选特征

#### 科学计算

1. [scikit-geometry](https://github.com/scikit-geometry/scikit-geometry)：Scientific Python Geometric Algorithms Library
2. [f2py import Fortran code in Python](https://www.scivision.dev/f2py-fortran-python-windows/)
3. [awkward-array](https://github.com/scikit-hep/awkward-array)：Manipulate arrays of complex data structures as easily as Numpy. [Example](https://www.youtube.com/watch?v=WlnUF3LRBj4&list=PLYx7XA2nY5GfY4WWJjG5cQZDc7DIUmn6Z&index=3)
4. [boost-histogram](https://github.com/scikit-hep/boost-histogram)：Python bindings for the C++14 Boost::Histogram library
5. [cusignal](https://github.com/rapidsai/cusignal)：cuSignal - RAPIDS Signal Processing Library
6. [scorep_binding_python](https://github.com/score-p/scorep_binding_python)：Allows tracing of python code using Score-P
7. [scikit-opt](https://github.com/guofei9987/scikit-opt): 传统优化算法等 Genetic Algorithm, Particle Swarm Optimization, Simulated Annealing, Ant Colony Optimization Algorithm,Immune Algorithm, Artificial Fish Swarm Algorithm, Differential Evolution and TSP



### GPU加速

1. [jax](https://github.com/google/jax)：Composable transformations of Python+NumPy programs: differentiate, vectorize, JIT to GPU/TPU, and more（XLA based）
2. [numba](https://github.com/numba/numba)：比jax更复杂NumPy aware dynamic Python compiler using LLVM



### 算法实现

1. [Minimal and clean examples of machine learning algorithms implementations](https://github.com/rushter/MLAlgorithms)
2. [ML-From-Scratch](https://github.com/eriklindernoren/ML-From-Scratch)：Machine Learning From Scratch. 
3. [Machine learning, in numpy 全numpy实现](https://github.com/ddbourgin/numpy-ml)
4. [统计学习方法](https://github.com/WenDesi/lihang_book_algorithm)
5. [统计学习方法：An-Introduction-to-Statistical-Learning](https://github.com/hardikkamboj/An-Introduction-to-Statistical-Learning)：官方版本
6. [概率模型：变分推断、GAN、MC等等 Python library for probabilistic modeling, inference, and criticism](https://github.com/blei-lab/edward)
7. [PRML algorithms implemented in Python](https://github.com/ctgk/PRML)
8. [finite-state toolkit--FST](https://github.com/graehl/carmel)
9. [ Machine learning: a probabilistic perspective ](https://github.com/probml/pyprobml)
10. [TGBoost](https://github.com/wepe/tgboost)
12. [Arbitrary order factorization machines](https://github.com/geffy/tffm)：TensorFlow implementation of an arbitrary order Factorization Machine
13. [SpectralNet](https://github.com/KlugerLab/SpectralNet)：Deep network that performs spectral clustering 【聚类】
14. [Deep universal probabilistic programming with Python and PyTorch](https://github.com/pyro-ppl/pyro)
15. [An-Introduction-to-Statistical-Learning](https://github.com/hardikkamboj/An-Introduction-to-Statistical-Learning)：This repository contains the exercises and its solution contained in the book "An Introduction to Statistical Learning" in python.
16. [hmmlearn](https://github.com/hmmlearn/hmmlearn)：Hidden Markov Models in Python, with scikit-learn like API



### 安全机器学习

1. [OpenMined / PySyft：A library for encrypted, privacy preserving machine learning ](https://github.com/OpenMined/PySyft)
2. [FATE](https://github.com/FederatedAI/FATE): An Industrial Level Federated Learning Framework

### AutoML

1. [AlphaPy](https://github.com/ScottfreeLLC/AlphaPy)：Automated Machine Learning [AutoML] with Python, scikit-learn, Keras, XGBoost, LightGBM, and CatBoost

### 可解释机器学习

1. [interpretable-ml-book](https://github.com/christophM/interpretable-ml-book)
2. [shapash](https://github.com/MAIF/shapash)：🔅 Shapash makes Machine Learning models transparent and understandable by everyone

### 实用资料/调参工具

1. [Machine Learning Cheatsheet](https://github.com/bfortuner/ml-cheatsheet)
2. [**hyperparameter_hunter**](https://github.com/HunterMcGushion/hyperparameter_hunter)：Automatically save and learn from Experiment results, leading to long-term, persistent optimization that remembers all your tests.
3. [hyperopt / hyperopt：超参数调整](https://github.com/hyperopt/hyperopt)



## 4 比赛方案

1. [TNSCUI2020-Seg-Rank1st](https://github.com/WAMAWAMA/TNSCUI2020-Seg-Rank1st)：图像分割
2. [CCKS2019_EventEntityExtraction_Rank5](https://github.com/hecongqing/CCKS2019_EventEntityExtraction_Rank5)：SEBERTNets：一种面向金融领域的事件主体抽取方法
3. [lic2019-dureader2.0-rank2](https://github.com/SunnyMarkLiu/lic2019-dureader2.0-rank2)：Rank2 solution (no-BERT) for 2019 Language and Intelligence Challenge - DuReader2.0 Machine Reading Comprehension.
4. [Tencent2019_Finals_Rank1st](https://github.com/bettenW/Tencent2019_Finals_Rank1st)：2019腾讯广告算法大赛完整代码（冠军）
5. [Tencent2020_Rank1st](https://github.com/guoday/Tencent2020_Rank1st)：The code for 2020 Tencent College Algorithm Contest, and the online result ranks 1st.
6. [riiid-acp-pub 3rd](https://github.com/jamarju/riiid-acp-pub)：Riiid! Answer Correctness Predction 3rd place solution. 复现需要较好的机器配置。
7. [quest_qa_labeling1st](https://github.com/oleg-yaroshevskiy/quest_qa_labeling)：Google QUEST Q&A Labeling. Improving automated understanding of complex question answer content
8. [gaic_track3_pair_sim](https://github.com/nilboy/gaic_track3_pair_sim)：全球人工智能技术创新大赛-短文本语义匹配--冠军方案
9. [ccks_baidu_entity_link](https://github.com/panchunguang/ccks_baidu_entity_link)：ccks baidu entity link 实体链接 第一名
10. [daguancup_-5th](https://github.com/effort-yq/daguancup_-5th)：第五届“达观杯” 基于大规模预训练模型的风险事件标签识别比赛，初赛A榜第四，最终排名第六。只用了单模nezha。



### 比赛信息

1. [MLCompetitionHub](https://github.com/LogicJake/MLCompetitionHub)：机器学习竞赛信息



---

## 5 开源工具

### 可视化

1. [Tool for visualizing attention in the Transformer model](https://github.com/jessevig/bertviz)
2. [tqdm](https://github.com/tqdm/tqdm)
3. [Visualizations for machine learning datasets](https://github.com/PAIR-code/facets)
4. [manim](https://github.com/3b1b/manim)：Animation engine for explanatory math videos
5. [diagrams](https://github.com/mingrammer/diagrams)： Diagram as Code for prototyping cloud system architectures，用代码画架构图
6. [dl-visualization](https://github.com/vivek3141/dl-visualization)：This is a repository containing the source code for the animations to the series "Visualizing Deep Learning" on the YouTube channel [vcubingx](https://youtube.com/vcubingx).
7. [weibo-analysis-and-visualization](https://github.com/HUANGZHIHAO1994/weibo-analysis-and-visualization)



### 系统工具

1. [tldr：Simplified and community-driven man pages](https://github.com/tldr-pages/tldr)
2. [ShellCheck, a static analysis tool for shell scripts](https://github.com/koalaman/shellcheck)
3. [Git] [Git的奇技淫巧](https://github.com/521xueweihan/git-tips)
4. [pure-bash-bible](https://github.com/dylanaraps/pure-bash-bible)：bash脚本使用指南
5. [C++] [Windows Terminal](https://github.com/microsoft/terminal)
6. [awesome window manager ](https://github.com/awesomeWM/awesome)
7. [memory-profiler](https://pypi.org/project/memory-profiler/) pip install memory-profiler
8. **[ code-server](https://github.com/cdr/code-server)**：VS Code in the browser [https://coder.com](https://coder.com/)
9. [gen_tags.vim](https://github.com/jsfaint/gen_tags.vim)：ctags增强
10. [bat](https://github.com/sharkdp/bat)：`bat` supports syntax highlighting for a large number of programming and markup languages
11. [records](https://github.com/kennethreitz42/records): SQL for Humans in Python. *Database support includes RedShift, Postgres, MySQL, SQLite, Oracle, and MS-SQL (drivers not included).*
12. [miasm](https://github.com/cea-sec/miasm)：Reverse engineering framework in Python
13. [graph-data-science](https://github.com/neo4j/graph-data-science)：Neo4j Graph Data Science library of graph algorithms.



### 小项目

1. [一个基于离线唤醒，自然语言理解和情感分析的开源自然交互系统](https://github.com/countstarlight/homo)
2. [微信助手](https://github.com/sfyc23/EverydayWechat)：1.每日定时给好友发送定制消息
3. [latest research results by crawling arxiv papers and summarizing abstracts. ](https://github.com/chiphuyen/sotawhat)
4. [nider](https://github.com/pythad/nider)：Python package to add text to images, textures and different backgrounds
5. [docusaurus](https://github.com/facebook/docusaurus)：Easy to maintain open source documentation websites. [https://docusaurus.io](https://docusaurus.io/)
6. [Synonyms](https://github.com/chatopera/Synonyms)：中文近义词：聊天机器人，智能问答工具包
7. [tushare](https://github.com/waditu/tushare): TuShare is a utility for crawling historical data of China stocks
8. [h5-Dooring](https://github.com/MrXujiang/h5-Dooring)：简单方便、专业可靠、无限可能的H5/PC页面制作解决方案.
9. [pytheory](https://github.com/kennethreitz42/pytheory): 学习音乐理论
10. [live2d-widget](https://github.com/stevenjoezhang/live2d-widget)：前端页面自定义看板娘
11. [Screenshot-to-code](https://github.com/emilwallner/Screenshot-to-code)：静态网页代码生成
12. [latexify_py](https://github.com/google/latexify_py)：Generates LaTeX math description from Python functions.
13. [sherlock](https://github.com/sherlock-project/sherlock)： Hunt down social media accounts by username across social networks
14. [core](https://github.com/home-assistant/core)：Open source home automation that puts local control and privacy first
15. [wttr.in](https://github.com/chubin/wttr.in)：⛅ The right way to check the weather in command line.
16. [typora-plugin-bilibili](https://github.com/xlzy520/typora-plugin-bilibili)：Typora粘贴图片自动上传到Bilibili图床，也可以自定义修改成任意其他图床接口。



### 底层编译架构

1. [MLIR："Multi-Level Intermediate Representation" Compiler Infrastructure](https://github.com/tensorflow/mlir)
2. [The LLVM Project is a collection of modular and reusable compiler and toolchain technologies](https://github.com/llvm/llvm-project)

### 并行计算

1. [dask / dask](https://github.com/dask/dask): Parallel computing with task scheduling

### 测试工具

1. [cypress-io / cypress](https://github.com/cypress-io/cypress)：Fast, easy and reliable testing for anything that runs in a browser.
2. [vscode-recipes](https://github.com/microsoft/vscode-recipes)：A collection of recipes for using VS Code with particular technologies.



---

## 6 数据集

### 工具包

处理中文

1. [python-pinyin](https://github.com/mozillazg/python-pinyin)：汉字转拼音(pypinyin)
2. [OpenCC](https://github.com/BYVoid/OpenCC): Conversion between Traditional and Simplified Chinese
3. [zhon](https://github.com/tsroten/zhon)：Zhon is a Python library that provides constants commonly used in Chinese text processing.



### NLP

1. [中文自然语言处理数据集](https://github.com/InsaneLife/ChineseNLPCorpus)
2. [100+ Chinese Word Vectors 上百种预训练中文词向量](https://github.com/Embedding/Chinese-Word-Vectors)
3. [glyph-aware-character-embedding](https://github.com/yagays/glyph-aware-character-embedding)：区别西文字母不同样式的vec
4. [TX-WORD2VEC-SMALL](https://github.com/cliuxinxin/TX-WORD2VEC-SMALL)：腾讯word2vec模型缩小版
5. [Fasttext](https://fasttext.cc/docs/en/crawl-vectors.html)
6. [ laserembeddings](https://github.com/yannvgn/laserembeddings)：LASER multilingual sentence embeddings as a pip package
7. [中文 自然语言处理 语料/数据集](https://github.com/SophonPlus/ChineseNlpCorpus)
8. [nlp_chinese_corpus](https://github.com/brightmart/nlp_chinese_corpus): 大规模中文自然语言处理语料 Large Scale Chinese Corpus for NLP
9. [WEIBO_USER_DATA](https://github.com/az0ne/WEIBO_USER_DATA)：收集了20W新浪微博用户的数据 
10. 中文NLP.数据集搜索：https://www.cluebenchmarks.com/dataSet_search.html
11. [toutiao-multilevel-text-classfication-dataset](https://github.com/skdjfla/toutiao-multilevel-text-classfication-dataset)：今日头条中文新闻文本(多层)分类数据集
12. [chinese_chatbot_corpus](https://github.com/codemayq/chinese_chatbot_corpus)：中文公开聊天语料库
13. [chinese-xinhua](https://github.com/pwxcoo/chinese-xinhua)：中华新华字典数据库。包括歇后语，成语，词语，汉字。
14. [zhvoice](https://github.com/KuangDD/zhvoice)：中文语音语料，语音更加清晰自然，包含8个开源数据集，3200个说话人，900小时语音，1300万字。
15. [CognitiveInference](https://github.com/liuhuanyong/CognitiveInference)：认知推理、常识知识库、常识推理与常识推理评估的系统项目
16. [ChineseNlpCorpus-1](https://github.com/liuhuanyong/ChineseNlpCorpus-1)：搜集、整理、发布 中文 自然语言处理 语料/数据集
17. [modern-poetry](https://github.com/qyxtim/modern-poetry)：最全的中国近现代诗以及外国诗数据库
18. [Poetry](https://github.com/Werneror/Poetry)：非常全的古诗词数据，收录了从先秦到现代的共计85万余首古诗词。
19. [ChineseLyrics](https://github.com/dengxiuqi/ChineseLyrics)：10W首中文歌词数据库
20. [poetry](https://github.com/javayhu/poetry)：china ancient poetry project data
21. [PersonGraphDataSet](https://github.com/liuhuanyong/PersonGraphDataSet)：人物图谱数据集，近十万的人物关系图谱事实数据库
22. [chinese-poetry](https://github.com/chinese-poetry/chinese-poetry)：最全中华古诗词数据库, 唐宋两朝近一万四千古诗人, 接近5.5万首唐诗加26万宋诗. 两宋时期1564位词人，21050首词。
23. [tang_poetry](https://github.com/hxgdzyuyi/tang_poetry)：全唐诗数据库



### 标注工具

1. [**LabelMeAnnotationTool**](https://github.com/CSAILVision/LabelMeAnnotationTool)
2. [Image Polygonal Annotation with Python](https://github.com/wkentaro/labelme)
3. [LabelImg is a graphical image annotation tool and label object bounding boxes in images](https://github.com/tzutalin/labelImg)
4. [ChineseAnnotator](https://github.com/t-web/ChineseAnnotator)：中文自然语言处理 (NLP) 标注工具



### 图书

1. [singgel / Study-Floder](https://github.com/singgel/Study-Floder)
2. [CS-Books](https://github.com/forthespada/CS-Books)：超过1000本的计算机经典书籍



## 7 Blogs + 面经

1. [frankmcsherry / blog](https://github.com/frankmcsherry/blog)
2. [Bert-for-Chinese-NLP](https://github.com/xueyouluo/Bert-for-Chinese-NLP)
3. [公众号文章小集](https://github.com/shenweichen/AlgoNotes)
4. [ML-NLP](https://github.com/NLP-LOVE/ML-NLP)：机器学习(Machine Learning)、深度学习(Deep Learning)、NLP面试中常考到的知识点和代码实现
5. [深度学习500问](https://github.com/scutan90/DeepLearning-500-questions)
7. [Reflection_Summary](https://github.com/sladesha/Reflection_Summary)：算法理论基础知识
8. [machinelearning](https://github.com/ljpzzz/machinelearning): blogs for machine learning
9. [Pre-trained-Models](https://github.com/loujie0822/Pre-trained-Models)：NLP预训练模型的总结Blog、
10. [Tech Interview Guide 技术面试必备基础知识](https://github.com/CyC2018/CS-Notes)
11. [ML-Interview](https://github.com/ms-sharma/ML-Interview)







附 git保持clone文件同步：

```
git checkout master   # ensure you are on the main "master" branch
git stash             # reset any changes you have made, !!!NOTICE!!!
git pull              # pull the latest versions
```

