# Awesome Practice

[English](./README-en.md) | 简体中文	
#### 这是一个用 docker 搭建 laravel + vue 前后台分离的项目,安装 docker 请参考[docker官方文档](https://docs.docker.com/)

## 执行步骤
1. 检查是否安装 docker 环境
2. 创建工作目录, 克隆当前项目
3. 进入awesome-practice 目录,运行`docker-compose up -d `
4. `docker-compose ps` 查看是否运行成功, 访问[http://localhost:8080](http://localhost:8080)
5. docker-compose.yml 适用于开发环境
6. 后台 php 环境测试地址[后台测试地址](http://localhost:8898)
7. vue 本地开发需要先运行 `npm run build` 然后刷新页面, 或者本地运行 `npm run dev` 