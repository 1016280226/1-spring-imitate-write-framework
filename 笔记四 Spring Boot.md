#  笔记四 Spring Boot

[TOC]

## 1. SpringBoot 原理

### 1.1 spring Boot 是什么？

> - 快速整合第三方框架。
> - 简化xml，完成采用注化。
> - 内置http服务器（Tomcat, Netty）。
> - 使用java 应用程序进行执行。



### 1.2 快速整合第三方框架

> 通过Maven 子父关系



### 1.3 简化xml，完成采用注化

> 1. 主要是spring 3.0 后，启用了注解@EnableMVC ，就是通过java 语言代码编写spring MVC 配置初始化。
>
>    （web.xml  被 @EnableMVC 通过代理编写通过反射.class 加载）



### 1.4 内嵌HTTP 服务器

> 通过Java 语言创建Tomcat 容器， 执行 class 文件.



