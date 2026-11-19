# 免费云原生 / 运维课程地图

把「云原生 + 运维 + 后端」这条学习路线拆成 30 个主题，每个主题列出**免费、公开、可长期访问**的视频课与官方文档。所有链接都经过实测，不只靠搜索引擎快照。

> 说明：本仓库只是**学习路线的公开资源对照表**，不收录任何付费课程内容；所有资源版权归原作者，链接指向其原始发布页。

## 怎么用

- 按主题找课：在[主题索引](#主题索引)里选方向，或直接看 [`courses.json`](courses.json)。
- 缺什么补什么：每个主题下的 `topics` 就是该主题该覆盖的知识点。
- 自己加课：见 [CONTRIBUTING.md](CONTRIBUTING.md)，**本仓库接受外部提交**。

## 数据格式

```json
{ "id": "13", "title": "Kubernetes", "topics": ["云原生架构组件"], "resources": [
  { "title": "…", "author": "…", "url": "https://…", "type": "video", "episodes": 61, "covers": "…", "verified": "2026-11-19" } ] }
```

字段：`type` 为 `video` 或 `doc`；`episodes` 为 B 站分 P 数；`verified` 是最近一次实测可访问的日期。

## 主题索引

| # | 主题 | 免费资源 |
|---|---|---|
| 01 | [Linux系统管理](#01-Linux系统管理) | 2 条 |
| 02 | [shell开发实战](#02-shell开发实战) | 4 条 |
| 03 | [分布式集群架构实战](#03-分布式集群架构实战) | 4 条 |
| 04 | [mysql高级DBA实战](#04-mysql高级DBA实战) | 2 条 |
| 05 | [redis缓存](#05-redis缓存) | 2 条 |
| 06 | [kafka架构与实战](#06-kafka架构与实战) | 3 条 |
| 07 | [秒杀系统设计](#07-秒杀系统设计) | 4 条 |
| 08 | [同城双活、两地三中心、异地多活](#08-同城双活、两地三中心、异地多活) | 3 条 |
| 09 | [sre网站稳定性建设](#09-sre网站稳定性建设) | 4 条 |
| 10 | [分布式集群架构演进及分库分表分区](#10-分布式集群架构演进及分库分表分区) | 4 条 |
| 11 | [Ansible应用与剧本开发实战](#11-Ansible应用与剧本开发实战) | 4 条 |
| 12 | [容器技术成神之路](#12-容器技术成神之路) | 4 条 |
| 13 | [k8s云原生从入门到深入实战](#13-k8s云原生从入门到深入实战) | 4 条 |
| 14 | [k8s定制开发及底层源码剖析](#14-k8s定制开发及底层源码剖析) | 4 条 |
| 15 | [k8s实战进阶](#15-k8s实战进阶) | 3 条 |
| 16 | [prometheus监控实战](#16-prometheus监控实战) | 3 条 |
| 17 | [日志收集与分析架构ELK、EFK、Loki从原理到实战](#17-日志收集与分析架构ELK、EFK、Loki从原理到实战) | 4 条 |
| 18 | [某大厂云原生项目-智慧城市-AI图像识别](#18-某大厂云原生项目-智慧城市-AI图像识别) | 4 条 |
| 19 | [某大厂研发效能项目-微服务容器云平台环境治理](#19-某大厂研发效能项目-微服务容器云平台环境治理) | 4 条 |
| 20 | [赠送项目-k8s CICD项目](#20-赠送项目-k8s-CICD项目) | 4 条 |
| 21 | [赠送项目-分布式存储ceph项目](#21-赠送项目-分布式存储ceph项目) | 4 条 |
| 22 | [python开发](#22-python开发) | 4 条 |
| 23 | [CMDB项目（python全栈开发）](#23-CMDB项目（python全栈开发）) | 4 条 |
| 24 | [Ubuntu24.04.3LTS版最新k8s1.34架构部署实战](#24-Ubuntu24.04.3LTS版最新k8s1.34架构部署实战) | 3 条 |
| 25 | [大规模k8s集群网络架构与高性能深入](#25-大规模k8s集群网络架构与高性能深入) | 4 条 |
| 26 | [k8s定制开发项目-生产环境调度不均衡问题复现与超卖源码开发实战](#26-k8s定制开发项目-生产环境调度不均衡问题复现与超卖源码开发实战) | 4 条 |
| 27 | [k8s云原生GPU算力相关](#27-k8s云原生GPU算力相关) | 5 条 |
| 28 | [生产环境全链路灰度方案](#28-生产环境全链路灰度方案) | 4 条 |
| 29 | [gitOps、AgoCD、jenkinsCI以及泳道环境设计](#29-gitOps、AgoCD、jenkinsCI以及泳道环境设计) | 4 条 |
| 30 | [面向必备-高薪offer之道](#30-面向必备-高薪offer之道) | 3 条 |

## 01 · Linux系统管理

**该覆盖的知识点**：Linux 安装与网络配置、用户与权限管理、包管理与自定义源、磁盘分区与 LVM、进程与系统负载、内核与网络栈、ssh 与 cron、iptables/firewalld

- 🎬 [【全748集】目前B站最全最细的云计算Linux零基础全套教程，2026最新版，包含所有干货！七天就能从小白到大神！少走99%的弯路！存下吧！很难找全的！](https://www.bilibili.com/video/BV14PDxBVEpT) — 云计算入门到精通，61 P
  - 覆盖：硬件组成/安装与目录/用户组权限/进程管理/软件包管理/磁盘与LVM/cron/ssh/防火墙
- 🎬 [【2026最新】Linux操作系统教程，很全，适合自学党！Linux运维必看！零基础自学到精通有这一套课程就够了！](https://www.bilibili.com/video/BV1gX4i6oEMv) — 喝茶敲代码修电脑，31 P
  - 覆盖：系统安装/远程登录/权限/vim/磁盘/进程/服务与定时任务/内核机制

## 02 · shell开发实战

**该覆盖的知识点**：脚本编写规范与执行方式、变量、参数与表达式、流程控制与条件判断、实战脚本、函数与数组、expect 免交互、grep/sed/awk 文本三剑客

- 🎬 [【2025新版】B站强推【Shell脚本编程课程】从零基础入门到精通，（shell脚本_shell自动化运维_shell编程）运维工程师必看！](https://www.bilibili.com/video/BV1PHQzYXEyt) — 跟着小帅学编程，44 P
  - 覆盖：脚本规范/变量/流程控制/实战脚本/函数
- 🎬 [【2025新版】Linux三剑客全套教程！从零到实战一套搞定（Linux运维学习极速入门，零基础必备）包含grep、sed、awk入门到精通有这一套足够了！](https://www.bilibili.com/video/BV18cEczjEvi) — 跟着小常学编程，61 P
  - 覆盖：grep与正则/sed/awk
- 🎬 [Linux Bash Shell脚本编程入门 中英字幕 1080P](https://www.bilibili.com/video/BV17ZRWBPEh8) — 码农的洋墨水，3 P
  - 覆盖：条件判断/循环/函数/重定向
- 🎬 [expect编程](https://www.bilibili.com/video/BV1zM411r71r) — DreamNotOver，1 P
  - 覆盖：expect 免交互自动化

## 03 · 分布式集群架构实战

**该覆盖的知识点**：网络分层与协议基础、虚拟化与 SDN、集群性能指标、CDN 原理与落地、LVS/nginx/haproxy 负载均衡、keepalived 高可用、HTTP 协议与抓包、应用部署与 tomcat、nginx 性能优化、HTTPS 与证书

- 🎬 [尚硅谷Linux集群教程(linux集群经典之作)](https://www.bilibili.com/video/BV1Db411G7pf) — 尚硅谷，66 P
  - 覆盖：LVS三模式/keepalived高可用/多级负载/CDN
- 🎬 [强推！不愧是B站最详细讲解的【Nginx高级】系列课程教程，让你自学nginx少走99%的弯路！入门必须懂功能配置 Web服务器/反向代理/负载均衡](https://www.bilibili.com/video/BV1NaPdePE7Y) — 鹅厂编程高工手记，73 P
  - 覆盖：OSI/IO模型/nginx虚拟主机/负载均衡
- 🎬 [【全80集】Nginx零基础到精通教程，从浅入深讲解（适合小白学习）](https://www.bilibili.com/video/BV18fAAznEnz) — 暴龙Boy，80 P
  - 覆盖：rewrite/反向代理/SSL与HTTPS/动静分离
- 🎬 [2025最新最详细教程完整版【Nginx架构实战】从入门到实战一套搞定，运维技术猛涨！！（反向代理 负载均衡 动静分离）学不会我倒立洗头！](https://www.bilibili.com/video/BV1JBcveZEQK) — 跟着小琪学编程，27 P
  - 覆盖：TCP/HTTP协议/三次握手/socket/nginx架构

## 04 · mysql高级DBA实战

**该覆盖的知识点**：SQL 开发与权限、存储引擎、索引与慢查询优化、事务与 redo/undo、锁机制与隔离级别、备份恢复与迁移、主从复制与 MHA、MySQL 8.0 新特性

- 🎬 [【MySQL教程】这绝对是你看过最好的MySQL数据库教程完整版全集，从底层原理到mysql调优实战及面试题全讲明白了！整整6小时（建议收藏）](https://www.bilibili.com/video/BV1UcKoz6E4S) — 图灵学院官方，39 P
  - 覆盖：索引B+树/执行计划/InnoDB/redo-undo/ACID/隔离级别/锁与MVCC/8.0特性
- 🎬 [MYSQL数据库主从复制及MHA高可用改造](https://www.bilibili.com/video/BV1yo17BTEsD) — 混合云架构师星海，1 P
  - 覆盖：主从复制原理/binlog格式/MHA切换

## 05 · redis缓存

**该覆盖的知识点**：持久化 RDB/AOF、缓存穿透/击穿/雪崩、主从、哨兵与集群、双写一致性与延时双删、CAP 与一致性模型、canal 订阅 binlog、大 key 治理

- 🎬 [黑马Redis进阶教程，分布式缓存，多级缓存，Redis企业实践经验总结](https://www.bilibili.com/video/BV1xF411R7Z9) — 黑马Java，49 P
  - 覆盖：RDB-AOF/主从/哨兵/分片集群/Canal/BigKey
- 🎬 [【2026版】这可能是B站唯一将Redis实战全套讲明白的教程，涵盖redis底层原理，redis分布式锁，高并发场景缓存穿透、击穿、雪崩，redis数据结构](https://www.bilibili.com/video/BV1EgvpBmES6) — 12点就睡的林同学，33 P
  - 覆盖：IO多路复用/持久化/穿透击穿雪崩/双写一致性

## 06 · kafka架构与实战

**该覆盖的知识点**：生产消费模型、削峰填谷、分区与多副本、ack 策略、消息存储与稀疏索引、pull/push 消费、客户端示例

- 🎬 [尚硅谷Kafka教程(消息队列kafka快速入门)](https://www.bilibili.com/video/BV1a4411B7V9) — 尚硅谷，43 P
  - 覆盖：架构/topic分区/稀疏索引/ACK/ISR/消费者组/削峰
- 🎬 [B站讲的最细的Kafka从入门到实战全套视频教程（2025最新版），带你彻底掌握kafka底层原理与案例源码！比啃书效果好多了！](https://www.bilibili.com/video/BV1R1YCzjEhv) — 大模型碎碎念，15 P
  - 覆盖：集群搭建/客户端/分区路由/幂等与事务
- 🎬 [Kafka集群从零到高可用](https://www.bilibili.com/video/BV1zdjq67EfV) — onedayhigh，1 P
  - 覆盖：副本与ISR/ZK与KRaft部署

## 07 · 秒杀系统设计

**该覆盖的知识点**：秒杀场景高性能设计、高一致性方案、高可用方案、动静分离与缓存、库存扣减与防超卖、流量削峰

- 🎬 [B站强推！这绝对是2026年讲的最好的Java高并发秒杀系统核心架构教程，涵盖所有面试核心知识点，让你少走99%弯路](https://www.bilibili.com/video/BV1Vr5k6jE8B) — 图灵教育-诸葛，9 P
  - 覆盖：CDN静态化/多级限流/Redis+Lua预扣减/MQ削峰/防超卖
- 🎬 [优极限【完整项目实战】半天带你用-springBoot、Redis轻松实现Java高并发秒杀系统-我们要能够撑住100W级压力](https://www.bilibili.com/video/BV1sf4y1L7KE) — 乐字节xyx小可爱qwq，66 P
  - 覆盖：页面静态化/预减库存/乐观锁/接口防刷
- 🎬 [这绝对是你2025见过的高质量Redis缓存架构实战，解决缓存穿透/缓存与数据库双写不一致问题，少走99%弯路！](https://www.bilibili.com/video/BV1Mj7WzrEEF) — 小七七是仙女呐，10 P
  - 覆盖：冷热分离/缓存击穿穿透/热点重建
- 🎬 [中科大郑老师《计算机网络》之 内容分发网络CDN](https://www.bilibili.com/video/BV1ca4y1x7rb) — 中科大-郑烇老师，1 P
  - 覆盖：CDN原理与调度

## 08 · 同城双活、两地三中心、异地多活

**该覆盖的知识点**：冷备与热备、同城双活、两地三中心、异地多活架构

- 🎬 [服务稳定性建设高可架构与多活治理](https://www.bilibili.com/video/BV1PXDSYEEQJ) — dbaplus社群，1 P
  - 覆盖：同城/异地多活/单元化
- 🎬 [「HCIE 2.0（云服务）综合实验（两地三中心）」01_实验介绍](https://www.bilibili.com/video/BV11s4y187oR) — 拂晓的海洋，1 P
  - 覆盖：两地三中心规划实施
- 🎬 [千万 QPS 架构，第 138 讲：「异地多活：从灾备到常态」](https://www.bilibili.com/video/BV1AaLp6yESX) — 柒衡科技柯杰
  - 覆盖：冷备热备到多活演进

## 09 · sre网站稳定性建设

**该覆盖的知识点**：稳定性指标 SLA/SLO、微服务雪崩、限流与令牌桶、熔断与降级、预案与稳定性建设

- 🎬 [SLO运营体系与报警：如何从工程理论探索到最佳实践](https://www.bilibili.com/video/BV1JHDSYzEGD) — dbaplus社群，1 P
  - 覆盖：SLA-SLO-SLI/稳定性体系
- 🎬 [什么叫熔断和降级？](https://www.bilibili.com/video/BV1AuKz6wEEa) — 计算机大白话
  - 覆盖：熔断三态与降级兜底
- 🎬 [180分钟带你手写面试常问四种分布式限流算法，Java面试少走99%弯路](https://www.bilibili.com/video/BV1DF4m1L7fi) — AI智能体实战课，11 P
  - 覆盖：计数器/滑窗/漏桶/令牌桶
- 🎬 [Google SRE 对待故障应急处理的方法论](https://www.bilibili.com/video/BV1eH4y1M7eV) — 中国DevOps社区，1 P
  - 覆盖：预案与故障演练

## 10 · 分布式集群架构演进及分库分表分区

**该覆盖的知识点**：单体到多级缓存演进、数据库集群与读写分离、垂直/水平拆分、分库分表中间件、TiDB 分布式数据库、搜索引擎与 ES

- 🎬 [尚硅谷Sharding Sphere，Sharding JDBC，分库分表利器，数据库中间件](https://www.bilibili.com/video/BV1LK411s7RX) — 尚硅谷，23 P
  - 覆盖：垂直水平拆分/分片算法/读写分离
- 🎬 [17.MySQL集群解决方案（主从复制、PXC集群、MyCat、HAProxy）](https://www.bilibili.com/video/BV1R4411s7zi) — 姑苏第一包子，27 P
  - 覆盖：读写分离与中间件
- 🎬 [【赵渝强老师】TiDB数据库从零开始](https://www.bilibili.com/video/BV18QofYaEwp) — 赵渝强老师，1 P
  - 覆盖：TiDB/TiKV/PD架构
- 🎬 [【尚硅谷】ElasticSearch教程入门到精通（基于ELK技术栈elasticsearch 7.x+8.x新特性）](https://www.bilibili.com/video/BV1hh411D7sb) — 尚硅谷
  - 覆盖：倒排索引/集群分片/DSL

## 11 · Ansible应用与剧本开发实战

**该覆盖的知识点**：ad-hoc 与 playbook、变量层级与 facts、流程控制与异常处理、jinja2 模板、roles 与剧本复用

- 🎬 [ansible和playbook和role运维实战教程](https://www.bilibili.com/video/BV1oX4y1z7Kr) — 运维实战课程，11 P
  - 覆盖：ad-hoc/playbook/变量facts/roles
- 🎬 [Ansible入门到精通，零基础入门Ansible自动化运维](https://www.bilibili.com/video/BV1KSXKBZE3Z) — 高鲲教育，8 P
  - 覆盖：模块/playbook应用
- 🎬 [70分钟一口气学完ansible自动化运维！带你掌握ansible所有核心知识点，全程干货，无废话！](https://www.bilibili.com/video/BV1kN4y187YM) — 一起学运维，49 P
  - 覆盖：register变量/jinja2模板
- 📄 [Using Ansible playbooks &mdash; Ansible Community Documentation](https://docs.ansible.com/ansible/latest/playbook_guide/index.html) — Ansible Community
  - 覆盖：官方playbook/roles文档

## 12 · 容器技术成神之路

**该覆盖的知识点**：虚拟化与容器原理、手写容器引擎、OCI/containerd/runc、docker 网络模式、cgroup 与性能隔离、容器 GPU

- 🎬 [手撕迷你Docker：200行C代码实现容器的namespace+cgroup+overlayfs](https://www.bilibili.com/video/BV1gAXhBTEJz) — DeeparchWorks
  - 覆盖：手写容器引擎/三大支柱
- 🎬 [Linux命令精讲之docker进阶-底层原理](https://www.bilibili.com/video/BV1Ljn56nETz) — 全栈二把刀
  - 覆盖：OCI/containerd与runc
- 🎬 [40分钟的Docker实战攻略，一期视频精通Docker](https://www.bilibili.com/video/BV1THKyzBER6) — 技术爬爬虾，1 P
  - 覆盖：镜像容器/网络模式
- 🎬 [容器里也能跑GPU？Docker 拿到显卡的全过程，完整拆解！](https://www.bilibili.com/video/BV1LVHr6wEv2) — 内核聊内核，1 P
  - 覆盖：GPU透传与nvidia-container-runtime

## 13 · k8s云原生从入门到深入实战

**该覆盖的知识点**：云原生架构组件、List-Watch 机制、kubeadm/二进制安装、资源对象操作、Pod 创建与调度流程、CNI（flannel/calico）、控制器与 HPA

- 🎬 [【尚硅谷】Kubernetes（k8s）入门到实战教程丨全新升级完整版](https://www.bilibili.com/video/BV1GT4y1A756) — 尚硅谷
  - 覆盖：架构/安装/资源/网络/控制器/Helm
- 🎬 [Kubernetes(K8S) 入门进阶实战完整教程，黑马程序员K8S全套教程（基础+高级）](https://www.bilibili.com/video/BV1Qv41167ck) — 黑马Java，85 P
  - 覆盖：集群安装/Pod/Service/网络/HPA
- 🎬 [K8s/Kubernetes 完整教程，从集群部署、Pod/Service 到 Ingress、ConfigMap 与容器编排实战，老男孩运维带你吃透企业级云原](https://www.bilibili.com/video/BV1e2s269EBt) — 老男孩IT教育
  - 覆盖：部署与资源操作
- 🎬 [K8s入门到精通，B站最火k8s教程，Kubernetes实战](https://www.bilibili.com/video/BV1w4411y7Go) — 尚硅谷，70 P
  - 覆盖：List-Watch/kubeadm/Flannel/Pod流程

## 14 · k8s定制开发及底层源码剖析

**该覆盖的知识点**：API 设计与版本、CRD 与 CR、client-go 与 informer、Operator 开发、admission webhook、源码剖析

- 🎬 [2022年最新k8s编程operator篇-12.自定义资源(CRD)简介](https://www.bilibili.com/video/BV1LY4y1i7Ly) — 账号注销20241001，1 P
  - 覆盖：CRD与Operator模型
- 🎬 [2022年最新k8s编程operator篇-11.client-go项目实战(下)：部署](https://www.bilibili.com/video/BV1hS4y1m7CT) — 账号注销20241001，1 P
  - 覆盖：client-go与controller实现
- 🎬 [一、3、k8s二次开发之如何扩展kubernetes系统](https://www.bilibili.com/video/BV12F411a7qR) — AIOps架构师，1 P
  - 覆盖：CRD/Aggregator/Webhook扩展方式
- 🎬 [【2023最新版】k8s进阶教程教程，带你0基础成为k8s架构师，解决各种实践中所遇到的问题（临时容器，Ratel，准入控制，服务质量QoS，权限管理）](https://www.bilibili.com/video/BV1LL411z7cE) — 凉柚船长，28 P
  - 覆盖：准入控制与权限

## 15 · k8s实战进阶

**该覆盖的知识点**：ConfigMap 与 Secret、RBAC 认证授权、Service 与 Ingress、灰度与金丝雀、CoreDNS 与服务发现、调度：亲和/污点/拓扑、descheduler 与驱逐、存储卷与 StorageClass、Helm 与高可用升级

- 🎬 [【尚硅谷】Kubernetes（k8s）入门到实战教程丨全新升级完整版](https://www.bilibili.com/video/BV1GT4y1A756) — 尚硅谷
  - 覆盖：ConfigMap-Secret/Service/Ingress/DNS/调度/存储/Helm
- 🎬 [Kubernetes(K8S) 入门进阶实战完整教程，黑马程序员K8S全套教程（基础+高级）](https://www.bilibili.com/video/BV1Qv41167ck) — 黑马Java，85 P
  - 覆盖：Service/Ingress/调度存储
- 🎬 [【全站第一】Kubernetes零基础入门到精通教程 |【K8S教程】【适合小白】](https://www.bilibili.com/video/BV1etn3zxEAP) — 河馬大王，198 P
  - 覆盖：Service/Ingress/存储/Helm

## 16 · prometheus监控实战

**该覆盖的知识点**：架构与部署、exporter 与服务发现、PromQL、Grafana 出图、Alertmanager 与钉钉、prometheus-operator、blackbox 探测

- 🎬 [300分钟讲透Prometheus快速入门到实战全套教程 | Spring Boot整合Prometheus | k8s部署coredns监控！](https://www.bilibili.com/video/BV17vXeYaECa) — 图灵徐庶，14 P
  - 覆盖：架构/PromQL/exporter/服务发现
- 🎬 [花了八千多买的Prometheus教程全套，现在分享给大家，Prometheus监控入门到精通(运维开发教程)](https://www.bilibili.com/video/BV1m54y1o79r) — 拒绝加班的程序猿，48 P
  - 覆盖：Alertmanager/Grafana/K8s监控
- 🎬 [如何使用 Prometheus 监控 Kubernetes 集群？](https://www.bilibili.com/video/BV1Kn4y1o77w) — 大数据老司机，1 P
  - 覆盖：kube-state-metrics/operator体系

## 17 · 日志收集与分析架构ELK、EFK、Loki从原理到实战

**该覆盖的知识点**：日志采集方案、filebeat/logstash/fluentd、EFK + Kafka、ES 与 Kibana 部署、索引与出图、Loki

- 🎬 [【千锋教育】最新版ELK分布式日志处理解决方案（完整版）](https://www.bilibili.com/video/BV1XZ4y1M77Y) — 千锋教育，13 P
  - 覆盖：ES/Logstash/Kibana/Filebeat
- 🎬 [2025最新ElasticStack（ELK）ES日志收集实战项目视频教程（包括ElasticSearch、kibana、logstash）](https://www.bilibili.com/video/BV1P8ncz5EWd) — 老男孩IT，38 P
  - 覆盖：采集到出图全流程
- 🎬 [尚硅谷大数据Filebeat教程（filebeat日志采集系统）](https://www.bilibili.com/video/BV1WK41117dA) — 尚硅谷，9 P
  - 覆盖：Filebeat与Kafka对接
- 🎬 [Loki 实战，安装 Promtail，监控本地 Django 日志文件，上传 Loki 并通过 Grafana 搜索日志](https://www.bilibili.com/video/BV1d84y1i7Tc) — 程序猿小当家，1 P
  - 覆盖：Loki轻量日志方案

## 18 · 某大厂云原生项目-智慧城市-AI图像识别

**该覆盖的知识点**：HDFS/YARN/MapReduce、Spark 架构与运行模式、GPU 与 vGPU、Operator 开发实战

- 🎬 [Hadoop教程，大数据hadoop3.x搭建到集群调优（MapReduce、YARN、HDFS）](https://www.bilibili.com/video/BV1Qp4y1n7EN) — 尚硅谷，178 P
  - 覆盖：HDFS/YARN/MapReduce
- 🎬 [Spark视频教程，Spark3.x新版教程，一套搞定大数据Spark](https://www.bilibili.com/video/BV12142167BL) — 尚硅谷，157 P
  - 覆盖：Spark架构/RDD/on YARN
- 🎬 [1-K8S进阶必备技能：自定义资源CRD与Operator开发 | 干货教学 |零基础也可上手实践](https://www.bilibili.com/video/BV1itzyBJEHa) — 程序员暮闲，1 P
  - 覆盖：CRD/调谐/Operator发布
- 🎬 [GPU 虚拟化技术分享 - 王老师](https://www.bilibili.com/video/BV1gT411J7SE) — 泰晓科技，1 P
  - 覆盖：GPU虚拟化与vGPU

## 19 · 某大厂研发效能项目-微服务容器云平台环境治理

**该覆盖的知识点**：泳道设计、多 SET 环境、istio sidecar 流量接管、服务发现与寻址、分支与环境治理

- 🎬 [【Istio Workshop/教程】第八讲：Sidecar模式和透明流量劫持](https://www.bilibili.com/video/BV1cF411T72o) — 云原生社区，1 P
  - 覆盖：sidecar与流量劫持
- 🎬 [k8s服务网格(Service Mesh)的istio灰度发布产品实战教程](https://www.bilibili.com/video/BV1PRmhYsEAD) — 运维实战课程，9 P
  - 覆盖：VirtualService/DestinationRule
- 🎬 [平安银行端到端全链路灰度验证实践](https://www.bilibili.com/video/BV1GC4y1V7RQ) — dbaplus社群，1 P
  - 覆盖：泳道与多环境验证
- 🎬 [微服务中的服务注册与发现机制](https://www.bilibili.com/video/BV1Hvs6eBEyU) — 程序猿DD，1 P
  - 覆盖：注册发现

## 20 · 赠送项目-k8s CICD项目

**该覆盖的知识点**：Jenkins 主从与动态 slave、GitLab 与 Harbor、Jenkinsfile 流水线、发布与回滚

- 🎬 [68.基于 K8S 的动态 Jenkins Slave](https://www.bilibili.com/video/BV18z421i7oB) — im_bili_vip
  - 覆盖：动态slave
- 🎬 [44_第十九章Jenkins+Gitlab+Harbor+K8S自动构建镜像DevOPS平台](https://www.bilibili.com/video/BV1L5L6zFEw3) — 大有希萌神，1 P
  - 覆盖：全链路流水线
- 🎬 [30分钟jenkins+gitlab中pipeline流水线讲解](https://www.bilibili.com/video/BV1orUYBVEEX) — 椰奶不爱西米露，1 P
  - 覆盖：Jenkinsfile
- 🎬 [Harbor私有镜像仓库搭建与镜像管理实战教程](https://www.bilibili.com/video/BV1k6HezzENy) — ThinkMo，1 P
  - 覆盖：Harbor

## 21 · 赠送项目-分布式存储ceph项目

**该覆盖的知识点**：RADOS 与 PG、CRUSH 算法、cache tiering 与 bluestore、OpenStack 对接、运维与排障

- 🎬 [2小时轻松部署分布式存储Ceph高可用集群 【2小时纯干货输出】](https://www.bilibili.com/video/BV16a411j78Q) — 马哥教育实战，8 P
  - 覆盖：MON-OSD-MGR部署
- 🎬 [Ceph的存储原理](https://www.bilibili.com/video/BV1Wm4y1V74n) — 皇帝的新依-，1 P
  - 覆盖：RADOS/PG
- 🎬 [Ceph CRUSH算法(一）](https://www.bilibili.com/video/BV1be1cYBEXB) — wharton0，1 P
  - 覆盖：CRUSH
- 🎬 [Ceph对接OpenStack Glance](https://www.bilibili.com/video/BV1gY516EEcm) — zcloudedu，1 P
  - 覆盖：私有云对接

## 22 · python开发

**该覆盖的知识点**：Python 基础与数据类型、模块与包、面向对象、Socket 通信、并发编程、数据库开发、Django

- 🎬 [黑马程序员Python教程_600集Python从入门到精通教程（懂中文就能学会）](https://www.bilibili.com/video/BV1ex411x7Em) — 黑马程序员
  - 覆盖：基础/数据类型/OOP/模块
- 🎬 [Python Socket网络编程](https://www.bilibili.com/video/BV1a7411z75u) — 白月黑羽编程，5 P
  - 覆盖：Socket
- 🎬 [【2021最新版】Python 并发编程实战，用多线程、多进程、多协程加速程序运行](https://www.bilibili.com/video/BV1bK411A7tV) — 蚂蚁学Python，10 P
  - 覆盖：并发编程
- 📄 [编写你的第一个 Django 应用，第 1 部分 | Django 文档 | Django](https://docs.djangoproject.com/zh-hans/5.0/intro/tutorial01/) — Django基金会
  - 覆盖：Django入门

## 23 · CMDB项目（python全栈开发）

**该覆盖的知识点**：资产采集：Agent/SSH/SaltStack、Django API 与权限、Redis 缓存与 token、数据清洗入库、前端 ECharts

- 🎬 [【老男孩教育】python--CMDB资产管理系统项目 #完结](https://www.bilibili.com/video/BV11Z4y1s79H) — 逆风微笑的代码狗，61 P
  - 覆盖：CMDB全流程
- 🎬 [B站最全最细致的Python自动化运维从入门到精通！](https://www.bilibili.com/video/BV1Zb9iYMEjV) — 字节跳动大侠，170 P
  - 覆盖：资产采集/SSH
- 🎬 [Linux懒人运维：8分钟搞定SaltStack自动化工具安装和使用](https://www.bilibili.com/video/BV1iSanzHE9Q) — Linux懒人运维，1 P
  - 覆盖：Saltstack
- 🎬 [ECharts数据可视化项目-大屏数据可视化展示-echarts 图表制作-pink老师直播课更新完毕）](https://www.bilibili.com/video/BV1v7411R7mp) — 黑马pink讲前端，53 P
  - 覆盖：ECharts前端

## 24 · Ubuntu24.04.3LTS版最新k8s1.34架构部署实战

**该覆盖的知识点**：系统与静态网络规划、containerd 运行时、apt 仓库与 kubeadm、新版本部署验证

- 🎬 [01-如何基于Ubuntu 24.04操作系统部署原生K8S 1.31集群？本期内容介绍](https://www.bilibili.com/video/BV1heHre7EA3) — 慧闲大大，1 P
  - 覆盖：Ubuntu24.04+containerd+kubeadm
- 🎬 [【2026最新版】Containerd容器管理全流程攻略！从入门安装到管理精通，全程干货不废话~](https://www.bilibili.com/video/BV1inrrBLEVT) — 八方网域_老唐，21 P
  - 覆盖：containerd安装配置
- 🎬 [【k8s 1.37】集群部署避坑指南：装之前必须定好的 10 件事！｜AI大模型｜运维｜环境部署｜k8s教程｜k8s入门｜k8s项目｜k8s集群｜k8s部署](https://www.bilibili.com/video/BV1gTxq6WEK7) — 程序员阿杉，42 P
  - 覆盖：部署前置规划

## 25 · 大规模k8s集群网络架构与高性能深入

**该覆盖的知识点**：calico BGP 与 RR、overlay/underlay、vxlan/ipip、NetworkPolicy、eBPF 数据面

- 🎬 [11.K8S网络之calico bgp rr & ipip](https://www.bilibili.com/video/BV17L4y1t7Z1) — 七天01，1 P
  - 覆盖：calico BGP/RR/IPIP
- 🎬 [Flannel、Calico、Cilium 到底怎么选？三大 CNI 的底层路线之争](https://www.bilibili.com/video/BV1kVJ56bEpR) — 混合云架构师星海，1 P
  - 覆盖：CNI选型
- 🎬 [用 NetworkPolicy 控制 Kubernetes 的 Pod 网络联通和隔离](https://www.bilibili.com/video/BV1JZ4y117Nc) — OpenShift之家，1 P
  - 覆盖：NetworkPolicy
- 🎬 [01·Cilium 是什么？把网络、安全、可观测全塞进 eBPF｜Cilium 源码深读](https://www.bilibili.com/video/BV1AcH16dEon) — 隔岸的灯塔_，1 P
  - 覆盖：eBPF数据面

## 26 · k8s定制开发项目-生产环境调度不均衡问题复现与超卖源码开发实战

**该覆盖的知识点**：资源调度与打分、Scheduler 扩展、admission webhook 定制、requests/limits 与超卖

- 🎬 [阿里技术大牛 30 分钟讲透 Kubernetes : 调度器的调度流程和算法介绍](https://www.bilibili.com/video/BV12J411q7k4) — 程序员小叨，1 P
  - 覆盖：调度流程与算法
- 🎬 [#76 Kubernetes Scheduler 设计与实现 【 Go 夜读 】](https://www.bilibili.com/video/BV1N7411w7M9) — Go夜读
  - 覆盖：Scheduler Framework
- 🎬 [【Meetup 分享】深入浅出 K8s 准入控制](https://www.bilibili.com/video/BV13F4m1A75n) — KubeSphere，1 P
  - 覆盖：Admission Webhook
- 🎬 [K8s的资源配额与限制](https://www.bilibili.com/video/BV1czUfYwEwz) — 莲城的老李，1 P
  - 覆盖：requests/limits/超卖

## 27 · k8s云原生GPU算力相关

**该覆盖的知识点**：GPU 驱动与 CUDA、device-plugin、gpu-operator、vGPU 与虚拟化、容器内 GPU

- 🎬 [阿里技术大牛 30 分钟讲透 Kubernetes : GPU 管理和 Device Plugin 工作机制](https://www.bilibili.com/video/BV1BJ411i7Yo) — 程序员小叨，1 P
  - 覆盖：device-plugin
- 🎬 [13. k8s 的gpu operator 的部署测试](https://www.bilibili.com/video/BV1ZRkVB3E68) — YugeOps，1 P
  - 覆盖：gpu-operator
- 🎬 [CUDA编程基础入门系列（持续更新）](https://www.bilibili.com/video/BV1sM4y1x7of) — 程序口袋，24 P
  - 覆盖：CUDA编程
- 🎬 [【AI Infra 一小时入门】GPU、CUDA、vLLM、PyTorch、KV Cache、Triton、K8s、Ray，一次搞懂大模型背后的技术体系](https://www.bilibili.com/video/BV1Fuxf6aEgJ) — 鸽鸽王分王，1 P
  - 覆盖：算力全景
- 📄 [About the NVIDIA GPU Operator &#8212; NVIDIA GPU Operator](https://docs.nvidia.com/datacenter/cloud-native/gpu-operator/latest/index.html) — NVIDIA
  - 覆盖：官方文档

## 28 · 生产环境全链路灰度方案

**该覆盖的知识点**：istio 流量治理、灰度发布策略、全链路灰度

- 🎬 [k8s服务网格(Service Mesh)的istio灰度发布产品实战教程](https://www.bilibili.com/video/BV1PRmhYsEAD) — 运维实战课程，9 P
  - 覆盖：istio流量治理
- 🎬 [基于Istio 的灰度发布实现](https://www.bilibili.com/video/BV1Fm4y1A7x4) — Zack说AI，1 P
  - 覆盖：从0安装与切流
- 🎬 [全链路灰度发布实践(绝对干货)](https://www.bilibili.com/video/BV1D5F5zuEEK) — leaf-dev，3 P
  - 覆盖：全链路灰度设计
- 📄 [Istio / 流量管理](https://istio.io/latest/zh/docs/concepts/traffic-management/) — Istio
  - 覆盖：官方文档

## 29 · gitOps、AgoCD、jenkinsCI以及泳道环境设计

**该覆盖的知识点**：ArgoCD 与 GitOps、Jenkins CI 整合、泳道环境设计

- 🎬 [Argo CD 系列视频教程](https://www.bilibili.com/video/BV17F411h7Zh) — 开源面对面，13 P
  - 覆盖：GitOps/ArgoCD
- 🎬 [一小时玩转GitOps之ArgoCD](https://www.bilibili.com/video/BV1NJ3v6qE5b) — 王晓春老师，1 P
  - 覆盖：GitOps流水线
- 🎬 [【尚硅谷】Jenkins教程（从配置到实战）](https://www.bilibili.com/video/BV1bS4y1471A) — 尚硅谷
  - 覆盖：Jenkins Pipeline
- 📄 [Argo CD - Declarative GitOps CD for Kubernetes](https://argo-cd.readthedocs.io/en/stable/) — Argo Project
  - 覆盖：官方文档

## 30 · 面向必备-高薪offer之道

**该覆盖的知识点**：简历撰写与优化、投递策略、面试技巧与自我介绍、背调与职业规划

- 🎬 [大厂程序员带你做简历](https://www.bilibili.com/video/BV1meFyetENm) — over_z，1 P
  - 覆盖：简历写法
- 🎬 [3-8年后端开发简历优化：照着这样写，让HR连夜推你简历，面试邀约率提升200%！](https://www.bilibili.com/video/BV1kJ2vBJES4) — BIGBANG的vip呢，9 P
  - 覆盖：简历优化
- 🎬 [面试自我介绍：面试官让你自我介绍时，到底想听到什么？（含案例详解）【鹅姐|求职】](https://www.bilibili.com/video/BV1jy4y1j7N6) — 鹅姐职场，1 P
  - 覆盖：自我介绍与面试技巧

## 维护

- 校验日期：2026-11-19
- 校验方式：B 站链接通过 api.bilibili.com/x/web-interface/view 校验 BV 号、标题与 UP 主；文档链接校验 HTTP 200。共 109 条。
- 失效处理：连续两次校验失败即从表中移除，并在提交信息里注明。

## 许可

本仓库内容（表格、JSON、说明文字）以 [CC BY-SA 4.0](LICENSE) 许可发布：可自由复制、修改、商用，需署名并以相同协议共享。
链接指向的课程/文档版权归各自作者所有，不在本许可范围内。
