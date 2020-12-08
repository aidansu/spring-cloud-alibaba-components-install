# Spring Cloud Alibaba 组件部署

## 部署方式
* docker-compose
* kubernetes

## 目录结构
```
spring-cloud-alibaba-middleware-install
├── nacos               -- nacos 部署文件
├    ├── docker         -- nacos docker-compose部署文件 
├    ├── kubernetes     -- nacos kubernetes部署文件 
├── sentinel-dashboard  -- sentinel-dashboard 部署文件
├    ├── docker         -- sentinel-dashboard docker-compose部署文件 
├    ├── kubernetes     -- sentinel-dashboard kubernetes部署文件 
├── rocketmq            -- rocketmq 部署文件
├    ├── docker         -- rocketmq docker-compose部署文件 
├    ├── kubernetes     -- rocketmq kubernetes部署文件 
```

## 软件版本
| 软件                 | 版本    |
|---------------------|--------|
| Nacos               | 1.2.1  |
| Sentinel-Dashboard  | 1.7.1  |
| RocketMQ            | 4.5.0  |
| RocketMQ-Console    | 1.0.1  |
