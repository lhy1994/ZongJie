#总结
  
##java

###Java基础

   switch能否用string做参数
   
   object有哪些公用方法：equals和==，hashcode，clone，wait，notify等
   
   String、StringBuffer与StringBuilder的区别。
   
   try catch finally，try里有return，finally还执行么？
   
   Excption与Error包结构。
   
   Override和Overload的含义与区别。
   
   Interface与abstract类的区别。
   
   Static class 与non static class的区别。
   
   foreach与正常for循环效率对比。
   
   反射机制
   
   String类内部实现，能否改变String对象内容，String源码
   
   Java1.7与1.8新特性。
   
###java集合
  
  java集合框架的结构
  
  list，set，map接口
  
  哪些是线程安全，哪些不安全
  
  hashmap能否用null作为键或值
  
  hashmap源码
  
  快速失败与安全失败
  
  arraylist，linkedlist底层实现区别，如何扩容
  
  treemap，hashmap，linkedhashmap区别和特点，底层实现的区别
  
  如何解决不安全的集合的安全性问题
  
###Jvm虚拟机

  强软弱虚四种引用

  java内存分区
  
  java的个内存分区在什么情况下内存溢出
  
  java垃圾回收机制，垃圾收集算法特点及工作在哪一代，分代收集策略，如何判断一个对象该被回收了，java对象实现如何自救，java的垃圾收集器，内存分配与回收及分配担保
  
  java的类加载机制，类加载的5个步骤，类加载器
  
###Java并发

  线程生命周期
  
  java如何使用多线程（runnable和Thread）
  
  stop，resume，suspend的缺点
  
  终止线程有哪些方法
  
  守护线程
  
  synchronize关键字和wait，notify，notifyAll
  
  lock与condition，Java中的几种不同锁
  
  线程死锁情景
  
  消费者生产者模型
  
  volatile关键字，是否保证原子性，优缺点
  
  ThreadLocal的特点和使用
  
  单例模式和多线程
  
  SimpleDateFormat的安全性问题
  
  java的并发容器包Concurrent。阻塞队列，CopyOnRightList等
  
  ConcurrentHashMap的源理
  
  java的线程池原理和自带的四大线程池
  
  Executor框架
  
##Android

###Android基础

  五种布局的特点和效率对比

  Activity的生命周期和缓存

  Fragment的生命周期

  Service的两种启动方式，如何保证一个Service不被杀死

  广播注册的两种方式的区别
  
  如何安全的退出一个已经开启多个activity的APP
  
  Android的进程优先级
  
  Asset目录与res目录的区别
  
  ANR问题，force close问题，activity，service，broadcast各自超过多少秒报ANR
  
  Activity启动模式，intent匹配规则
  
  Android反编译
  
  JNI和native方法
  
  Android系统的有哪些安全机制
  
  Android新特性有哪些（5.0 6.0 7.0）
  
  Dalvik和ART区别
  
  Android屏幕适配有哪些方法

###Android View相关

  View事件体系，滑动冲突
  
  View绘制原理，性能问题（view绘制间隔16ms，60fps）,measure，layout，draw三大过程
  
  如何避免overdraw
  
  自定义View相关知识，下拉刷新的实现
  
  Android动画分类和各自特点
  
  View和SurfaceView的区别

###Android性能优化

  APK瘦身的办法

  ListView的源码和如何优化Listview

  Android如何获取Crash信息
  
  ANR日志分析
  
  Android动态加载，如何解决方法数越界

  Android怎么加速启动Activity
  
  Android内存泄漏问题，内存泄漏分析工具
  
  Android内存溢出问题，图片的三级缓存
  
###Android framework和底层原理

  Android系统开机过程
  
  Zygote和System进程的启动过程

  Android的消息机制，Handler原理
  
  AsyncTask源码，优缺点
  
  HandlerThread和IntentService的原理和特点

  Android的IPC机制
  
  AIDL原理
  
  Binder机制原理
  

###Android框架和源码

  项目各个细节熟练，熟悉项目用到的框架源码
  
  Volley
  
  xUtils
  
  okHttp
  
  UniversalImageLoader
  
  RxJava
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  

  
