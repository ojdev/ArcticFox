这个框架是一个简单的给予abp的结构搭建的框架，通过查看abp的源码，abp中的appService是基于Controller的;
目前这个框架只是用来做webapi；

还有很多内容可以进行完善，但是以上的这些已经基本形成了一个完整的框架。

## 已实现：
* DDD结构
* Swagger控制
* 仓储
* 异常拦截
* 白名单（白名单优先级高于黑名单）
* 黑名单
* 审计日志（默认全部审计，不进行审计的方法可以使用Auditing(false)属性进行标识）
* 将审计日志存储到数据库
* UnitOfWork
* 自动迁移
## 实现中
* 属性注入
* 消息队列
* 分布式事务
## 待加入


