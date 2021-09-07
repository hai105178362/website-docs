---
title: 在 Linux 系统中安装并设置 kubectl
weight: 10
---


## 准备开始


kubectl 版本和集群版本之间的差异必须在一个小版本号内。
例如：v1.22 版本的客户端能与 v1.21、 v1.22 和 v1.23 版本的控制面通信。 用最新版的 kubectl 有助于避免不可预见的问题。

## 在 Linux 系统中安装 kubectl 


在 Linux 系统中安装 kubectl 有如下几种方法：


- [用 curl 在 Linux 系统中安装 kubectl](#install-kubectl-binary-with-curl-on-linux)
- [用原生包管理工具安装](#install-using-native-package-management)
- [用其他包管理工具安装](#install-using-other-package-management)
