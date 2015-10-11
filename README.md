# Java资源大全中文版

Java资源大全中文版。以awesome Java为基石，持续更新最新的Java开发资源。

涵盖开发库、开发工具、网站、博客、微信、微博等，专注最新国外Java资源及优秀中文Java资源。由伯乐在线持续更新。

- [Java资源大全中文版](#awesome-java-cn)
    - [古董级工具](#ancients)
    - [构建工具](#build)
    - [字节码操作](#bytecode-manipulation)
    - [集群管理](#cluster-management)
    - [代码分析](#code-analysis)
    - [编译器生成工具](#compiler-compiler)
    - [外部配置工具](#configuration)
    - [约束满足问题求解程序](#constraint-satisfaction-problem-solver)
    - [持续集成](#continuous-integration)
    - [CSV解析](#csv)
    - [数据结构](#data-structures)
    - [数据库](#database)
    - [时间日期工具库](#date-and-time)
    - [依赖注入](#dependency-injection)
    - [开发流程增强工具](#development)
    - [应用发布](#distributed-applications)
    - [分布式数据库](#distributed-databases)
    - [发布](#distribution)
    - [文档处理工具](#document-processing)
    - [函数式编程](#functional-programming)
    - [游戏开发](#game-development)
    - [GUI](#gui)
    - [高性能计算](#high-performance)
    - [IDE](#ide)
    - [图像处理](#imagery)
    - [JSON](#json)
    - [JVM与JDK](#jvm-and-jdk)
    - [基于JVM的语言](#languages)
    - [日志](#logging)
    - [机器学习](#machine-learning)
    - [消息传递](#messaging)
    - [杂项](#miscellaneous)
    - [应用监控工具](#monitoring)
    - [原生开发库](#native)
    - [自然语言处理](#natural-language-processing)
    - [网络](#networking)
    - [ORM](#orm)
    - [PDF](#pdf)
    - [响应式开发库](#reactive-libraries)
    - [REST框架](#rest-frameworks)
    - [科学计算与分析](#science)
    - [搜索引擎](#search)
    - [安全](#security)
    - [序列化](#serialization)
    - [应用服务器](#server)
    - [模板引擎](#template-engine)
    - [测试](#testing)
    - [通用工具库](#utility)
    - [网络爬虫](#web-crawling)
    - [Web框架](#web-frameworks)
- [资源](#resources)
    - [活跃的讨论](#communities)
    - [有影响力的书](#influential-books)
    - [播客](#podcasts)
    - [微博、微信公众号](#weibo-weixin)
    - [知名网站](#websites)
    - [博客](blogs)
- [加入贡献](#contributing)

<h2 id="ancients">古董级工具</h2>

*这些工具伴随着Java一起出现，在各自辉煌之后还在一直使用。*

* [Apache Ant](http://ant.apache.org/)：基于XML的构建管理工具。
* [cglib](https://github.com/cglib/cglib)：字节码生成库。
* [GlassFish](https://glassfish.java.net/)：应用服务器，由Oracle赞助支持的Java EE参考实现。
* [Hudson](http://hudson-ci.org/) ：持续集成服务器，目前仍在活跃开发。
* [JavaServer Faces](https://javaserverfaces.java.net/)：Mojarra是JSF标准的一个开源实现，由Oracle开发。
* [JavaServer Pages](https://jsp.java.net/)：支持自定义标签库的网站通用模板库。
* [Liquibase](http://www.liquibase.org/)：与具体数据库独立的追踪、管理和应用数据库Scheme变化的工具。


<h3 id="build">构建工具</h3>

*构建及应用依赖关系处理工具。*

* [Apache Maven](http://maven.apache.org/) ：Maven是一款声明式构建及依赖管理工具，采用约定优于配置方式进行管理。相对Apache Ant更推荐使用Maven，前者采用了过程式管理，维护相对困难。
* [Bazel](http://bazel.io)：来自Google的构建工具，可以快速、可靠地构建代码。
* [Gradle](http://www.gradle.org/)：使用Groovy（非XML）进行增量构建，可以很好地与Maven依赖管理配合工作。

<h3 id="bytecode-manipulation">字节码操作</h3>
<h3 id="cluster-management">集群管理</h3>
<h3 id="code-analysis">代码分析</h3>
<h3 id="compiler-compiler">编译器生成工具</h3>
<h3 id="configuration">外部配置工具</h3>
<h3 id="constraint-satisfaction-problem-solver">约束满足问题求解程序</h3>
<h3 id="continuous-integration">持续集成</h3>
<h3 id="csv">CSV解析</h3>
<h3 id="data-structures">数据结构</h3>
<h3 id="database">数据库</h3>
<h3 id="date-and-time">时间日期工具库</h3>
<h3 id="dependency-injection">依赖注入</h3>
<h3 id="development">开发流程增强工具</h3>
<h3 id="distributed-applications">应用发布</h3>
<h3 id="distributed-databases">分布式数据库</h3>
<h3 id="distribution">发布</h3>
<h3 id="document-processing">文档处理工具</h3>
<h3 id="functional-programming">函数式编程</h3>
<h3 id="game-development">游戏开发</h3>
<h3 id="gui">GUI</h3>
<h3 id="high-performance">高性能计算</h3>
<h3 id="ide">IDE</h3>
<h3 id="imagery">图像处理</h3>
<h3 id="json">JSON</h3>
<h3 id="jvm-and-jdk">JVM与JDK</h3>
<h3 id="languages">基于JVM的语言</h3>
<h3 id="logging">日志</h3>
<h3 id="machine-learning">机器学习</h3>
<h3 id="messaging">消息传递</h3>
<h3 id="miscellaneous">杂项</h3>
<h3 id="monitoring">应用监控工具</h3>
<h3 id="native">原生开发库</h3>
<h3 id="natural-language-processing">自然语言处理</h3>
<h3 id="networking">网络</h3>
<h3 id="orm">ORM</h3>
<h3 id="pdf">PDF</h3>
<h3 id="reactive-libraries">响应式开发库</h3>
<h3 id="rest-frameworks">REST框架</h3>
<h3 id="science">科学计算与分析</h3>
<h3 id="search">搜索引擎</h3>
<h3 id="security">安全</h3>
<h3 id="serialization">序列化</h3>
<h3 id="server">应用服务器</h3>
<h3 id="template-engine">模板引擎</h3>
<h3 id="testing">测试</h3>
<h3 id="utility">通用工具库</h3>
<h3 id="web-crawling">网络爬虫</h3>
<h3 id="web-frameworks">Web框架</h3>
<h3 id="resources">资源</h3>
<h3 id="communities">活跃的讨论</h3>
<h3 id="influential-books">有影响力的书</h3>
<h3 id="podcasts">播客</h3>
<h3 id="weibo-weixin">微博、微信公众号</h3>
<h3 id="websites">知名网站</h3>
<h3 id="contributing">加入贡献</h3>


