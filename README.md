# SpringStudy
框架Spring的学习笔记，这一个项目用来总结Spring的常用开发流程和学习备忘。

Spring 是一个基于Java的开源的，轻量级的，一站式的开发框架。这三个关键词要理解好。

Spring 这个项目的主页是 https://projects.spring.io/spring-framework/

从主页上看，主要的版本号集中在4和5.

![](https://i.imgur.com/OWJ8xa2.png)

我们在这里先搭建最基本的Spring 环境，不使用依赖工具。

在Spring 3 的文档里面，有一个结构图，

![](https://i.imgur.com/6dERo97.png)

从这里面我们可以看出 Bean, core, context 和 EL 是核心的包， logging和dom4j是xml解析和记录的包。

我们可以使用如下的包来进行下载 spring 的 jar 包。

[https://repo.spring.io/webapp/#/artifacts/browse/tree/General/libs-release-local/org/springframework/spring/4.3.2.RELEASE/spring-framework-4.3.2.RELEASE-schema.zip](https://repo.spring.io/webapp/#/artifacts/browse/tree/General/libs-release-local/org/springframework/spring/4.3.2.RELEASE/spring-framework-4.3.2.RELEASE-schema.zip "Spring Jar")

