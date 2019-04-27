#   东南大学LabVIEW俱乐部数据库

##  项目简介

本项目希望实现一个数据库，来存储*东南大学Labview俱乐部*的各种数据，包括：[资产登记表](#资产登记表)，[会员登记表](#会员登记表)，[事件记录表](#事件记录表)和杂项。

[![License: GPL](https://img.shields.io/github/license/seu-labview/Labview_Database.svg)](LICENSE)
![](https://img.shields.io/github/stars/seu-labview/Labview_Database.svg?style=social)
![](http://progressed.io/bar/1?title=progress)

##  项目目标

*   在**Linux系统**上实现**联网数据库**，服务器设在校内的一台电脑（可能为**树莓派**）上。由于在学校内网，可能须实现**内网穿透**；
*   数据库要**便于修改**，以及**友好的前端界面**以便查看，甚至可能创建**微信小程序**；
*   数据库也要能**存储照片，视频，PPT等**文件；

### 进度

- [ ] 搭建服务器
- [ ] 搭建数据库
- [ ] 实现存储文件功能
- [ ] 载入数据
- [ ] 搭建网页前端
- [ ] 创建微信小程序

##  数据库内容

### 资产登记表

1.  名称
2.  存放位置
3.  数量
4.  估算价格
5.  权力所属（是否做过学校固定资产登记）
6.  照片，视频等其他文件（URL）
7.  现在状态（能不能用，是否借出）
8.  借用记录（借出时间，借用人员，归还时间）
9.  备注
10. 物品ID
11. 总ID

### 会员登记表

未完待续

### 事件记录表

未完待续

##  关于我们

*东南大学LabVIEW俱乐部* 是 *[东南大学](https://www.seu.edu.cn)* 与 *[NI公司](https://www.ni.com)* 合作开办的学术实践类社团，以LabVIEW语言培训为主，以技术交流共享为辅，希望构建便捷的学习图形化编程语言的渠道，以及为学生提供学习、竞赛、交流的技术平台。

[微信公众号](http://mp.weixin.qq.com/mp/homepage?__biz=MzU2MzcwNTE4Ng==&hid=1&sn=28b3c683ca78cfb80f0766ab8a1386f8&scene=18#wechat_redirect)

![](https://mp.weixin.qq.com/rr?timestamp=1556297163&src=3&ver=1&signature=rZBRsm39F9N8LlLIOqiVWrs57LEB7QhSdvMUnxWnXokl0pfNJllOWp1hpU0mIcrJvrmFpFYg*f2jRCC2dDO899g-O63wXpsA5Z91*ojwkU8=)

##  版权声明

本项目中，数据库架构采用开源协议，数据不对外部人员开放。
