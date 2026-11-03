# 基于SpringBoot+Vue的顺风车管理系统

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Vue3](https://img.shields.io/badge/-Vue3-grey?style=flat-square) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MyBatis](https://img.shields.io/badge/-MyBatis-000000?style=flat-square&logo=mybatis&logoColor=white) 

## 项目介绍

RideShare 是一款面向通勤与城际拼车的顺风车管理平台，**重点支持地图路线预览**：行程/需求详情页可按起终点与途经经停点自动驾车规划、走廊筛点纠偏同名站，地图上标注起终点与途经点并绘制真实路网路线。业务覆盖车主资质审核、车辆档案、行程与需求大厅、拼车下单托管、司乘私聊、双向评价与 AI 出行向导，适合毕设、课设与学习参考。

## 主要功能模块

- **地图路线预览（核心亮点）**：行程/需求详情嵌入在线地图，起终点检索与驾车路径规划，途经点按自身城市检索并用路线走廊过滤错误同名点，地图标注与折线同步展示
- **行程大厅模块**：市内通勤/城际/节假返乡行程发布与筛选，卡片展示途经点摘要，详情页联动地图路线
- **需求大厅模块**：乘客发布出行需求，车主浏览接洽，详情同样支持地图路线预览
- **拼车订单模块**：下单座位扣减、钱包托管支付、确认/出行/完单/取消退款状态机
- **车主中心模块**：驾驶证资质审核、车辆档案维护、默认座驾与发行程前置校验
- **司乘私聊模块**：按订单会话列表、未读角标、打开会话自动已读
- **管理中台模块**：ECharts 运营大屏、资质审核、车辆/行程/订单监管与用户管理
- **权限与 AI**：普通用户/管理员双角色 JWT 鉴权，通义千问出行向导辅助答疑

## 技术架构

- **后端**：Spring Boot + MyBatis-Plus + JWT + Lombok
- **前端**：Vue 3 + TypeScript + Vue Router + Pinia + Element Plus + Vite + ECharts
- **数据库**：MySQL

<!-- screenshots-start -->
## 系统截图

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/rideshare/%E5%87%BA%E8%A1%8C%E8%AF%A6%E6%83%85.png" alt="出行详情" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/rideshare/%E6%8B%BC%E8%BD%A6%E5%8F%91%E5%B8%83.png" alt="拼车发布" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/rideshare/%E8%A1%8C%E7%A8%8B%E5%A4%A7%E5%8E%85.png" alt="行程大厅" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/rideshare/%E9%9C%80%E6%B1%82%E5%A4%A7%E5%8E%85.png" alt="需求大厅" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/rideshare/%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2.png" alt="登录页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/rideshare/%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5.png" alt="用户首页" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/rideshare/%E8%AE%A2%E5%8D%95%E9%A1%B5%E9%9D%A2.png" alt="订单页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/rideshare/%E8%BD%A6%E4%B8%BB%E4%B8%AD%E5%BF%83.png" alt="车主中心" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/rideshare/%E5%8F%B8%E4%B9%98%E7%A7%81%E8%81%8A.png" alt="司乘私聊" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/rideshare/%E7%AE%A1%E7%90%86%E5%91%98%E4%BB%AA%E8%A1%A8%E7%9B%98.png" alt="管理员仪表盘" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/rideshare/%E8%BD%A6%E8%BE%86%E6%A1%A3%E6%A1%88%E7%AE%A1%E7%90%86.png" alt="车辆档案管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/rideshare/%E8%AE%BA%E6%96%87%E5%9B%BE1.png" alt="论文图1" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/rideshare/%E8%AE%BA%E6%96%87%E5%9B%BE2.png" alt="论文图2" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/rideshare/UML%E5%9B%BE%E5%88%97%E8%A1%A8.png" alt="UML图列表" width="600" />

<!-- screenshots-end -->

## 接毕业设计和论文

### 作者微信：vvsgxmn  (支持修改、 部署调试、 支持代做毕设)

### 接网站建设、小程序

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 都可以做

### 购买地址：[https://www.vvxx.love](https://www.vvxx.love)（vv毕设网）

### 支持 **一键生成 UML 图**：上传项目压缩包即可自动产出功能模块图、用例图、流程图、E-R 图、时序图等全套毕设图表。

### 提供 **免费配套软件下载 + 安装说明 + 部署教程**

![vv毕设网 - 一键画图](https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/uml-draw.png)

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/image-20260825133349317.png" alt="image-20260825133349317" />

⚠️ Bug添加微信**免费修复**，免费修复。其他平台的私信一律不管（微信方便发送文件）
