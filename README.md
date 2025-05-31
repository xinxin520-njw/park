# 智慧园区管理系统 智慧楼宇系统

#### 介绍
智慧园区管理系统、智慧园区管理平台、智慧园区解决方案,我们致力于智慧化工园区、智慧园区、智慧科技园区、智慧办公园区、等各种工业园区的综合管理系统的设计、建设和智慧园区综合解决方案。

智慧园区管理系统，主要实现园区的资产管理，企业服务及档案管理，人脸门禁、智慧停车场、工单报修、视频监控、智慧巡检、资产管理、财务管理、招商管理、OA办公等等，多维度，多业态助力商业园区以及商业楼宇数字化升级。园区的活动及商城的搭建。 智慧园区是用信息技术为手段、智慧应用为支撑，全面整合园区内外的资源，使园区管理服务等更高效便捷，实现基础设施网络化、管理信息化、功能服务精准化和产业发展智能化， 全面提升园区信息化管理水平。打造城市代言，智慧城市缩影、打造产业基地，谋求跨越发展、传感网、物联网等战略性新兴技术的示范应用；向规模化、集群化、现代化升级、资源集中化，成本优势，规模优势，产业链协同、物流配套畅通

# 架构图
![园区架构图](https://github.com/user-attachments/assets/86ff7da4-3be0-4a89-8396-ae19bb16606f)

# 智慧园区技术特点
* Java 后端： JDK 17/21 + Spring Boot 3.2
* 管理后台的电脑端：Vue3 提供 [element-plus](https://gitee.com/yudaocode/yudao-ui-admin-vue3)、[vben(ant-design-vue)](https://gitee.com/yudaocode/yudao-ui-admin-vben) 两个版本
* 管理后台的移动端：采用 [uni-app](https://github.com/dcloudio/uni-app) 方案，一份代码多终端适配，同时支持 APP、小程序、H5！
* 后端采用 Spring Cloud Alibaba 微服务架构，注册中心 + 配置中心 Nacos，定时任务 XXL-Job，服务保障 Sentinel，服务网关 Gateway，分布式事务 Seata
* 数据库可使用 MySQL、Oracle、PostgreSQL、SQL Server、MariaDB、国产达梦 DM、TiDB 等，基于 MyBatis Plus、Redis + Redisson 操作
* 消息队列可使用 Event、Redis、RabbitMQ、Kafka、RocketMQ 等
* 权限认证使用 Spring Security & Token & Redis，支持多终端、多种用户的认证系统，支持 SSO 单点登录
* 支持加载动态权限菜单，按钮级别权限控制，Redis 缓存提升性能
* 高效率开发，使用代码生成器可以一键生成 Java、Vue 前后端代码、SQL 脚本、接口文档，支持单表、树表、主子表
* 实时通信，采用 Spring WebSocket 实现，内置 Token 身份校验，支持 WebSocket 集群
* 集成微信小程序、微信公众号、企业微信、钉钉等三方登陆，集成支付宝、微信等支付与退款
* 集成阿里云、腾讯云等短信渠道，集成 MinIO、阿里云、腾讯云、七牛云等云存储服务
* 集成报表设计器、大屏设计器，通过拖拽即可生成酷炫的报表与大屏


