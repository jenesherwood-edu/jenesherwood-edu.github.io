---
layout:     post
title:      Spring中各个jar包的作用
subtitle:   简述
date:       2018-07-17
author:     JeneSherwood
header-img: img/post-bg-article.jpg
catalog: true
tags:
    - Spring
---

Spring AOP：Spring的面向切面编程，提供AOP（面向切面编程）的实现

Spring Aspects：Spring提供的对AspectJ框架的整合

Spring Beans：Spring IOC的基础实现，包含访问配置文件、创建和管理bean等。

Spring Context：在基础IOC功能上提供扩展服务，此外还提供许多企业级服务的支持，有邮件服务、任务调度、JNDI定位，EJB集成、远程访问、缓存以及多种视图层框架的支持。

Spring Context Support：Spring context的扩展支持，用于MVC方面。

Spring Core：Spring的核心工具包

Spring expression：Spring表达式语言

Spring Framework Bom：

Spring Instrument：Spring对服务器的代理接口

Spring Instrument Tomcat：Spring对tomcat连接池的集成

Spring JDBC：对JDBC 的简单封装

Spring JMS：为简化jms api的使用而做的简单封装

Spring Messaging：

Spring orm：整合第三方的orm实现，如hibernate，ibatis，jdo以及spring 的jpa实现

Spring oxm：Spring对于object/xml映射的支持，可以让JAVA与XML之间来回切换

Spring test：对JUNIT等测试框架的简单封装

Spring tx：为JDBC、Hibernate、JDO、JPA等提供的一致的声明式和编程式事务管理。

Spring web：包含Web应用开发时，用到Spring框架时所需的核心类，包括自动载入WebApplicationContext特性的类、Struts与JSF集成类、文件上传的支持类、Filter类和大量工具辅助类。

Spring webmvc：包含SpringMVC框架相关的所有类。包含国际化、标签、Theme、视图展现的FreeMarker、JasperReports、 Tiles、Velocity、XSLT相关类。当然，如果你的应用使用了独立的MVC框架，则无需这个JAR文件里的任何类。

Spring webmvc portlet：Spring MVC的增强

Spring websocket：提供 Socket通信， web端的推送功能