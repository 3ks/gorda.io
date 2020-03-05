---
title: "草稿纸"
date: 2020-03-01T23:07:56+08:00
tags: ["none",]
draft: true 

---

# cp -f 依然提示是否覆盖

[linux cp拷贝覆盖不提示](https://blog.csdn.net/sunny05296/article/details/78607277)

# 网页指定 favicon

[设置favicon的几种方式](https://blog.csdn.net/YLXB2/article/details/53336962)

# 服务器加速

建站 TCPA
带宽 BBR(PLUS)
买 CN2 GIA-E？
试试 trojan？

# 路线流程

- 安装 proxmox 
- 基于 cloud-init 快速初始化多个节点
- 基于 [kubespray](https://github.com/kubernetes-sigs/kubespray#requirements) 快速安装安装 k8s 高可用集群

# 还不知道怎么弄的下一步

- 快速安装 Istio
- 自动部署项目
- 快速安装一堆组件，监控，可视化，日志等

# 需要持久化的内容

- 各种数据（数据库/缓存/网络文件系统等）
- 各种文件（软件包/镜像等），以加快二次下载速度（是否可行？）
- 项目内容（代码/配置/环境变量/脚本等），放在代码仓库

# 目标

全流程自动化（节点 -> k8s 集群 -> Istio -> 项目）

# 问题记录

- 未订阅的情况下，proxmox 每个虚拟机只能有一个备份

# 博客分类

日志（主页）
系列文章
Tags
实验室
杂文
关于我

# 目录

序章
概念原理
数据平面
控制平面
流量管理
安全
多集群部署
日志监控和追踪
策略和遥测
性能和可伸缩性
最佳实践


序章
概念原理及架构
  服务网格是什么？
  服务网格架构
  Istio 是什么？
  Istio 架构
  现状及前景
安装并使用 Istio
  安装 k8s
  安装 Istio
  示例（如 Bookinfo）
基础功能及用法（对涉及到的名词、术语做介绍，也可以简单介绍相关的原理等）
  流量管理
  安全
  策略
  可观察性
配置详解
  流量管理
  安全
  策略
  可观察性
组件/源码分析
  xDS 协议
  Pilot
  Mixer
部署架构及迁移路线等
展望
附录：
  名词表
  术语表
  全景图 
  
  
  
序章
概念原理及架构
  服务网格是什么？
  服务网格架构
  Istio 是什么？
  Istio 架构
  现状及前景
安装并使用 Istio
  安装 k8s
  安装 Istio
  示例（如 Bookinfo）
流量管理 Envoy
  基础功能及用法
  配置详解
  组件/源码分析
策略 Pilot
  基础功能及用法
  配置详解
  组件/源码分析
可观察性 Mixer 
  基础功能及用法
  配置详解
  组件/源码分析
安全 Citadel
  基础功能及用法
  配置详解
部署架构及迁移路线等
展望
附录：
  名词表
  术语表
  全景图