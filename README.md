<div align=center><img src="info.png" width="600"/></div>

# USE 使用
```
Application Main class add
@ComponentScan(basePackages={"you project package","org.mountcloud.springcloud"})
```

```
<parent>
	<groupId>org.mountcloud</groupId>
	<artifactId>spring-cloud-common-parent</artifactId>
	<version>2.2.1.RELEASE-Hoxton.RELEASE-1.1</version>
</parent>
```

# Warning 警告

  There are data model constraints in this framework! When using this framework, the primary key name in the data table must be id and the data type must be long. And must inherit from org.mountcloud.springproject.common.entity.BaseEntity
  
  本框架中存在数据模型约束！在使用此框架时，数据表中的主键名称必须为id，数据类型必须是long类型。并且必须继承继承org.mountcloud.springproject.common.entity.BaseEntity

# DEMO
  The demo includes the usage of all components in the framework (Redis, Mybatis, Mongodb, Oauth).Demo中包含了框架中所有组件的使用方式（Redis、Mybatis、Mongodb、Oauth）。

https://github.com/MountCloud/spring-cloud-common-demo


# NOTE

&nbsp;&nbsp;Since Eureka 2x is no longer maintained, the service registration in this framework uses Consul for registration services.

&nbsp;&nbsp;This project is a framework for quickly building the spring cloud, and extended work for individual components of spring boot. Spring cloud version used: Hoxton.RELEASE, spring boot version: 2.2.1.RELEASE.
   
&nbsp;&nbsp;The project provides a solution integrating Oauth, a solution integrating feigh, a solution integrating Mongo, a solution integrating mybatis, and a solution integrating redis.
   
# Composition
Readme in connection contains usage and introduction
spring-project-common: https://github.com/MountCloud/spring-project-common

spring-cloud-mvc-common: https://github.com/MountCloud/spring-cloud-mvc-common

spring-cloud-common-oauth-feigh: https://github.com/MountCloud/spring-cloud-common-oauth-feigh

spring-cloud-common-mongo: https://github.com/MountCloud/spring-cloud-common-mongo

spring-cloud-common-mybatis: https://github.com/MountCloud/spring-cloud-common-mybatis

spring-cloud-common-redis: https://github.com/MountCloud/spring-cloud-common-redis

# 介绍

&nbsp;&nbsp;由于Eureka 2x停止维护，所以此框架中服务注册使用Consul进行注册服务。
   
&nbsp;&nbsp;该项目是一个快速构建spring cloud的框架，并且针对spring boot的个别组件进行了扩展工作。使用的spring cloud版本：Hoxton.RELEASE，spring boot版本：2.2.1.RELEASE。
   
&nbsp;&nbsp;项目提供了集成Oauth的解决方案、集成feigh的解决方案、集成Mongo的解决方案、集成mybatis的解决方案、集成redis的解决方案。
 
# 组成
连接中的Readme包含使用方式与简介
spring-project-common: https://github.com/MountCloud/spring-project-common

spring-cloud-mvc-common: https://github.com/MountCloud/spring-cloud-mvc-common

spring-cloud-common-oauth-feigh: https://github.com/MountCloud/spring-cloud-common-oauth-feigh

spring-cloud-common-mongo: https://github.com/MountCloud/spring-cloud-common-mongo

spring-cloud-common-mybatis: https://github.com/MountCloud/spring-cloud-common-mybatis

spring-cloud-common-redis: https://github.com/MountCloud/spring-cloud-common-redis
