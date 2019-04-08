# 笔记一 Spring IOC 

[TOC]

## 1. IOC

### 1.1 什么是IOC

> Bean 与 Bean 之间的关系交给Spring容器进行管理。



### 1.2 有几种方式

- xml
- 注解

### 1.3 原理流程图

- xml

  ![SpringIOC xml原理](C:\Users\Calvin\Pictures\Saved Pictures\SpringIOC xml原理.png)

- 注解

  ![SpringIOC 注解原理](C:\Users\Calvin\Pictures\Saved Pictures\SpringIOC 注解原理.png)

## 2. 依赖注入（DI）

### 2.1 依赖注入

> 引用别人的对象

### 2.2  原理

1. 使用反射机制获取属性， 判断是否启用注解 ， 根据对象名称查询属性。