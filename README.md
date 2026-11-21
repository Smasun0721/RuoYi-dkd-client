# 帝可得后台管理系统（前端）

![Vue](https://img.shields.io/badge/Vue-3-42B883?logo=vue.js&logoColor=white)
![Vite](https://img.shields.io/badge/Build-Vite-646CFF?logo=vite&logoColor=white)
![Element Plus](https://img.shields.io/badge/UI-Element%20Plus-409EFF)
![RuoYi](https://img.shields.io/badge/Framework-RuoYi%203.8.7-4B6BFB)

基于 RuoYi-Vue 3.8.7 前端脚手架开发的“帝可得”后台管理系统前端，提供商品、货道、工单、订单、策略和设备等管理页面。

## 功能页面

- 登录与权限菜单
- 商品管理、货道管理
- 工单管理、订单管理
- 策略管理、设备管理
- 系统管理（用户、角色、菜单、日志）

## 技术栈

- Vue 3、Vite
- Element Plus、Vue Router、Pinia
- Axios、ECharts
- RuoYi-Vue 3.8.7

## 环境要求

- Node.js 18+
- npm 或 pnpm

## 安装与启动

~~~bash
git clone https://github.com/Smasun0721/RuoYi-dkd-client.git
cd RuoYi-dkd-client
npm install
npm run dev
~~~

开发环境默认通过 VITE_APP_BASE_API=/dev-api 代理到后端，后端地址见 .env.development 和 vite.config.js。

## 关联仓库

- 服务端：[RuoYi-dkd-server](https://github.com/Smasun0721/RuoYi-dkd-server)

## 目录结构

~~~text
RuoYi-dkd-client/
├── src/
│   ├── api/
│   ├── assets/
│   ├── components/
│   ├── layout/
│   ├── router/
│   ├── store/
│   └── views/
├── public/
├── vite/
├── package.json
└── vite.config.js
~~~

## 说明

本项目基于 RuoYi-Vue 3.8.7 前端脚手架二次开发，保留原框架的权限、菜单和基础组件，并实现帝可得业务页面。
