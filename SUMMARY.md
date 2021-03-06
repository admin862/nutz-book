# Summary

这是一本好玩的nutz书

* [简介](README.md)
* [前言](chapter1.md)
   * [为什么写这本书](chapter1.1.md)
   * [这本书怎么用](chapter1.2.md)
   * [如何反馈](chapter1.3.md)
   * [术语表](chapter1.4.md)
   * [提问的智慧](chapter1.5.md)
* [环境准备](chapter2.md)
   * [基础知识](chapter2.1.md)
       * [Java基础](chapter2.1.1.md)
	   * [Java EE基础](chapter2.1.2.md)
	   * [Nutz的基本概念](chapter2.1.3.md)
   * [工具选用](chapter2.2.md)
   * [让Eclipse工作在UTF8环境](chapter2.3.md)
   * [准备必要的jar包](chapter2.4.md)
* 搭个架子
   * 什么是架子
   * 新建web项目
   * 添加jar包
   * 添加log4j配置
   * 添加一个首页
   * 修改web.xml
   * 配置druid监控页面
   * 创建MainModule
   * 配置IocBy
       * json加载器
	   * 注解加载器
   * 配置dao.js
       * 数据源配置
	   * NutDao配置
   * 配置Modules
       * 枚举模块类
	   * 包扫描
   * 配置Setup
       * init方法
	   * depose方法
   * 配置默认Ok和Fail
       * 基本语法
	   * 扩展语法简介
   * 配置Localization
       * 目录与语言
	   * 默认语言
   * 配置Views
       * 自定义View的说明
   * 配置Aop
       * 基于注解的Aop
	   * 基于声明的Aop
   * 启动项目
   * 分析一下打印的log信息
       * nutz的日志分类
       * 日志系统的Log
	   * 资源扫描系统的Log
	   * 容器重要信息的Log
	   * Ioc初始化的Log
	   * URL映射关系的Log
	   * 其他小Log
	* 可能遇到的问题
	   * 无日志输出
	   * 数据库连接失败
	   * ClassNotFound
* 用户登陆登出
   * 建几个Pojo
   * 建Module类
   * 配置Module类的Ioc信息
   * 创建默认用户
   * 实现登陆方法
   * 实现登陆页面
   * 实现登出方法
   * 运行起来看看
   * 添加验证码
      * 添加相关的jar
	  * 修改登录方法
	  * 修改页面
	  * 测试一下效果
* 文件上传
   * 添加上传页面
   * 新建一个UploadModule
   * 配置Ioc信息
   * 实现上传方法
* 文件下载
   * 添加下载索引页
   * 实现下载方法
* 基本的权限系统
   * 添加shiro
       * 添加jar包
	   * 修改web.xml
	   * 添加shiro.ini
	* 添加nutz-shiro集成
	   * 声明新的动作链
	   * 建立realm关联
	   * 登陆方法改造
	* 添加页面
		* 用户管理页面
		* 组管理页面
		* 权限管理页面
	* 添加权限方法
		* 用户相关的方法
		* 组相关的方法
		* 权限相关的方法


