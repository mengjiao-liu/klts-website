---
title: "KLTS"
disableToc: true
---

## 终端用户指南

[详情](/zh/user-guide)

## 开发者指南

[详情](/zh/developer-guide)

## 关于

KLTS (Kubernetes Long Term Support)

Kubernetes 作为一个企业基础设施, 您不应该使用一个不再维护的 Kubernetes 版本。
KLTS 为 Kubernetes 官方不再维护的最新迭代版本进行维护, 以避免您的基础设置升级到较新版本 Kubernetes 版本, 
引入的一些暂时没用到的特性而引起的 Bug, 您只需要升级到只做小修补的 KLTS 补丁版本, 
让 Kubernetes 作为您的基础设施更加稳定.

KLTS 会在官方结束维护对某个版本结束维护后, 额外提供 2 年的该版本维护. 主要是修补 CVE 漏洞和较为严重的 bug.

KLTS 所有流程完全托管在 GitHub 上, 你可以直接 Fork 项目非常简单的构建属于您自己的的 Kubernetes 版本.
构建的产物将会全部存在 GitHub 上, 镜像将存在 GitHub Package, rpm 和 deb 包将存到同仓库的 repos 分支.
