![image](https://user-images.githubusercontent.com/2004103/57691648-59208500-7677-11e9-9b6f-21ee0eb5a4dd.png)

Kong是一个丛云到本地的、快速的、可伸缩的分布式微服务抽象层(也称为API网关、API中间件或某些情况下的服务网格)。作为一个开源项目，它的核心价值是高性能和可扩展性。

由于对项目的积极维护，Kong被广泛用于从初创公司到全球5000强以及政府机构的生产中。


# 目录

* [**快速入门**](GETTING-STARTED)
    * [简介](GETTING-STARTED/introduction.md)
    * [五分钟快速开始](GETTING-STARTED/quickstart.md)  
    * [配置一个服务](GETTING-STARTED/configuring-a-service.md)   
    * [启用插件](GETTING-STARTED/enabling-plugins.md)  
    * [添加消费者](GETTING-STARTED/adding-consumers.md)   
* **开发指南**
    * [配置](GUIDES&REFERENCES/configuration.md)    
    * [CLI](GUIDES&REFERENCES/cli.md)    
    * 代理    
    * 认证     
    * 负载均衡  
    * 健康检查和断路器
    * 集群  
    * 日志  
    * 网络&防火墙  
    * 保证 Admin API 安全  
    * 插件开发
        * 简介
        * [文件结构](GUIDES&REFERENCES/plugin-development/file-structure.md)
        * [实现自定义逻辑](GUIDES&REFERENCES/plugin-development/custom-logic.md)
        * [插件配置](GUIDES&REFERENCES/plugin-development/plugin-configuration)
        * [访问数据存储区](GUIDES&REFERENCES/plugin-development/access-the-datastore.md)
        * [存储自定义实体](GUIDES&REFERENCES/plugin-development/custom-entities.md)
        * [缓存自定义实体](GUIDES&REFERENCES/plugin-development/entities-cache.md)
        * 扩展Admin API
        * [编写单元测试](GUIDES&REFERENCES/plugin-development/tests.md)
        * [安装/卸载插件](GUIDES&REFERENCES/plugin-development/distribution.md)
    * [插件开发套件(PDK)](GUIDES&REFERENCES/PDK/pdk.md)
        * kong.client
        * kong.ctx
        * kong.ip
        * kong.log
        * kong.node
        * kong.request
        * kong.response
        * kong.router
        * kong.service
        * kong.service.request
        * kong.service.response
        * kong.table
* [**Admin Api**](ADMIN-API)
    * 支持的 Content Types
    * 信息路由
    * 无DB配置
    * 标签
    * Service对象
    * Router对象
    * Consumer对象
    * 插件对象
    * 认证对象
    * SNI对象
    * Upstream对象
    * Target对象

