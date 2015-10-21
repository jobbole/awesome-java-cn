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
*Libraries that assist with processing office document formats.*

* [Apache POI](http://poi.apache.org/)：Supports OOXML (XLSX, DOCX, PPTX) as well as OLE2 (XLS, DOC or PPT).
* [documents4j](http://documents4j.com)：API for document format conversion using third-party converters such as MS Word.
* [jOpenDocument](http://www.jopendocument.org/)：Processes the OpenDocument format.

<h3 id="functional-programming">函数式编程</h3>
*Libraries that facilitate functional programming.*

* [Cyclops](https://github.com/aol/cyclops)：Monad and stream utilities, comprehensions, pattern matching, trampolines and much more.
* [Fugue](https://bitbucket.org/atlassian/fugue)：Functional extensions to Guava.
* [Functional Java](http://www.functionaljava.org)：Implements numerous basic and advanced programming abstractions that assist composition-oriented development.
* [Javaslang](http://javaslang.com)：Functional component library that provides persistent data types and functional control structures.
* [jOOλ](https://github.com/jOOQ/jOOL)：Extension to Java 8 which aims to fix gaps in lambda, providing numerous missing types and a rich set of sequential Stream API additions.

<h3 id="game-development">游戏开发</h3>
*Frameworks that support the development of games.*

* [jMonkeyEngine](http://jmonkeyengine.org/)：Game engine for modern 3D development.
* [libGDX](http://libgdx.badlogicgames.com/)：All-round cross-platform, high-level framework.
* [LWJGL](http://lwjgl.org/)：Robust framework that abstracts libraries like OpenGL/CL/AL.


<h3 id="gui">GUI</h3>
*Libraries to create modern graphical user interfaces.*

* [JavaFX](http://www.oracle.com/technetwork/java/javase/overview/javafx-overview-2158620.html)：The successor of Swing.
* [Scene Builder](http://www.oracle.com/technetwork/java/javase/downloads/javafxscenebuilder-info-2157684.html)：Visual layout tool for JavaFX applications.

<h3 id="high-performance">高性能计算</h3>
*Everything about high performance computation, from collections to specific libraries.*

* [Agrona](https://github.com/real-logic/Agrona)：Data structures and utility methods that are common in high-performance applications.
* [Disruptor](http://lmax-exchange.github.io/disruptor/)：Inter-thread messaging library.
* [fastutil](http://fastutil.di.unimi.it/)：Fast and compact type-specific collections.
* [GS Collections](https://github.com/goldmansachs/gs-collections)：Collection framework inspired by Smalltalk.
* [HPPC](http://labs.carrotsearch.com/hppc.html)：Primitive collections.
* [Javolution](http://javolution.org/)：Library for real-time and embedded systems.
* [JCTools](https://github.com/JCTools/JCTools)：Concurrency tools currently missing from the JDK.
* [Koloboke](https://github.com/OpenHFT/Koloboke)：Hash sets and hash maps.
* [Trove](http://trove.starlight-systems.com/)：Primitive collections.

<h3 id="ide">IDE</h3>
*Integrated development environments that try to simplify several aspects of development.*

* [Eclipse](http://www.eclipse.org/)：Established, open-souce project with support for lots of plugins and languages.
* [IntelliJ IDEA](http://www.jetbrains.com/idea/)：Supports a lot of JVM languages and provides good options for Android development. The commercial edition targets the enterprise sector.
* [NetBeans](https://netbeans.org/)：Provides integration for several Java SE and EE features from database access to HTML5.

<h3 id="imagery">图像处理</h3>
*Libraries that assist with the creation, evaluation or manipulation of graphical images.*

* [Imgscalr](https://github.com/thebuzzmedia/imgscalr)：Simple and efficient hardware-accelerated image-scaling library implemented in pure Java 2D.
* [Picasso](http://square.github.io/picasso/)：Image downloading and caching library for Android.
* [Thumbnailator](https://github.com/coobird/thumbnailator)：Thumbnailator is a high-quality thumbnail generation library for Java.
* [ZXing](https://github.com/zxing/zxing)：Multi-format 1D/2D barcode image processing library.

<h3 id="json">JSON</h3>
*Libraries that simplify JSON processing.*

* [Genson](http://owlike.github.io/genson)：Powerful and easy to use Java to JSON conversion library.
* [Gson](https://github.com/google/gson)：Serializes objects to JSON and vice versa. Good performance with on-the-fly usage.
* [Jackson](http://wiki.fasterxml.com/JacksonHome)：Similar to GSON but has performance gains if you need to instantiate the library more often.
* [LoganSquare](https://github.com/bluelinelabs/LoganSquare)：JSON parsing and serializing library based on Jackson's streaming API. Outpeforms GSON & Jackson's library.

<h3 id="jvm-and-jdk">JVM与JDK</h3>
*Current implementations of the JVM/JDK.*

* [JDK 9](https://jdk9.java.net/)：Early access releases of JDK 9.
* [OpenJDK](http://openjdk.java.net/)：Open-source implementation.

<h3 id="languages">基于JVM的语言</h3>
*Languages other than Java that can be used to write JVM applications.*

* [Scala](http://www.scala-lang.org/)：Statically typed programming language that fuses the object - oriented model and functional programming ideas.
* [Groovy](http://www.groovy-lang.org/)：Optionally typed and dynamic language, with static-typing and static compilation capabilities. Currently an incubating Apache project
* [Clojure](http://clojure.org/)：Dynamically typed programming language that can be seen as a modern take on Lisp.
* [Ceylon](http://ceylon-lang.org/)：Statically typed object-oriented language developed by RedHat.
* [Kotlin](http://kotlinlang.org/)：JetBrain's statically typed programming language for the JVM, Android and the browser.

<h3 id="logging">日志</h3>
*Libraries that log the behavior of an application.*

* [Apache Log4j 2](http://logging.apache.org/log4j/)：Complete rewrite with a powerful plugin and configuration architecture.
* [kibana](http://www.elasticsearch.org/overview/kibana/)：Analyzes and visualizes log files.
* [Logback](http://logback.qos.ch/)：Robust logging library with interesting configuration options via Groovy.
* [logstash](http://logstash.net/)：Tool for managing log files.
* [Metrics](http://metrics.codahale.com/)：Expose metrics via JMX or HTTP and can send them to a database.
* [SLF4J](http://www.slf4j.org/)：Abstraction layer which is to be used with an implementation.

<h3 id="machine-learning">机器学习</h3>
*Tools that provide specific statistical algorithms which allow learning from data.*

* [Apache Flink](https://flink.apache.org/)：Fast and reliable large-scale data processing engine.
* [Apache Hadoop](http://hadoop.apache.org/)：Storage and large-scale processing of data-sets on clusters of commodity hardware.
* [Apache Mahout](https://mahout.apache.org/)：Scalable algorithms focused on collaborative filtering, clustering and classification.
* [Apache Spark](http://spark.apache.org/)：Data analytics cluster computing framework.
* [DeepDive](http://deepdive.stanford.edu)：Creates structured information from unstructured data and integrates it into an existing database.
* [Deeplearning4j](http://deeplearning4j.org/)：Distributed and multi-threaded deep learning library.
* [H2O](http://0xdata.com/)：Analytics engine for statistics over big data.
* [Weka](http://www.cs.waikato.ac.nz/ml/weka/)：Collection of algorithms for data mining tasks ranging from pre-processing to visualization.

<h3 id="messaging">消息传递</h3>
*Tools that help to send messages between clients in order to ensure protocol independency.*

* [Aeron](https://github.com/real-logic/Aeron)：Efficient reliable unicast and multicast message transport.
* [Apache ActiveMQ](http://activemq.apache.org/)：Message broker that implements JMS and converts synchronous to asynchronous communication.
* [Apache Camel](http://camel.apache.org/)：Glues together different transport APIs via Enterprise Integration Patterns.
* [Apache Kafka](http://kafka.apache.org/)：High-throughput distributed messaging system.
* [Hermes](http://hermes.allegro.tech)：Fast and reliable message broker built on top of Kafka.
* [JBoss HornetQ](http://hornetq.jboss.org/)：Clear, concise, modular and made to be embedded.
* [JeroMQ](https://github.com/zeromq/jeromq)：Implementation of ZeroMQ.
* [Smack](https://github.com/igniterealtime/Smack/)：Cross-platform XMPP client library.

<h3 id="miscellaneous">杂项</h3>
*Everything else.*

* [Design Patterns](https://github.com/iluwatar/java-design-patterns)：Implementation and explanation of the most common design patterns.
* [Jimfs](https://github.com/google/jimfs)：In-memory file system.
* [Lanterna](https://code.google.com/p/lanterna/)：Easy console text GUI library similar to curses.
* [LightAdmin](http://lightadmin.org/)：Pluggable CRUD UI library for rapid application development.
* [OpenRefine](http://openrefine.org/)：Tool for working with messy data: cleaning, transforming, extending it with web services and linking it to databases.
* [RoboVM](http://www.robovm.org/)：Commercial framework with a free trial to write native iOS apps.

<h3 id="monitoring">应用监控工具</h3>
*Tools that monitor applications in production.*

* [AppDynamics](http://www.appdynamics.com/)：Commercial performance monitor.
* [JavaMelody](https://github.com/javamelody/javamelody)：Performance monitoring and profiling.
* [Kamon](http://www.kamon.io/)：Tool for monitoring applications running on the JVM.
* [New Relic](http://newrelic.com/)：Commercial performance monitor.
* [SPM](http://sematext.com/spm/)：Commercial performance monitor with distributing transaction tracing for JVM apps.
* [Takipi](https://www.takipi.com/)：Commercial in-production error monitoring and debugging.

<h3 id="native">原生开发库</h3>
*For working with platform-specific native libraries.*

* [JNA](https://github.com/twall/jna)：Work with native libraries without writing JNI. Also provides interfaces to common system libraries.

<h3 id="natural-language-processing">自然语言处理</h3>
*Libraries that specialize on processing text.*

* [Apache OpenNLP](https://opennlp.apache.org/)：Toolkit for common tasks like tokenization.
* [CoreNLP](http://nlp.stanford.edu/software/corenlp.shtml)：Stanford's CoreNLP provides a set of fundamental tools for tasks like tagging, named entity recognition, sentiment analysis and many more.
* [LingPipe](http://alias-i.com/lingpipe/)：Toolkit for a variety of tasks ranging from POS tagging to sentiment analysis.
* [Mallet](http://mallet.cs.umass.edu/)：Statistical natural language processing, document classification, clustering, topic modeling and more.

<h3 id="networking">网络</h3>
*Libraries for network programming.*

* [Async Http Client](https://github.com/AsyncHttpClient/async-http-client)：Asynchronous HTTP and WebSocket client library.
* [Grizzly](https://grizzly.java.net/)：NIO framework. Used as a network layer in Glassfish.
* [Netty](http://netty.io/)：Framework for building high performance network applications.
* [OkHttp](http://square.github.io/okhttp/)：HTTP+SPDY client.
* [Undertow](http://undertow.io/)：Web server providing both blocking and non-blocking API’s based on NIO. Used as a network layer in WildFly.

<h3 id="orm">ORM</h3>
*APIs which handle the persistence of objects.*

* [Ebean](http://ebean-orm.github.io/)：Provides simple and fast data access.
* [EclipseLink](https://www.eclipse.org/eclipselink/)：Supports a number of persistence standards: JPA, JAXB, JCA and SDO.
* [Hibernate](http://hibernate.org/orm/)：Robust and widely used with an active community.
* [MyBatis](http://mybatis.github.io/mybatis-3/)：Couples objects with stored procedures or SQL statements.
* [OrmLite](http://ormlite.com/)：Lightweight package avoiding the complexity and overhead of other ORM products.

<h3 id="pdf">PDF</h3>
*Everything that helps with the creation of PDF files.*

* [Apache FOP](http://xmlgraphics.apache.org/fop/)：Creates PDF from XSL-FO.
* [Apache PDFBox](http://pdfbox.apache.org/)：Toolbox for creating and manipulating PDF.
* [DynamicReports](http://dynamicreports.org/)：Simplifies JasperReports.
* [flyingsaucer](https://github.com/flyingsaucerproject/flyingsaucer)：XML/XHTML and CSS 2.1 renderer.
* [iText](http://itextpdf.com/)：Creates PDF files programmatically but requires a license for commercial purposes.
* [JasperReports](http://community.jaspersoft.com/project/jasperreports-library)：Complex reporting engine.

<h3 id="performance-analysis">性能分析</h3>
*Tools for performance analysis, profiling and benchmarking.*

* [jHiccup](http://github.com/giltene/jHiccup)：Logs and records platform JVM stalls.
* [JMH](http://openjdk.java.net/projects/code-tools/jmh/)：Microbenchmarking tool for the JVM.
* [JProfiler](https://www.ej-technologies.com/products/jprofiler/overview.html)：Commercial profiler.
* [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils)：Utilities for latency measurement and reporting.
* [VisualVM](http://visualvm.java.net/)：Visual interface for detailed information about running applications.
* [YourKit Java Profiler](https://www.yourkit.com/features/)：Co

<h3 id="reactive-libraries">响应式开发库</h3>
*Libraries for developing reactive applications.*

* [Reactive Streams](https://github.com/reactive-streams/reactive-streams-jvm/)：Provide a standard for asynchronous stream processing with non-blocking backpressure.
* [Reactor](http://projectreactor.io/)：Library for building reactive fast-data applications.
* [RxJava](https://github.com/Netflix/RxJava)：Library for composing asynchronous and event-based programs using observable sequences from the JVM.


<h3 id="rest-frameworks">REST框架</h3>
*Frameworks specifically for creating RESTful services.*

* [Dropwizard](https://dropwizard.github.io/dropwizard/)：Opinionated framework for setting up modern web applications with Jetty, Jackson, Jersey and Metrics.
* [Feign](https://github.com/Netflix/feign)：HTTP client binder inspired by Retrofit, JAXRS-2.0, and WebSocket.
* [Jersey](https://jersey.java.net/)：JAX-RS reference implementation.
* [RESTEasy](http://resteasy.jboss.org/)：Fully certified and portable implementation of the JAX-RS specification.
* [RestExpress](https://github.com/RestExpress/RestExpress)：Thin wrapper on the JBOSS Netty HTTP stack to provide scaling and performance.
* [RestX](http://restx.io)：Framework based on annotation processing and compile-time source generation.
* [Retrofit](http://square.github.io/retrofit/)：Type-safe REST client.
* [Spark](http://www.sparkjava.com/)：Sinatra inspired framework.
* [Swagger](https://helloreverb.com/developers/swagger)：Swagger is a specification and complete framework implementation for describing, producing, consuming, and visualizing RESTful web services.

<h3 id="science">科学计算与分析</h3>
*Libraries for scientific computing and analysis.*

* [DataMelt](http://jwork.org/dmelt/)：Environment for scientific computation, data analysis and data visualization.
* [JGraphT](https://github.com/jgrapht/jgrapht)：Graph library that provides mathematical graph-theory objects and algorithms.
* [JScience](http://jscience.org/)：Provides a set of classes to work with scientific measurements and units.

<h3 id="search">搜索引擎</h3>
*Engines which index documents for search and analysis.*

* [Apache Solr](http://lucene.apache.org/solr/)：Enterprise search engine optimized for high volume traffic.
* [Elasticsearch](http://www.elasticsearch.org/)：Distributed, multitenant-capable full-text search engine with a RESTful web interface and schema-free JSON documents.

<h3 id="security">安全</h3>
*Libraries that handle security, authentication, authorization or session management.*

* [Apache Shiro](http://shiro.apache.org/)：Performs authentication, authorization, cryptography and session management.
* [Bouncy Castle](https://www.bouncycastle.org/java.html)：All-purpose cryptographic library. JCA provider, wide range of functions from basic helpers to PGP/SMIME operations.
* [Cryptomator](http://cryptomator.org/)：Multiplatform transparent client-side encryption of files in the cloud.
* [Keycloak](http://keycloak.jboss.org/)：Integrated SSO and IDM for browser apps and RESTful web services.
* [PicketLink](http://picketlink.org/)：Umbrella project for security and identity management.

<h3 id="serialization">序列化</h3>
*Libraries that handle serialization with high efficiency.*

* [FlatBuffers](https://github.com/google/flatbuffers)：Memory efficient serialization library that can access serialized data without unpacking and parsing it.
* [Kryo](https://github.com/EsotericSoftware/kryo)：Fast and efficient object graph serialization framework.
* [FST](https://github.com/RuedigerMoeller/fast-serialization)：JDK compatible high performance object graph serialization.
* [MessagePack](https://github.com/msgpack/msgpack-java)：Efficient binary serialization format.

<h3 id="server">应用服务器</h3>
*Servers which are specifically used to deploy applications.*

* [Apache Tomcat](http://tomcat.apache.org/)：Robust all-round server for Servlet and JSP.
* [Apache TomEE](http://tomee.apache.org/)：Tomcat plus Java EE.
* [Jetty](http://www.eclipse.org/jetty/)：Lightweight, small server, often embedded in projects.
* [WebSphere Liberty](https://developer.ibm.com/wasdev/)：Lightweight, modular server developed by IBM
* [WildFly](http://www.wildfly.org/)：Formerly known as JBoss and developed by Red Hat with extensive Java EE support.


<h3 id="template-engine">模板引擎</h3>
*Tools which substitute expressions in a template.*

* [Apache Velocity](http://velocity.apache.org/)：Templates for HTML pages, emails or source code generation in general.
* [FreeMarker](http://freemarker.org/)：General templating engine without any heavyweight or opinionated dependencies.
* [Handlebars.java](http://jknack.github.io/handlebars.java/)：Logic-less and semantic Mustache templates.
* [Thymeleaf](http://www.thymeleaf.org/)：Aims to be a substitute for JSP and works for XML files in general.

<h3 id="testing">测试</h3>
*Tools that test from model to the view.*

* [Apache JMeter](http://jmeter.apache.org/)：Functional testing and performance measurements.
* [Arquillian](http://arquillian.org/)：Integration and functional testing platform for Java EE containers.
* [AssertJ](http://joel-costigliola.github.io/assertj/)：Fluent assertions that improve readability.
* [Awaitility](https://github.com/jayway/awaitility)：DSL for synchronizing asynchronous operations.
* [Cucumber](https://github.com/cucumber/cucumber-jvm)：BDD testing framework.
* [Gatling](http://gatling.io/)：Load testing tool designed for ease of use, maintainability and high performance.
* [Hamcrest](http://hamcrest.org/JavaHamcrest/)：Matchers that can be combined to create flexible expressions of intent.
* [JMockit](http://jmockit.org/)：Mocks static, final methods and more.
* [JUnit](http://junit.org/)：Common testing framework.
* [Mockito](https://github.com/mockito/mockito)：Creation of test double objects in automated unit tests for the purpose of TDD or BDD.
* [PowerMock](https://github.com/jayway/powermock)： Enables mocking of static methods, constructors, final classes and methods, private methods and removal of static initializers.
* [REST Assured](https://github.com/jayway/rest-assured)：Java DSL for easy testing for REST/HTTP services.
* [Selenide](http://selenide.org/)：Concise API around Selenium to write stable and readable UI tests.
* [Selenium](http://docs.seleniumhq.org/)：Portable software testing framework for web applications.
* [Spock](http://docs.spockframework.org/)：JUnit-compatible framework featuring an expressive Groovy-derived specification language.
* [TestNG](http://testng.org/)：Testing framework.
* [Truth](https://github.com/google/truth)：Google's assertion and proposition framework.
* [Unitils](http://www.unitils.org/)：Modular testing library for unit and integration testing.
* [WireMock](http://wiremock.org/)：Stubbs and mocks web services.

<h3 id="utility">通用工具库</h3>
*Libraries which provide general utility functions.*

* [Apache Commons](http://commons.apache.org/)：Provides different general purpose functions like configuration, validation, collections, file upload or XML processing.
* [args4j](http://args4j.kohsuke.org/)：Command line arguments parser.
* [CRaSH](http://www.crashub.org)：Provides a CLI for running processes.
* [Gephi](https://github.com/gephi/gephi/)：Cross-platform for visualizing and manipulating large graph networks.
* [Guava](https://github.com/google/guava)：Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and so forth.
* [JADE](http://jade.tilab.com/)：Framework and environment for building and to debugging multi-agent systems.
* [javatuples](http://www.javatuples.org/)：Tuples.
* [JCommander](http://jcommander.org/)：Command line arguments parser.
* [Protégé](http://protege.stanford.edu/)：Provides an ontology editor and a framework to build knowledge-based systems.

<h3 id="web-crawling">网络爬虫</h3>
*Libraries that analyze the content of websites.*

* [Apache Nutch](http://nutch.apache.org/)：Highly extensible, highly scalable web crawler for production environment.
* [Crawler4j](https://github.com/yasserg/crawler4j)：Simple and lightweight web crawler.
* [JSoup](http://jsoup.org/)：Scrapes, parses, manipulates and cleans HTML.

<h3 id="web-frameworks">Web框架</h3>
*Frameworks that handle the communication between the layers of an web application.*

* [Apache Tapestry](http://tapestry.apache.org/)：Component-oriented framework for creating dynamic, robust, highly scalable web applications.
* [Apache Wicket](http://wicket.apache.org/)：Component-based web application framework similar to Tapestry with a stateful GUI.
* [Google Web Toolkit](http://www.gwtproject.org/)：Toolbox which includes a Java-to-JavaScript compiler for client-side code, XML parser, API for RPC, JUnit integration, internationalization support and widgets for the GUI.
* [Grails](https://grails.org/)：Groovy framework with the aim to provide a highly productive environment by favoring convention over configuration, no XML and support for mixins.
* [Ninja](http://www.ninjaframework.org/)：Full stack web framework.
* [Pippo](http://www.pippo.ro/)：Small, highly modularized Sinatra-like framework.
* [Play](http://www.playframework.com/)：Uses convention over configuration, hot code reloading and display of errors in the browser.
* [PrimeFaces](http://primefaces.org/)：JSF framework which has a free and a commercial version with support. Provides several frontend components.
* [Ratpack](http://www.ratpack.io/)：Set of libraries that facilitate fast, efficient, evolvable and well tested HTTP applications.
* [Spring Boot](http://projects.spring.io/spring-boot/)：Microframework which simplifies the development of new Spring applications.
* [Spring](http://projects.spring.io/spring-framework/)：Provides many packages ranging from dependency injection to aspect-oriented programming to security.
* [Vaadin](https://vaadin.com/)：Event-driven framework build on top of GWT. Uses server-side architecture with Ajax on the client-side.

<h2 id="resources">资源</h2>
<h3 id="communities">社区</h3>
* [r/java](http://www.reddit.com/r/java)：Subreddit for the Java community.
* [stackoverflow](http://stackoverflow.com/questions/tagged/java)：Question/answer platform.
* [vJUG](http://virtualjug.com/)：Virtual Java User Group.

<h3 id="influential-books">有影响力的书</h3>
*Books that had a high impact and are still worth reading.*

* [Effective Java (2nd Edition)](http://www.amazon.com/Effective-Java-Edition-Joshua-Bloch/dp/0321356683)
* [Java 8 in Action](http://www.amazon.com/Java-Action-Lambdas-functional-style-programming/dp/1617291994/)
* [Java Concurrency in Practice](http://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
* [Thinking in Java](http://www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)

<h3 id="podcasts">播客</h3>
*Something to listen to while programming.*

* [The Java Council](http://virtualjug.com/podcast/)
* [The Java Posse](http://www.javaposse.com/)：Discontinued as of 02/2015.

<h3 id="weibo-weixin">微博、微信公众号</h3>

<h3 id="websites">知名网站</h3>
*Sites to read.*

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

<h3 id="contributing">加入贡献</h3>

