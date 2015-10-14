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
*编程方式操作字节码的开发库。*

* [ASM](http://asm.ow2.org/)：通用底层字节码操作和分析开发库。
* [Byte Buddy](http://bytebuddy.net/)：使用流式API进一步简化字节码生成。
* [Byteman](http://byteman.jboss.org/)：在运行时通过DSL（规则）操作字节码进行测试和故障排除。
* [Javassist](http://jboss-javassist.github.io/javassist)：一个简化字节码编辑尝试。

<h3 id="cluster-management">集群管理</h3>
*在集群内动态管理应用程序的框架。*

* [Apache Aurora](http://aurora.apache.org/)：Apache Aurora是一个Mesos框架，用于长时间运行服务和定时任务（cron job）。
* [Singularity](http://getsingularity.com/)：Singularity是一个Mesos框架，方便部署和操作。它支持Web Service、后台运行、调度作业和一次性任务。

<h3 id="code-analysis">代码分析</h3>
*测量代码指标和质量工具。*

* [Checkstyle](https://github.com/checkstyle/checkstyle)：代码编写规范和标准静态分析工具。
* [Error Prone](https://github.com/google/error-prone)：将常见编程错误作为运行时错误报告。
* [FindBugs](http://findbugs.sourceforge.net/)：通过字节码静态分析查找隐藏bug。
* [jQAssistant](http://jqassistant.org/)：使用基于Neo4J查询语言进行代码静态分析。
* [PMD](https://github.com/pmd/pmd)：对源代码分析查找不良的编程习惯。
* [SonarQube](http://www.sonarqube.org/)：通过插件集成其它分析组件，对过去一段时间内的数据进行统计。


<h3 id="compiler-compiler">编译器生成工具</h3>
*用来创建解析器、解释器或编译器的框架。*

* [ANTLR](http://www.antlr.org/)：复杂的全功能自顶向下解析框架。
* [JavaCC](https://javacc.java.net/)：JavaCC是更加专门的轻量级工具，易于上手且支持语法超前预测。


<h3 id="configuration">外部配置工具</h3>
*支持外部配置的开发库。*

* [config](https://github.com/typesafehub/config)：针对JVM语言的配置库。
* [owner](https://github.com/lviggiano/owner)：减少冗余配置属性。

<h3 id="constraint-satisfaction-problem-solver">约束满足问题求解程序</h3>
*帮助解决约束满足问题的开发库。*

* [Choco](http://choco-solver.org/)：可直接使用的约束满足问题求解程序，使用了约束规划技术。
* [JaCoP](https://github.com/radsz/jacop/)：为FlatZinc语言提供了一个接口，可以执行MiniZinc模型。
* [OptaPlanner](http://www.optaplanner.org/)：企业规划与资源调度优化求解程序。
* [Sat4J](http://www.sat4j.org/)：逻辑代数与优化问题最先进的求解程序。

<h3 id="continuous-integration">持续集成</h3>
* [Bamboo](https://www.atlassian.com/software/bamboo)：Atlassian解决方案，可以很好地集成Atlassian的其他产品。可以选择开源许可，也可以购买商业版。
* [CircleCI](https://circleci.com/)：提供托管服务，可以免费试用。
* [Codeship](https://www.codeship.io/features)：提供托管服务，提供有限的免费模式。
* [fabric8](http://fabric8.io/)：容器集成平台。
* [Go](http://www.thoughtworks.com/products/go-continuous-delivery)：ThoughtWork开源解决方案。
* [Jenkins](http://jenkins-ci.org/)：支持基于服务器的部署服务。
* [TeamCity](http://www.jetbrains.com/teamcity/)：JetBrain的持续集成解决方案，有免费版。
* [Travis](https://travis-ci.org)：通常用作开源项目的托管服务。

<h3 id="csv">CSV解析</h3>
*简化CSV数据读写的框架与开发库*

* [uniVocity-parsers](https://github.com/uniVocity/univocity-parsers)：速度最快功能最全的CSV开发库之一，同时支持TSV与固定宽度记录的读写。

<h3 id="database">数据库</h3>
*简化数据库交互的相关工具。*

* [Apache Phoenix](http://phoenix.apache.org/)：HBase针对低延时应用程序的高性能关系数据库层。
* [Crate](https://crate.io/)：实现了数据同步、分片、缩放、复制的分布式数据存储。除此之外还可以使用基于SQL的语法跨集群查询。
* [Flyway](http://flywaydb.org/)：简单的数据库迁移工具。
* [H2](http://h2database.com/)：小型SQL数据库，以可以作为内存数据库使用著称。
* [HikariCP](https://github.com/brettwooldridge/HikariCP)：高性能JDBC连接工具。
* [JDBI](http://jdbi.org/)：便捷的JDBC抽象。
* [jOOQ](http://www.jooq.org/)：为SQL schema生成typesafe代码。
* [MapDB](http://www.mapdb.org/)：以磁盘或堆内存中并发集合为基础的嵌入式数据库引擎。
* [Presto](https://github.com/facebook/presto)：针对大数据的分布式SQL查询引擎。
* [Querydsl](http://www.querydsl.com/)：Typesafe统一查询。

<h3 id="data-structures">数据结构</h3>
* [Apache Parquet](https://parquet.incubator.apache.org/)：Google Dremel论文中发布的基于组装算法的列式（Columnar）存储格式。
* [Protobuf](https://github.com/google/protobuf)：Google数据交换格式。
* [SBE](https://github.com/real-logic/simple-binary-encoding)：简单二进制编码，是最快速的消息格式之一。
* [Wire](https://github.com/square/wire)：整洁轻量级协议缓存。

<h3 id="date-and-time">时间日期工具库</h3>
*处理时间和日期的开发库。*

* [Joda-Time](http://www.joda.org/joda-time/)：在Java 8发布前，Joda-Time是实际使用的时间日期库标准。
* [Time4J](https://github.com/MenoData/Time4J)：高级时间和日期库。

<h3 id="dependency-injection">依赖注入</h3>
*帮助实现[依赖翻转](http://en.wikipedia.org/wiki/Inversion_of_control)范式的开发库。*

* [Apache DeltaSpike](https://deltaspike.apache.org/)：CDI扩展框架。
* [Dagger2](http://google.github.io/dagger/)：编译时注入框架，不需要使用反射。
* [Guice](https://github.com/google/guice)：可以匹敌Dagger的轻量级注入框架。
* [HK2](https://hk2.java.net)：轻量级动态依赖注入框架。

<h3 id="development">开发流程增强工具</h3>
*从最基本的层面增强开发流程。*

* [ADT4J](https://github.com/sviperll/adt4j)：针对代数数据类型的JSR-269代码生成器。
* [AspectJ](https://eclipse.org/aspectj/)：面向切面编程（AOP）的无缝扩展。
* [Auto](https://github.com/google/auto)：源代码生成器集合。
* [DCEVM](http://dcevm.github.io/)：通过修改JVM在运行时支持对已加载的类进行无限次重定义。
* [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent)：支持无限次重定义运行时类与资源。
* [Immutables](http://immutables.github.io/)：类似Scala的条件类。
* [JHipster](https://github.com/jhipster/generator-jhipster)：基于Spring Boot与AngularJS应用程序的Yeoman源代码生成器。
* [JRebel](http://zeroturnaround.com/software/jrebel/)：无需重新部署，可以即时重新加载代码与配置的商业软件。
* [Lombok](http://projectlombok.org/)：减少冗余的代码生成器。
* [Spring Loaded](https://github.com/spring-projects/spring-loaded)：类重载代理。
* [vert.x](http://vertx.io/)：多语言事件驱动应用框架。

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

