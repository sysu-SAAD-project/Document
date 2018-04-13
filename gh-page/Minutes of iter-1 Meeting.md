# 第一次迭代总结会议

## 1. 成果展示

### 1.1 最终产品展示（修改后）
![海报墙页面](../pic/production/海报墙页面.jpg)

![海报详情](../pic/production/海报详情.jpg)

![类型筛选](../pic/production/类型筛选.jpg)

![校区筛选](../pic/production/校区筛选.jpg)

### 1.2 过程产出

#### 1.2.1 功能架构图
![功能架构图](../pic/功能架构图.png)

#### 1.2.2 软件需求说明书
[软件需求说明书](../iter-1/软件需求说明书.md)

#### 1.2.3 api接口设计与实现
HOST: https://www.sysuactivity.com

- List required activities [GET /act?page={pageNum}]
- Get detailed activity information [GET /act/{id}]

#### 1.2.4 数据库设计
![数据库设计](../pic/db.png)

### 1.3 测试反馈
[小程序1.0测试反馈](https://shimo.im/docs/JeOeEFIl6eA4wgCK)

## 2. 第二次迭代说明

### 2.1 产品功能
- 完成小程序端的三大主要功能之一：“我的”。实现用户登录权限和用户信息展示

### 2.2 完善测试流程
- 前端配置eslint检查代码风格，并使用travis CI集成
