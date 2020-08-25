---
date: 2019-02-01T15:00:00+08:00
title: 日常开发部署运维
weight: 1000
description : "统一基础设施"
---

### 统一基础设施 

- Coral: 微服务化 + VIP
- Pipeline/Apollo： 发布/部署平台
- Versionset： 版本管理系统

 ### 统一调用方式

 - 一切都是服务(从infra类 到中间件 到各种tools 到开发流程，是一种理念)
 - 任何AWS service都是通过其他AWS service服务实现的，都是通过配置endpoint的AWS SDK来call

### 统一安全措施：AAA

- access key, secret key 
- IAM user, assume-role
- Cloudtrail

### 统一监控

- 统一元数据（ARN）
- Amazon 资源名称 (ARN) 唯一标识 AWS 资源, 在 AWS 全局环境中（比如 IAM 策略、API 调用中）明确指定一项资源尤为重要
- 资源间依赖/调用/父子关系；资源间协调；event-driven processing

### 统一生态
