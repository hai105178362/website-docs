---
title: 控制面到节点通信
content_type: concept
weight: 20
---

本文列举控制面节点（确切说是 API 服务器）和 Kubernetes 集群之间的通信路径。
目的是为了让用户能够自定义他们的安装，以实现对网络配置的加固，使得集群能够在不可信的网络上
（或者在一个云服务商完全公开的 IP 上）运行。
