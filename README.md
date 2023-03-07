

# 资讯自媒体平台

​	一个仿博客园的面向开发者的知识分享社区 , 包括用户中心 , 管理中心 , 媒体中心三大平台

## 项目介绍

​	资讯自媒体平台，是一个可以在线阅读、搜索、发表新闻的自媒体网站，包括前台新闻系统、作家页面以及后台管理系统，基于 SpringBoot、MyBatis实现。前台新闻系统包括：网站首页、用户登录、注册、文章搜索、文章详情、文章分类、最新热文等模块。作家页面包括：内容管理、发布文章、账号设置、粉丝管理、粉丝画像等。后台管理系统包括：文章审核、用户管理、文章分类管理、设置管理员等模块。

## 组织结构

```
news
├── imooc-news-dev-common -- 工具类及通用代码
├── imooc-news-dev-api -- 子模块的接口暴露
├── imooc-news-dev-model -- 数据层包括pojo、vo对象等
├── imooc-news-dev-service-user -- 用户服务
├── imooc-news-dev-service-admin -- 管理员模块
├── imooc-news-dev-service-article -- 文章模块
├── imooc-news-dev-service-article-html -- 静态文章模块
├── imooc-news-dev-service-article -- 文件上传模块
```

## 技术选型

### 后端技术

|     技术      |     说明     |                   官网                   |                   官网                   |   
| :-----------: | :----------: | :--------------------------------------: | :--------------------------------------: |
|      JDK      |  Java版本   | https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html |1.8|
|  SpringBoot   | 容器+MVC框架 |  https://spring.io/projects/spring-boot  |2.2.5|
|     Redis     |   缓存数据   |             https://redis.io             |3.2.12
|    MyBatis    |   ORM框架    |         https://mp.baomidou.com          |2.2.5|
|   RabbitMQ    |   消息队列   |         https://www.rabbitmq.com         |3.8.5|
| Elasticsearch |   搜索引擎   | https://github.com/elastic/elasticsearch |6.8.6|
|     MySQL     |    数据库    |          https://www.mysql.com           |5.7|
|     MongoDB   |数据库        |   http://nginx.org/en/download.html     |4.2.3|
## 环境搭建

### 开发工具

|     工具      |        说明         |                           官网                           |
| :-----------: | :-----------------: | :------------------------------------------------------: |
|     IDEA      |    开发Java程序     |         https://www.jetbrains.com/idea/download          |
|      RDM      | redis客户端连接工具 | https://github.com/uglide/RedisDesktopManager/stargazers |
|  SwitchHosts  |    本地host管理     |            https://oldj.github.io/SwitchHosts            |
|   X-Shell7   |  Linux远程连接工具  |       https://www.vandyke.com/products/securecrt/        |
|    Navicat    |   数据库连接工具    |           http://www.formysql.com/xiazai.html            |
| PDManer |   数据库设计工具    |                 https://gitee.com/robergroup/pdmaner                  |
|    Postman    |   API接口调试工具   |                 https://www.postman.com                  |
|    Typora     |   Markdown编辑器    |                    https://typora.io                     |


