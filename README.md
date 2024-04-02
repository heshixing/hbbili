# 项目介绍

本项目是一个前后端分离的弹幕视频网站，核心功能是观看视频并发送弹幕进行交流。

使用到的技术有：
* 后端
  * SpringBoot
  * MySQL
  * MyBatis-Plus
  * RabbitMQ
  * Redis
  * WebSocket
  * ElasticSearch
  * AOP
  * 协同过滤算法
* 前端：
  * Vue2
  * uniapp
  * dplayer

以下是项目的一些简要介绍：
1. 登录注册、修改资料、查看资料
2. 发布视频、观看视频、观看历史、收藏视频、评论视频、发送弹幕、实时更新同时在看人数、实时收发弹幕
3. 利用 WebSocket 技术和消息队列优化弹幕体验
4. 具备关注订阅功能，被关注用户发布视频后，粉丝能够接收通知
5. 集成 Elasticsearch 的搜索体验：随机排序（不同用户不同顺序），关键词高亮
6. 使用协同过滤算法，有基于用户推荐视频、基于视频推荐视频两种推荐算法
7. 使用消息队列、定时任务、阿里云视频点播服务对视频进行自动审核视频和发布
8. 使用 AOP 进行登录鉴权、接口限流
9. 视频等相关用户数据（点赞、收藏、观看次数）使用定时任务、多线程技术持久化

# 页面展示

```text
这里展示的同学写的uniapp前端，我前端不太行
```
![image](https://github.com/heshixing/hbbili/assets/102710734/71d53149-97cc-4cbc-8157-384ec0717c1a)


*** ***

*** ***

***

![image](https://github.com/heshixing/hbbili/assets/102710734/a7f6a1f6-3ad4-4634-8fd0-895ae933de42)


***

***

***

![image](https://github.com/heshixing/hbbili/assets/102710734/a0004210-415f-40db-97e7-0d15fe0ce2c0)


***

***

***

![image](https://github.com/heshixing/hbbili/assets/102710734/2e1b1c69-6ecf-4857-8ba8-9f9b49c972ae)


***

***

***

