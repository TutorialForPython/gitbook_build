# python-io

`IO`(输入输出)通常来讲不属于语法的范畴,但又是任何语言任何程序不可缺少的一块--程序往往用来处理输入,而结果则通过输出告知用户.


通常讲io分为3种

1. 标准输入输出
2. 文件读写
3. socket


本篇介绍python的输入输出相关工具.但socket过于底层,本篇更加关注实际的使用.因此会再做细分

1. 标准输入输出
2. 文件与io流
3. 数据库读写
4. 消息队列读写

关于消息队列更多的是在业务上使用,在本文之前我已经写过[一篇相关博客](http://blog.hszofficial.site/experiment/2019/04/09/%E5%B8%B8%E8%A7%81%E7%9A%84%E6%B6%88%E6%81%AF%E4%B8%AD%E9%97%B4%E4%BB%B6/),刚好是使用python实现的,可以拿它作为参考,本文就不再详细描述

再由于python现在区分同步异步,而异步编程的主要用武之地就在于io一块,所以在有两种不同编程方式的章节中我也会做出区分.
