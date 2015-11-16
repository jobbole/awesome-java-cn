# Java资源大全中文版

我想很多程序员应该记得 GitHub 上有一个 Awesome - XXX 系列的资源整理。[awesome-java](https://github.com/akullpp/awesome-java) 就是 akullpp 发起维护的 Java 资源列表，内容包括：构建工具、数据库、框架、模板、安全、代码分析、日志、第三方库、书籍、Java 站点等等。伯乐在线已经把 awesome-java 资源列表翻成中文后发布于 [ImportNew](http://www.importnew.com/14429.html)。

Awesome 系列虽然挺全，但基本只对收录的资源做了极为简要的介绍，如果有更详细的中文介绍，对相应开发者的帮助会更大。这也是我们发起这个开源项目的初衷。

* * *

### 我们要做什么？

- 基于 awesome-java 资源列表，我们将对各个资源项进行编译整理。
- 整理后的内容，将收录在[伯乐在线资源频道](http://hao.jobbole.com/)。可参考已整理的内容：
  - 《[PgCli：支持自动补全和语法高亮的 PostgreSQL 工具](http://hao.jobbole.com/pgcli-postgresql/)》
  - 《[Wireshark：开源的网络数据包分析软件](http://hao.jobbole.com/wireshark/)》
  - 《[tcpdump：运行在命令行下的嗅探工具](http://hao.jobbole.com/tcpdump/)》

* * *

### 如何参与本项目？

从下面的目录来看，本项目的工作量小不了，所以非常期待能有更多程序员一起来参与。

不过加入前，有几个小要求：

* 英文还不错，能读懂英文并用自己的话复述；
* 在用 Java；

如有兴趣，请加 QQ：50872495。加 Q 时请注明「Java大全」

* * *

### 本项目的参与者

- 维护者：[tangyouhua](https://github.com/tangyouhua)

- 贡献者：[tangyouhua](https://github.com/tangyouhua)、[kingzone](https://github.com/kingzone)、[llhua2329](https://github.com/llhua2329)、[BadCoderChou](https://github.com/BadCoderChou)、You

注：名单不分排名，不定期补充更新

* * *
### 目录
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
    - [分布式应用](#distributed-applications)
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
    - [性能分析](#performance-analysis)
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
    - [社区](#communities)
    - [有影响力的书](#influential-books)
    - [播客](#podcasts)
    - [微博、微信公众号](#weibo-weixin)
    - [Twitter](#twitter)
    - [知名网站](#websites)
    - [博客](blogs)


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

<h3 id="distributed-applications">分布式应用</h3>
*用来编写分布式容错应用的开发库和框架。*

* [Akka](http://akka.io)：用来编写分布式容错并发事件驱动应用程序的工具和运行时。
* [Apache Storm](http://storm.incubator.apache.org/)：实时计算系统。
* [Apache ZooKeeper](http://zookeeper.apache.org/)：针对大型分布式系统的协调服务，支持分布式配置、同步和名称注册。
* [Hazelcast](http://hazelcast.org/)：高可扩展内存数据网格。
* [Hystrix](https://github.com/Netflix/Hystrix)：提供延迟和容错。
* [JGroups](http://www.jgroups.org/)：提供可靠的消息传递和集群创建的工具。
* [Orbit](http://orbit.bioware.com/)：支持虚拟角色（Actor），在传统角色的基础上增加了另外一层抽象。
* [Quasar](http://www.paralleluniverse.co/quasar/)：为JVM提供轻量级线程和角色。

<h3 id="distributed-databases">分布式数据库</h3>
*对应用程序而言，在分布式系统中的数据库看起来就像是只有一个数据源。*

* [Apache Cassandra](http://cassandra.apache.org)：列式数据库，可用性高且没有单点故障。
* [Apache HBase](http://hbase.apache.org)：针对大数据的Hadoop数据库。
* [Druid](http://druid.io)：实时和历史OLAP数据存储，在聚集查询和近似查询方面表现不俗。
* [Infinispan](http://infinispan.org/)：针对缓存的高并发键值对数据存储。

<h3 id="distribution">发布</h3>
*以本机格式发布应用程序的工具。*

* [Bintray](https://bintray.com/)：发布二进制文件版本控制工具。可以于Maven或Gradle一起配合使用。提供开源免费版本和几种商业收费版本。
* [Central Repository](http://search.maven.org/)：最大的二进制组件仓库，面向开源社区提供免费服务。Apache Maven默认使用Central Repository，也可以在所有其他构建工具中使用。
* [IzPack](http://izpack.org/)：为跨平台部署建立创作工具（Authoring Tool）。
* [JitPack](https://jitpack.io/)：打包GitHub仓库的便捷工具。可根据需要构建Maven、Gradle项目，发布可立即使用的组件。
* [Launch4j](http://launch4j.sourceforge.net/)：将JAR包装为轻量级本机Windows可执行程序。
* [Nexus](http://www.sonatype.com/nexus)：支持代理和缓存功能的二进制管理工具。
* [packr](https://github.com/libgdx/packr/)：将JAR、资源和JVM打包成Windows、Linux和Mac OS X本地发布文件。


<h3 id="document-processing">文档处理工具</h3>
*处理Office文档的开发库。*

* [Apache POI](http://poi.apache.org/)：支持OOXML规范（XLSX、DOCX、PPTX）以及OLE2规范（XLS、DOC、PPT）。
* [documents4j](http://documents4j.com)：使用第三方转换器进行文档格式转换，转成类似MS Word这样的格式。
* [jOpenDocument](http://www.jopendocument.org/)：处理OpenDocument格式（由Sun公司提出基于XML的文档格式）。

<h3 id="functional-programming">函数式编程</h3>
*函数式编程支持库。*

* [Cyclops](https://github.com/aol/cyclops)：支持一元（Monad）操作和流操作工具类、comprehension（List语法）、模式匹配、trampoline等特性。
* [Fugue](https://bitbucket.org/atlassian/fugue)：Guava的函数式编程扩展。
* [Functional Java](http://www.functionaljava.org)：实现了多种基础和高级编程抽象，用来辅助面向组合开发（composition-oriented development）。
* [Javaslang](http://javaslang.com)：一个函数式组件库，提供持久化数据类型和函数式控制结构。
* [jOOλ](https://github.com/jOOQ/jOOL)：旨在填补Java 8 lambda差距的扩展，提供了众多缺失的类型和一组丰富的顺序流API。

<h3 id="game-development">游戏开发</h3>
*游戏开发框架。*

* [jMonkeyEngine](http://jmonkeyengine.org/)：现代3D游戏开发引擎。
* [libGDX](http://libgdx.badlogicgames.com/)：全面的跨平台高级框架。
* [LWJGL](http://lwjgl.org/)：对OpenGL/CL/AL等技术进行抽象的健壮框架。


<h3 id="gui">GUI</h3>
*现代图形化用户界面开发库。*

* [JavaFX](http://www.oracle.com/technetwork/java/javase/overview/javafx-overview-2158620.html)：Swing的后继者。
* [Scene Builder](http://www.oracle.com/technetwork/java/javase/downloads/javafxscenebuilder-info-2157684.html)：开发JavaFX应用的可视化布局工具。

<h3 id="high-performance">高性能计算</h3>
*涵盖了从集合到特定开发库的高性能计算相关工具。*

* [Agrona](https://github.com/real-logic/Agrona)：高性能应用中常见的数据结构和工具方法。
* [Disruptor](http://lmax-exchange.github.io/disruptor/)：线程间消息传递开发库。
* [fastutil](http://fastutil.di.unimi.it/)：快速紧凑的特定类型集合（Collection）。
* [GS Collections](https://github.com/goldmansachs/gs-collections)：受Smalltalk启发的集合框架。
* [HPPC](http://labs.carrotsearch.com/hppc.html)：基础类型集合。
* [Javolution](http://javolution.org/)：实时和嵌入式系统的开发库。
* [JCTools](https://github.com/JCTools/JCTools)：JDK中缺失的并发工具。
* [Koloboke](https://github.com/OpenHFT/Koloboke)：Hash set和hash map。
* [Trove](http://trove.starlight-systems.com/)：基础类型集合。

<h3 id="ide">IDE</h3>
*简化开发的集成开发环境。*

* [Eclipse](http://www.eclipse.org/)：老牌开源项目，支持多种插件和编程语言。
* [IntelliJ IDEA](http://www.jetbrains.com/idea/)：支持众多JVM语言，是安卓开发者好的选择。商业版主要针对企业客户。
* [NetBeans](https://netbeans.org/)：为多种技术提供集成化支持，包括Java SE、Java EE、数据库访问、HTML5等。

<h3 id="imagery">图像处理</h3>
*创建、评价和操作图片的支持库。*

* [Imgscalr](https://github.com/thebuzzmedia/imgscalr)：纯Java 2D实现，简单、高效、支持硬件加速的图像缩放开发库。
* [Picasso](http://square.github.io/picasso/)：安卓图片下载和图片缓存开发库。
* [Thumbnailator](https://github.com/coobird/thumbnailator)：Thumbnailator是一个高质量Java缩略图开发库。
* [ZXing](https://github.com/zxing/zxing)：支持多种格式的一维、二维条形码图片处理开发库。

<h3 id="json">JSON</h3>
*简化JSON处理的开发库。*

* [Genson](http://owlike.github.io/genson)：强大且易于使用的Java到JSON转换开发库。
* [Gson](https://github.com/google/gson)：支持在对象与JSON之间双向序列化，性能良好且可以实时调用。
* [Jackson](http://wiki.fasterxml.com/JacksonHome)：与GSON类似，在频繁使用时性能更佳。
* [LoganSquare](https://github.com/bluelinelabs/LoganSquare)：基于Jackson流式API，提供对JSON解析和序列化。比GSON与Jackson组合方式效果更好。

<h3 id="jvm-and-jdk">JVM与JDK</h3>
*目前的JVM和JDK实现。*

* [JDK 9](https://jdk9.java.net/)：JDK 9的早期访问版本。
* [OpenJDK](http://openjdk.java.net/)：JDK开源实现。

<h3 id="languages">基于JVM的语言</h3>
*除Java外，可以用来编写JVM应用程序的编程语言。*

* [Scala](http://www.scala-lang.org/)：融合了面向对象和函数式编程思想的静态类型编程语言。
* [Groovy](http://www.groovy-lang.org/)：类型可选（Optionally typed）的动态语言，支持静态类型和静态编译。目前是一个Apache孵化器项目。
* [Clojure](http://clojure.org/)：可看做现代版Lisp的动态类型语言。
* [Ceylon](http://ceylon-lang.org/)：RedHat开发的面向对象静态类型编程语言。
* [Kotlin](http://kotlinlang.org/)：JetBrain针对JVM、安卓和浏览器提供的静态类型编程语言。

<h3 id="logging">日志</h3>
*记录应用程序行为日志的开发库。*

* [Apache Log4j 2](http://logging.apache.org/log4j/)：使用强大的插件和配置架构进行完全重写。
* [kibana](http://www.elasticsearch.org/overview/kibana/)：分析及可视化日志文件。
* [Logback](http://logback.qos.ch/)：强健的日期开发库，通过Groovy提供很多有趣的选项。
* [logstash](http://logstash.net/)：日志文件管理工具。
* [Metrics](http://metrics.codahale.com/)：通过JMX或HTTP发布参数，并且支持存储到数据库。
* [SLF4J](http://www.slf4j.org/)：日志抽象层，需要与具体的实现配合使用。

<h3 id="machine-learning">机器学习</h3>
*提供具体统计算法的工具。其算法可从数据中学习。*

* [Apache Flink](https://flink.apache.org/)：快速、可靠的大规模数据处理引擎。
* [Apache Hadoop](http://hadoop.apache.org/)：在商用硬件集群上用来进行大规模数据存储的开源软件框架。
* [Apache Mahout](https://mahout.apache.org/)：专注协同过滤、聚类和分类的可扩展算法。
* [Apache Spark](http://spark.apache.org/)：开源数据分析集群计算框架。
* [DeepDive](http://deepdive.stanford.edu)：从非结构化数据建立结构化信息并集成到已有数据库的工具。
* [Deeplearning4j](http://deeplearning4j.org/)：分布式多线程深度学习开发库。
* [H2O](http://0xdata.com/)：用作大数据统计的分析引擎。
* [Weka](http://www.cs.waikato.ac.nz/ml/weka/)：用作数据挖掘的算法集合，包括从预处理到可视化的各个层次。

<h3 id="messaging">消息传递</h3>
*在客户端之间进行消息传递，确保协议独立性的工具。*

* [Aeron](https://github.com/real-logic/Aeron)：高效可扩展的单播、多播消息传递工具。
* [Apache ActiveMQ](http://activemq.apache.org/)：实现JMS的开源消息代理（broker），可将同步通讯转为异步通讯。
* [Apache Camel](http://camel.apache.org/)：通过企业级整合模式（Enterprise Integration Pattern EIP）将不同的消息传输API整合在一起。
* [Apache Kafka](http://kafka.apache.org/)：高吞吐量分布式消息系统。
* [Hermes](http://hermes.allegro.tech)：快速、可靠的消息代理（Broker），基于Kafka构建。
* [JBoss HornetQ](http://hornetq.jboss.org/)：清晰、准确、模块化，可以方便嵌入的消息工具。
* [JeroMQ](https://github.com/zeromq/jeromq)：ZeroMQ的纯Java实现。
* [Smack](https://github.com/igniterealtime/Smack/)：跨平台XMPP客户端函数库。

<h3 id="miscellaneous">杂项</h3>
*未分类其它资源。*

* [Design Patterns](https://github.com/iluwatar/java-design-patterns)：实现并解释了最常见的设计模式。
* [Jimfs](https://github.com/google/jimfs)：内存文件系统。
* [Lanterna](https://code.google.com/p/lanterna/)：类似curses的简单console文本GUI函数库。
* [LightAdmin](http://lightadmin.org/)：可插入式CRUD UI函数库，可用来快速应用开发。
* [OpenRefine](http://openrefine.org/)：用来处理混乱数据的工具，包括清理、转换、使用Web Service进行扩展并将其关联到数据库。
* [RoboVM](http://www.robovm.org/)：Java编写原生iOS应用。

<h3 id="monitoring">应用监控工具</h3>
*监控生产环境中应用程序的工具。*

* [AppDynamics](http://www.appdynamics.com/)：性能监测商业工具。
* [JavaMelody](https://github.com/javamelody/javamelody)：性能监测和分析工具。
* [Kamon](http://www.kamon.io/)：Kamon用来监测在JVM上运行的应用程序。
* [New Relic](http://newrelic.com/)：性能监测商业工具。
* [SPM](http://sematext.com/spm/)：支持对JVM应用程序进行分布式事务追踪的性能监测商业工具。
* [Takipi](https://www.takipi.com/)：产品运行时错误监测及调试商业工具。

<h3 id="native">原生开发库</h3>
*用来进行特定平台开发的原生开发库。*

* [JNA](https://github.com/twall/jna)：不使用JNI就可以使用原生开发库。此外，还为常见系统函数提供了接口。

<h3 id="natural-language-processing">自然语言处理</h3>
*用来专门处理文本的函数库。*

* [Apache OpenNLP](https://opennlp.apache.org/)：处理类似分词等常见任务的工具。
* [CoreNLP](http://nlp.stanford.edu/software/corenlp.shtml)：斯坦佛CoreNLP提供了一组基础工具，可以处理类似标签、实体名识别和情感分析这样的任务。
* [LingPipe](http://alias-i.com/lingpipe/)：一组可以处理各种任务的工具集，支持POS标签、情感分析等。
* [Mallet](http://mallet.cs.umass.edu/)：统计学自然语言处理、文档分类、聚类、主题建模等。

<h3 id="networking">网络</h3>
*网络编程函数库。*

* [Async Http Client](https://github.com/AsyncHttpClient/async-http-client)：异步HTTP和WebSocket客户端函数库。
* [Grizzly](https://grizzly.java.net/)：NIO框架，在Glassfish中作为网络层使用。
* [Netty](http://netty.io/)：构建高性能网络应用程序开发框架。
* [OkHttp](http://square.github.io/okhttp/)：一个Android和Java应用的HTTP+SPDY客户端。
* [Undertow](http://undertow.io/)：基于NIO实现了阻塞和非阻塞API的Web服务器，在WildFly中作为网络层使用。

<h3 id="orm">ORM</h3>
*A处理对象持久化的API。*

* [Ebean](http://ebean-orm.github.io/)：支持快速数据访问和编码的ORM框架。
* [EclipseLink](https://www.eclipse.org/eclipselink/)：支持许多持久化标准，JPA、JAXB、JCA和SDO。
* [Hibernate](http://hibernate.org/orm/)：广泛使用、强健的持久化框架。Hibernate的技术社区非常活跃。
* [MyBatis](http://mybatis.github.io/mybatis-3/)：带有存储过程或者SQL语句的耦合对象（Couples object）。
* [OrmLite](http://ormlite.com/)：轻量级开发包，免除了其它ORM产品中的复杂性和开销。

<h3 id="pdf">PDF</h3>
*用来帮助创建PDF文件的资源。*

* [Apache FOP](http://xmlgraphics.apache.org/fop/)：从XSL-FO创建PDF。
* [Apache PDFBox](http://pdfbox.apache.org/)：用来创建和操作PDF的工具集。
* [DynamicReports](http://dynamicreports.org/)：JasperReports的精简版。
* [flyingsaucer](https://github.com/flyingsaucerproject/flyingsaucer)：XML/XHTML和CSS 2.1渲染器。
* [iText](http://itextpdf.com/)：一个易于使用的PDF函数库，用来编程创建PDF文件。注意，用于商业用途时需要许可证。
* [JasperReports](http://community.jaspersoft.com/project/jasperreports-library)：一个复杂的报表引擎。

<h3 id="performance-analysis">性能分析</h3>
*性能分析、性能剖析及基准测试工具。*

* [jHiccup](http://github.com/giltene/jHiccup)：提供平台中JVM抛锚的日志和记录。
* [JMH](http://openjdk.java.net/projects/code-tools/jmh/)：JVM为基准测试工具。
* [JProfiler](https://www.ej-technologies.com/products/jprofiler/overview.html)：商业分析器。
* [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils)：测量和报告延迟的工具。
* [VisualVM](http://visualvm.java.net/)：对运行中的应用程序信息提供了可视化界面。
* [YourKit Java Profiler](https://www.yourkit.com/features/)：商业分析器。

<h3 id="reactive-libraries">响应式开发库</h3>
*用来开发响应式应用程序的开发库。*

* [Reactive Streams](https://github.com/reactive-streams/reactive-streams-jvm/)：异步流处理标准，支持非阻塞式反向压力（backpressure）。
* [Reactor](http://projectreactor.io/)：构建响应式快速数据（fast-data）应用程序的开发库。
* [RxJava](https://github.com/Netflix/RxJava)：通过JVM可观察序列（observable sequence）构建异步和基于事件的程序。


<h3 id="rest-frameworks">REST框架</h3>
*用来创建RESTful 服务的框架。*

* [Dropwizard](https://dropwizard.github.io/dropwizard/)：偏向于自己使用的Web框架。用来构建Web应用程序，使用了Jetty、Jackson、Jersey和Metrics。
* [Feign](https://github.com/Netflix/feign)：受Retrofit、JAXRS-2.0和WebSocket启发的HTTP客户端连接器（binder）。
* [Jersey](https://jersey.java.net/)：JAX-RS参考实现。
* [RESTEasy](http://resteasy.jboss.org/)：经过JAX-RS规范完全认证的可移植实现。
* [RestExpress](https://github.com/RestExpress/RestExpress)：一个Java类型安全的REST客户端。
* [RestX](http://restx.io)：基于朱洁处理和编译时源码生成的框架。
* [Retrofit](http://square.github.io/retrofit/)：类型安全的REST客户端。
* [Spark](http://www.sparkjava.com/)：受到Sinatra启发的Java REST框架。
* [Swagger](https://helloreverb.com/developers/swagger)：Swagger是一个规范且完整的框架，提供描述、生产、消费和可视化RESTful Web Service。

<h3 id="science">科学计算与分析</h3>
*用于科学计算和分析的函数库。*

* [DataMelt](http://jwork.org/dmelt/)：用于科学计算、数据分析及数据可视化的开发环境。
* [JGraphT](https://github.com/jgrapht/jgrapht)：支持数学图论对象和算法的图形库。
* [JScience](http://jscience.org/)：用来进行科学测量和单位的一组类。

<h3 id="search">搜索引擎</h3>
*文档索引引擎，用于搜索和分析。*

* [Apache Solr](http://lucene.apache.org/solr/)：一个完全的企业搜索引擎。为高吞吐量通信进行了优化。
* [Elasticsearch](http://www.elasticsearch.org/)：一个分布式、支持多租户（multitenant）全文本搜索引擎。提供了RESTful Web接口和无schema的JSON文档。

<h3 id="security">安全</h3>
*用于处理安全、认证、授权或会话管理的函数库。*

* [Apache Shiro](http://shiro.apache.org/)：执行认证、授权、加密和会话管理。
* [Bouncy Castle](https://www.bouncycastle.org/java.html)：多用途加密开发库。支持JCA提供者（JCA provider)，涵盖了从基础的帮助函数到PGP/SMIME操作。
* [Cryptomator](http://cryptomator.org/)：在云上进行客户端跨平台透明加密。
* [Keycloak](http://keycloak.jboss.org/)：为浏览器应用和RESTful Web Service集成SSO和IDM。目前还处于beta版本，但是看起来非常有前途。
* [PicketLink](http://picketlink.org/)：PicketLink是一个针对Java应用进行安全和身份认证管理的大型项目（Umbrella Project）。

<h3 id="serialization">序列化</h3>
*用来高效处理序列化的函数库。*

* [FlatBuffers](https://github.com/google/flatbuffers)：高效利用内存的序列化函数库，无需解包和解析即可高效访问序列化数据。
* [Kryo](https://github.com/EsotericSoftware/kryo)：快速、高效的对象图形序列化框架。
* [FST](https://github.com/RuedigerMoeller/fast-serialization)：提供兼容JDK的高性能对象图形序列化。
* [MessagePack](https://github.com/msgpack/msgpack-java)：一种高效的二进制序列化格式。

<h3 id="server">应用服务器</h3>
*用来部署应用程序的服务器。*

* [Apache Tomcat](http://tomcat.apache.org/)：针对Servlet和JSP的应用服务器，健壮性好且适用性强。
* [Apache TomEE](http://tomee.apache.org/)：Tomcat加Java EE。
* [Jetty](http://www.eclipse.org/jetty/)：轻量级、小巧的应用服务器，通常会嵌入到项目中。
* [WebSphere Liberty](https://developer.ibm.com/wasdev/)：轻量级、模块化应用服务器，由IBM开发。
* [WildFly](http://www.wildfly.org/)：之前被称作JBoss，由Red Hat开发。支持很多Java EE功能。


<h3 id="template-engine">模板引擎</h3>
*在模板中替换表达式的工具。*

* [Apache Velocity](http://velocity.apache.org/)：提供HTML页面模板、email模板和通用开源代码生成器模板。
* [FreeMarker](http://freemarker.org/)：通用模板引擎，不需要任何重量级或自己使用的依赖关系。
* [Handlebars.java](http://jknack.github.io/handlebars.java/)：使用Java编写的模板引擎，逻辑简单，支持语义扩展（semantic Mustache）。
* [Thymeleaf](http://www.thymeleaf.org/)：旨在替换JSP，支持XML文件的工具。

<h3 id="testing">测试</h3>
*测试内容从对象到接口，涵盖性能测试和基准测试工具。*

* [Apache JMeter](http://jmeter.apache.org/)：功能性测试和性能评测。
* [Arquillian](http://arquillian.org/)：集成测试和功能行测试平台，集成Java EE容器。
* [AssertJ](http://joel-costigliola.github.io/assertj/)：支持流式断言提高测试的可读性。
* [Awaitility](https://github.com/jayway/awaitility)：用来同步异步操作的DSL。
* [Cucumber](https://github.com/cucumber/cucumber-jvm)：BDD测试框架。
* [Gatling](http://gatling.io/)：设计为易于使用、可维护的和高性能负载测试工具。
* [Hamcrest](http://hamcrest.org/JavaHamcrest/)：可用来灵活创建意图（intent）表达式的匹配器。
* [JMockit](http://jmockit.org/)：用来模拟静态、final方法等。
* [JUnit](http://junit.org/)：通用测试框架。
* [Mockito](https://github.com/mockito/mockito)：在自动化单元测试中创建测试对象，为TDD或BDD提供支持。
* [PowerMock](https://github.com/jayway/powermock)： 支持模拟静态方法、构造函数、final类和方法、私有方法以及移除静态初始化器的模拟工具。
* [REST Assured](https://github.com/jayway/rest-assured)：为REST/HTTP服务提供方便测试的Java DSL。
* [Selenide](http://selenide.org/)：为Selenium提供精准的周边API，用来编写稳定且可读的UI测试。
* [Selenium](http://docs.seleniumhq.org/)：为Web应用程序提供可移植软件测试框架。
* [Spock](http://docs.spockframework.org/)：JUnit-compatible framework featuring an expressive Groovy-derived specification language.兼容JUnit框架，支持衍生的Groovy范的语言。
* [TestNG](http://testng.org/)：测试框架。
* [Truth](https://github.com/google/truth)：Google的断言和命题（proposition）框架。
* [Unitils](http://www.unitils.org/)：模块化测试函数库，支持单元测试和集成测试。
* [WireMock](http://wiremock.org/)：Web Service测试桩（Stub）和模拟函数。

<h3 id="utility">通用工具库</h3>
*通用工具类函数库。*

* [Apache Commons](http://commons.apache.org/)：提供各种用途的函数，比如配置、验证、集合、文件上传或XML处理等。
* [args4j](http://args4j.kohsuke.org/)：命令行参数解析器。
* [CRaSH](http://www.crashub.org)：为运行进行提供CLI。
* [Gephi](https://github.com/gephi/gephi/)：可视化跨平台网络图形化操作程序。
* [Guava](https://github.com/google/guava)：集合、缓存、支持基本类型、并发函数库、通用注解、字符串处理、I/O等。
* [JADE](http://jade.tilab.com/)：构建、调试多租户系统的框架和环境。
* [javatuples](http://www.javatuples.org/)：正如名字表示的那样，提供tuple支持。尽管目前tuple的概念还有留有争议。
* [JCommander](http://jcommander.org/)：命令行参数解析器。
* [Protégé](http://protege.stanford.edu/)：提供存在论（ontology）编辑器以及构建知识系统的框架。

<h3 id="web-crawling">网络爬虫</h3>
*用于分析网站内容的函数库。*

* [Apache Nutch](http://nutch.apache.org/)：可用于生产环境的高度可扩展、可伸缩的网络爬虫。
* [Crawler4j](https://github.com/yasserg/crawler4j)：简单的轻量级网络爬虫。
* [JSoup](http://jsoup.org/)：刮取、解析、操作和清理HTML。

<h3 id="web-frameworks">Web框架</h3>
*用于处理Web应用程序不同层次间通讯的框架。*

* [Apache Tapestry](http://tapestry.apache.org/)：基于组件的框架，使用Java创建动态、强健的、高度可扩展的Web应用程序。
* [Apache Wicket](http://wicket.apache.org/)：基于组件的Web应用框架，与Tapestry类似带有状态显示GUI。
* [Google Web Toolkit](http://www.gwtproject.org/)：一组Web开发工具集，包含在客户端将Java代码转为JavaScript的编译器、XML解析器、RCP API、JUnit集成、国际化支持和GUI控件。
* [Grails](https://grails.org/)：Groovy框架，旨在提供一个高效开发环境，使用约定而非配置、没有XML并支持混入（mixin）。
* [Ninja](http://www.ninjaframework.org/)：Java全栈Web开发框架。非常稳固、快速和高效。
* [Pippo](http://www.pippo.ro/)：小型、高度模块化的类Sinatra框架。
* [Play](http://www.playframework.com/)：使用约定而非配置，支持代码热加载并在浏览器中显示错误。
* [PrimeFaces](http://primefaces.org/)：JSF框架，提供免费和带支持的商业版本。包括若干前端组件。
* [Ratpack](http://www.ratpack.io/)：一组Java开发函数库，用于构建快速、高效、可扩展且测试完备的HTTP应用程序。
* [Spring Boot](http://projects.spring.io/spring-boot/)：微框架，简化了Spring新程序的开发过程。
* [Spring](http://projects.spring.io/spring-framework/)：旨在简化Java EE的开发过程，提供依赖注入相关组件并支持面向切面编程。
* [Vaadin](https://vaadin.com/)：基于GWT构建的事件驱动框架。使用服务端架构，客户端使用Ajax。

<h2 id="resources">资源</h2>
<h3 id="communities">社区</h3>
* [r/java](http://www.reddit.com/r/java)：Reddit的Java子社区。
* [stackoverflow](http://stackoverflow.com/questions/tagged/java)：问答平台。
* [vJUG](http://virtualjug.com/)：虚拟Java用户组。

<h3 id="influential-books">有影响力的书</h3>
*具有广泛影响且值得阅读的Java经典书籍。*

* [Effective Java (2nd Edition)](http://www.amazon.cn/gp/product/0321356683/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=536&creative=3200&creativeASIN=0321356683&linkCode=as2&tag=vastwork-23)
* [Java 8 in Action](http://www.amazon.com/Java-Action-Lambdas-functional-style-programming/dp/1617291994/)
* [Java Concurrency in Practice | Java并发编程实战](http://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
* [Thinking in Java | Java编程思想](hhttp://www.amazon.cn/gp/product/B0011C3CVA/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=536&creative=3200&creativeASIN=B0011C3CVA&linkCode=as2&tag=vastwork-23)

<h3 id="podcasts">播客</h3>
*可以一边编程一边听的东西。*

* [Java Council](http://virtualjug.com/podcast/)
* [Java Posse](http://www.javaposse.com/)：Discontinued as of 02/2015.

<h3 id="weibo-weixin">微博、微信公众号</h3>
* ImportNew：是最受欢迎的、专注Java技术分享的微信公众号。专注Java技术分享，包括Java基础技术、进阶技能、架构设计和Java技术领域动态等。 
<br>![](http://ww2.sinaimg.cn/small/63918611gw1epb2c7rv2uj20460463ym.jpg)
* ImportNew 微博：[@ImportNew](http://weibo.com/importnew)

<h3 id="twitter">Twitter</h3>
* [Adam Bien](https://twitter.com/AdamBien/)：自由职业者、作家、JavaONE明星演讲者、顾问、Java Champion。
* [Antonio Goncalves](https://twitter.com/agoncal/)：Java Champion、JUG Leader、Devoxx France、Java EE 6/7、JCP、作家。
* [Arun Gupta](https://twitter.com/arungupta/)：Java Champion、JavaONE明星演讲者、JUG Leader、Devoxx4Kids成员、Red Hatter。
* [Bruno Borges](https://twitter.com/brunoborges)：Oracle产品经理、Java Jock。
* [Ed Burns](https://twitter.com/edburns)：Oracle技术团队顾问。
* [Eugen Paraschiv](https://twitter.com/baeldung)：Spring安全课程作者。
* [James Weaver](https://twitter.com/JavaFXpert)：Java、JavaFX、IoT开发者、作者和演讲者。
* [Java EE](https://twitter.com/Java_EE/)：Java EE Twitter官方账号。
* [Java Magazine](https://twitter.com/Oraclejavamag)：Java杂志官方账号。
* [Java.net](https://twitter.com/javanetbuzz/)：Java.net官方账号。
* [Java](https://twitter.com/java/)：Java Twitter官方账号。
* [Javin Paul](https://twitter.com/javinpaul)：知名Java博客作者。
* [Lukas Eder](https://twitter.com/lukaseder)：Data Geekery（jOOQ）创始人兼CEO。
* [Mario Fusco](https://twitter.com/mariofusco)：RedHatter、JUG协调、活跃讲师和作者。
* [Mark Reinhold](https://twitter.com/mreinhold)：Oracle首席架构师、Java平台开发组。
* [Martijn Verburg](https://twitter.com/karianna)：London JUG co-leader、演讲者、作家、Java Champion等。
* [OpenJDK](https://twitter.com/OpenJDK)：OpenJDK官方账号。
* [Reza Rahman](https://twitter.com/reza_rahman)：Java EE、GlassFish、WebLogic传道者、作家、演讲者、开源黑客。
* [Simon Maple](https://twitter.com/sjmaple)：Java Champion、virtualJUG创始人、LJC leader、RebelLabs作者。
* [Stephen Colebourne](https://twitter.com/jodastephen)： Java Champion、演讲者。
* [Tim Boudreau](https://twitter.com/kablosna)：作家、NetBeans大牛。
* [Trisha Gee](https://twitter.com/trisha_gee)：Java Champion、演讲者。

<h3 id="websites">知名网站</h3>
*值得关注的Java技术站点。*

<h4>中文站点</h4>

* [ImportNew](http://www.importnew.com/)（ImportNew 专注 Java 技术）

<h4>英文站点</h4>

* [Android Arsenal](https://android-arsenal.com)
* [Google Java Style](http://google-styleguide.googlecode.com/svn/trunk/javaguide.html)
* [InfoQ](http://www.infoq.com/)
* [Java Code Geeks](http://www.javacodegeeks.com/)
* [Java, SQL, and jOOQ](http://blog.jooq.org/)
* [Java.net](http://java.net/)
* [Javalobby](http://java.dzone.com/)
* [JavaWorld](http://www.javaworld.com/)
* [JAXenter](http://jaxenter.com/)
* [RebelLabs](http://zeroturnaround.com/rebellabs/)
* [The Java Specialist' Newsletter](http://www.javaspecialists.eu/archive/archive.jsp)
* [The Takipi Blog](http://blog.takipi.com/)
* [TheServerSide.com](http://www.theserverside.com/)
* [Thoughts On Java](http://www.thoughts-on-java.org/)
* [Vanilla Java](http://vanillajava.blogspot.ch/)
* [Vlad Mihalcea on Hibernate](http://vladmihalcea.com/)
* [Voxxed](https://www.voxxed.com/)
