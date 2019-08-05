# Express-System
使用 spring boot，基于 ssm 框架和 shiro 安全框架，开发的一个物流管理系统。前端使用的是 H-ui 开源框架，运用了 Bootstrap table、zTree、PageHelper、jQuery validate 等插件。

## 特点
1. 基于 spring boot、maven 构建；
2. 运用了 spring、spring mvc、mybatis 和 shiro 框架；
3. 采用了 RBAC 的思路设计系统，采用了 Mysql 作为数据库支持；
4. 不同的角色登录系统会有不同的菜单列表，且会根据角色返回特定的数据；
5. 拥有基础数据管理模块，管理员管理模块，角色管理模块，权限管理模块，客户管理模块，订单管理模块和业务处理模块；
6. 能够实现完整的业务流程：添加客户、添加订单、订单处理、财务报表。

## 编译环境
1. JDK 1.8；
2. Maven；
3. Tomcat 8。

## 测试体验
物流管理系统部署在在 Linux 云服务器上，可用前往体验，可以添加数据，但请勿删除和修改任何数据。[访问链接](http://167.71.143.69:8080/logistic)

> username:admin
>
> password:123456

## 备注
该系统为个人学习过程中独自开发，页面设计较为单一，主要是为了实现后台的功能设计，如果有意见欢迎大家提出，谢谢！
