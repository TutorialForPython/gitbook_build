# 数学与统计应用篇

python是一门应用领域非常广泛的编程语言,但现今最为人所知的应用领域应该就是科学计算和机器学习了.

本篇就是介绍相应工具的篇章.本文不是讲数学,统计,算法的文章,因此不会太过具体的介绍这些工具的理论基础,更多的是会在实现角度和应用角度做出介绍.

常见的相关工具包括:

+ 专用数据结构和类型
    
    主要是由[numpy](http://www.numpy.org/)和[pandas](http://pandas.pydata.org/)提供,也因此这两个工具从成了python数据科学的基石.这两个工具除了实现了数据类型外也实现了一些算法,在多数时候也已经够用.

    + 同构定长多维数组工具numpy.dnarry

    + 结构化数据表DataFrame实现pandas.DataFrame
    
    + 序列对象pandas.Series

+ 计算框架
    
    通常这类框架是某种理论框架的延续,也就是说算出结果只是附带的事情,这些框架关心的其实更多的是如何实现计算这一过程,虽然未必应用广泛但通常也没有替代品
    + 符号计算框架[Sympy](http://www.sympy.org/en/index.html)
    + 贝叶斯推断框架[Pymc3](http://docs.pymc.io/index.html)
    + 分布式大数据计算框架[spark](http://spark.apache.org/docs/latest/api/python/index.html)
    + 纯python的分布式计算框架[dask](https://dask.org/)

+ 算法封装

    + 通用科学计算算法包[scipy](https://docs.scipy.org/doc/scipy/reference/)
    + 机器学习算法包[sklearn](http://scikit-learn.org/stable/)
    + 专业统计工具包[Statsmodels](http://www.statsmodels.org/stable/index.html)
    + 复杂网络计算框架[networkx](http://networkx.github.io/)以及`C/C++`实现的[igraph](http://igraph.org/)
    + 深度学习计算框架[pytorch](https://pytorch.org/)

  

本文会着重介绍Numpy和Pandas,并且以介绍其数据结构为主.当然,更重要的,本文还会介绍python标准库中的数学计算工具.其他的内容就过于专业了,以后有机会会在其他文章中介绍.

本文会分为如下几个部分:

+ 使用标准库处理基本数学问题
+ 使用python做科学计算
+ 使用python做数据分析
+ 使用python做统计分析
+ 使用python做大数据分析
+ 使用python做复杂网络分析
+ 使用python做机器学习
+ 使用python做深度学习