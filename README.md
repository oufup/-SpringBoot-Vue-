# 基于SpringBoot与Vue框架的大学生竞赛管理系统

## 项目概述

大学生竞赛管理系统旨在解决传统竞赛管理中信息分散、流程繁琐、效率低下等问题。系统采用前后端分离架构，后端基于Spring Boot，前端基于Vue 3，实现了竞赛管理的全流程信息化。

## 技术栈

### 后端
- &zwnj;**Spring Boot**&zwnj;：快速开发框架
- &zwnj;**Spring Security**&zwnj;：用户认证与权限控制
- &zwnj;**MyBatis-Plus**&zwnj;：持久层框架
- &zwnj;**MySQL**&zwnj;：关系型数据库
- &zwnj;**Redis**&zwnj;：缓存数据库
- &zwnj;**Quartz**&zwnj;：定时任务调度

### 前端
- &zwnj;**Vue 3**&zwnj;：前端框架
- &zwnj;**Element-Plus**&zwnj;：UI组件库
- &zwnj;**Axios**&zwnj;：数据交互

## 功能模块

![image](https://github.com/user-attachments/assets/bc91ad85-167b-492a-8a10-8302ec3a3de5)

## 系统架构

系统采用分层架构设计，包括访问层、前端UI、前端交互、后端服务、数据层及基础服务层。这种设计使得系统具备模块化、灵活、易维护等特点。

## 使用说明

1. &zwnj;**环境准备**&zwnj;
   - 安装Java JDK 11及以上版本
   - 安装MySQL数据库
   - 安装Redis
   - 安装Node.js和npm

2. &zwnj;**项目构建**&zwnj;
   - 克隆项目到本地
   ```bash
   git clone https://github.com/your-repo/competition-management-system.git
