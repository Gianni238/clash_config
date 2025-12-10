# 🛠️ My Clash Configs

![Clash](https://img.shields.io/badge/Clash-Configuration-blue?style=flat-square&logo=clash)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

这里存放个人日常使用的 Clash 配置文件、规则集（Rule Providers）以及脚本片段。主要用于多端同步与备份。

## 📂 目录结构说明

| 文件夹/文件 | 说明 | 备注 |
| :--- | :--- | :--- |
| **`/General`** | **完整配置** | 包含基础的分流策略和覆写设置 |
| `general.yaml` | 通用配置模板 | 适用于大多数桌面端 |
| `mobile.yaml` | 移动端精简配置 | 适用于 Clash for Android/Stash |
| **`/Rules`** | **分流规则** | 单独的规则文件 |
| `direct.list` | 直连列表 | 国内域名、公司内网等 |
| `proxy.list` | 代理列表 | 需要走节点的域名 |
| `reject.list` | 广告拦截 | 简单的广告过滤规则 |
| **`/Script`** | **脚本/插件** | JS 脚本或 Mixin 配置 |

## 🚀 如何使用

### 方式一：引用远程配置 (推荐)
在 Clash 客户端的配置文件下载栏（Profile / Import）中填入文件的 **Raw** 链接。

**CDN 加速链接格式 (推荐国内环境使用):**
```text
https://cdn.jsdelivr.net/gh/[你的GitHub用户名]/[仓库名称]@main/[文件路径]
