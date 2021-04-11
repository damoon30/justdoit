# Java 学习大纲
首先有个开始，先总结一下自己的知识点，然后针对各个知识点去复习和巩固

## 一、Java基础

### 1. Java基础数据结构
#### 1.1 List
>##### 1.1.1 ArrayList(数组)
>##### 1.1.2 LinkedList(链表)
>##### 1.1.3 Vector(线程安全)

#### 1.2 Map
>##### 1.2.1 HashMap
>##### 1.2.2 LinkHashMap
>##### 1.2.3 concurrentHashMap
>##### 1.2.4 TreeMap
>##### 1.2.5 HashTable

#### 1.3 Set
>##### 1.3.1 HashSet
>##### 1.3.2 LinkHashSet
>##### 1.3.3 TreeSet

### 2. Java 基础知识点

>#### 2.1 Java泛型
>#### 2.2 Java反射
>#### 2.3 Java注解
>#### 2.4 Java类加载机制
>#### 2.5 Java异常分类
>#### 2.6 Java的内存模型


## 二、Java多线程并发

### 1. 线程的基本知识
>#### 1.1 并发知识库
>#### 1.2 Java线程创建的姿势
>#### 1.3 Java线程终止的姿势
>#### 1.4 Sleep和 Wait，start和Run
>#### 1.5 线程的五种状态
>#### 1.6 线程的基本方法,join,wait,notify
>#### 1.7 死锁的几个必要条件

### 2.Java 4种线程池
>#### 2.1 FixedThreadPool
>#### 2.2 ScheduleThreadPool
>#### 2.3 SingleThreadPool
>#### 2.4 CacheThreadPool
>#### 2.5 线程池的原理

### 3.Java锁和jdk的几个关键字
>#### 3.1 公平锁与非公平锁
>#### 3.2 乐观锁和悲观锁
>#### 3.3 自旋锁
>#### 3.4 共享锁和独占锁
>#### 3.5 偏向锁->轻量级锁->重量级锁
>#### 3.6 synchronized
>#### 3.7 reentrantLock
>#### 3.8 锁优化
>#### 3.9 CountdownLatch
>#### 3.10 Semaphore 
>#### 3.11 CyclicBarrier 
>#### 3.12 volatile关键字

### 4.Java阻塞队列原理

>#### 4.1 阻塞队列的简介
>#### 4.2 ArrayBlockingQueue
>#### 4.3 LinkedBlockingQueue
>#### 4.4 PriorityBlockingQueue
>#### 4.5 DelayQueue
>#### 4.6 SynchronousQueue
>#### 4.7 LinkedBlockingQueue
>#### 4.8 LinkedTransferQueue

### 5.并发知识点
>#### 5.1 ThreadLocal作用和原理
>#### 5.2 Java用到的线程调度
>#### 5.3 进程调度算法
>#### 5.4 CAS实现原理（比较并交换）
>#### 5.5 AQS实现原理（抽象队列同步器）

## 三、JVM知识点
### 1.线程的实体

### 2.JVM运行时数据区域
>#### 2.1 运行时内存总览
>#### 2.2 堆内存及新老生代
>#### 2.3 栈和栈帧及方法调用
>#### 2.4 方法调用的原理和实现

### 3.垃圾收集器和内存分配
>### 3.1 引用计数法和可达性算法
>### 3.2 垃圾收集算法
>### 3.3 G1收集器
>### 3.4 Java中的四种引用

### 4.jdk自带的命令行工具
>#### 4.1 jps,jstat,jinfo,jmap,jhat,jstack
>#### 4.2 堆内存排查方案

### 5.类加载机制
>#### 5.1 类加载的过程
>#### 5.2 双亲委派模型
>#### 5.3 破坏双亲委派模型的设计

### 6.编译时的优化
>#### 6.1 早期编译的优化
>#### 6.2 晚期编译的优化


### 7.Java的IO/NIO
>#### 7.1 Java的几种IO模型
>#### 7.2 Java的NIO

## 四、Spring原理
### 1. Spring IOC工厂的构建
>#### 1.1 BeanFactory 和 FactoryBean
>#### 1.2 依赖注入的三种方式

### 2. Spring restart 启动源码解析
>#### 2.1 Spring基于扩展点实现bean的后置处理
>#### 2.2 Spring 的 SPI
>#### 2.3 Spring 解决循环依赖的三级缓存

### 3. Spring 的 AOP原理
>#### 3.1 jdk的动态代理
>#### 3.2 cglib的动态代理

### 4.SpringMVC 原理
>#### 4.1 MVC流程和常用注解

### 5.Mybatis和 Tomcat
>#### 5.1 mybatis请求流程图
>#### 5.2 mybatis一级缓存和二级缓存
>#### 5.3 Tomcat介绍和基本原理



## 五、微服务
>#### 1. 服务注册与发现
>#### 1.1 客户端注册与发现
>#### 1.2 服务端注册与发现
>#### 1.3 Consul
>#### 1.4 Eureka
>#### 1.4 SmartStack和 Etcd
#### 2. API网关
>#### 2.1 Feign和 Ribbon和 Zuul
#### 3. 配置中心
>#### 3.1 Spring Cloud Config
#### 4. 事件调度和服务跟踪
#### 5. 服务熔断（Hystrix）
#### 6. Api管理（SwaggerAPI）


## 六、数据库
#### 1. 数据库索引
>#### 1.1 数据库三范式
>#### 1.2 B+树
> 
### 2. 数据库事务
>#### 2.1 MVCC的实现原理
>#### 2.2 两阶段提交协议
>#### 2.3 三阶段提交协议

### 3. 数据库锁
>#### 3.1 间隙锁
>#### 3.2 行级锁、表级锁和页级锁

## 七、分布式缓存Redis
### 1. Redis常用数据结构
>#### 1.1 String字符串
>#### 1.2 Zset底层实现原理
>#### 1.2 缓存穿透，缓存雪崩，缓存击穿

### 2. Redis分布式锁
>#### 2.1 分布式锁的实现
>#### 2.2 Redison实现分布式锁

### 3. Redis集群
>#### 3.1 Redis cluster模式
>#### 3.2 Redis 哨兵模式


## 七、网络
* 网络的七层架构
  
  [网络的五层协议](https://blog.csdn.net/qq_33592535/article/details/115473609)

* TCP/IP协议 
  
  [UDP与TCP协议](https://github.com/princeSeven/justdoit/blob/master/network/TCP%E4%B8%8EUDP%E5%8D%8F%E8%AE%AE.md)

* 三次握手/四次挥手 
  
  [三次握手和四次挥手](https://github.com/princeSeven/justdoit/blob/master/network/%E4%B8%89%E6%AC%A1%E6%8F%A1%E6%89%8B%E5%92%8C%E5%9B%9B%E6%AC%A1%E6%8C%A5%E6%89%8B.md)

* http和https的区别
* 一个URL访问的全过程
* TCP拥堵解决方案
  


* DNS原理


