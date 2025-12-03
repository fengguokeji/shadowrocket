# Shadowrocket,小火箭,Shadowrocket官网,Shadowrocket,小火箭节点,小火箭订阅,科学上网,梯子.
## 适用于 iPhone/iPad/Apple TV/Mac(M系列芯片)  
Shadowrocket 是一款基于规则的代理实用程序客户端，适用于 iPhone、iPad 、Apple TV 和 Mac(M系列芯片)  

# [点击购买节点](https://dxfg.netlify.app/)

---
## 海外网站加速：加速访问Google、YouTube、Twitter、Instagram、GitHub等热门国际网站。

# 数据加密：全面加密您的数据，保护隐私安全

# 多平台兼容：支持iOS、安卓、Windows、Mac等多种设备。
# 超越50条线路，遍布全球多个地区，助您轻松穿越网络，无忧连接

### 主要特点

#### 🚀 不收集数据的 App
开发人员不会从此应用收集任何数据、连接、域名，用户可配置阻止广告。

#### 📱 适用于 iPhone/iPad/Apple TV 设备
支持 iOS 13 及以上版本，从头设计全功能应用。支持所有 HTTP/HTTPS/TCP 流量，并配置远程服务器。

#### ✍️ 本地地址重写
完全支持 IPv6，提供多种在线和离线格式支持，并允许请求重写。

#### 📊 网络流量统计
记录和显示应用在 iOS 设备中的 HTTP、HTTPS、DNS 请求、运营 WiFi、蜂窝数据流量等详细信息，增强网络连接管理。

#### 🔠 多种导入规则
URL 规则支持 Cloudflare 无服务器，支持托管配置及更灵活的脚本管理。

#### 🔗 支持多种终端代理
支持在终端环境上工作，兼容 trojan、cloak、gost、v2ray 核心等，并支持加密 DNS 及 QUIC 协议。

#### 🛠️ 支持多种配置规则
可批量编辑规则，支持按域名、域名前缀、端口、运营商、地理位置等多种条件编写代理规则。

#### 🎯 高精度匹配
提供多个匹配模式，支持完全匹配、子域名匹配、CIDR IP 段匹配及 GeoIP 规则。

#### 💻 实用的客户端
适用于 iPhone/iPad 终端的便捷代理客户端，增强用户网络管理体验。
# Shadowrocket 配置

## 简介
这是一个 **Shadowrocket**（小火箭）代理工具的配置仓库，提供**免费节点**、**订阅地址**和**规则集**，帮助用户实现**科学上网**和**代理分流**。支持 **socks5**、**Shadowsocks**、**Vmess** 等协议，适用于 iOS/macOS。

关键词：**Shadowrocket 配置**、**小火箭订阅**、**免费节点分享**、**代理规则**、**去广告脚本**。

## 功能特点
- **节点管理**：自动更新订阅、Ping 排序、节点筛选（e.g., **clash 节点**、**v2ray 订阅**）。
- **规则优化**：**GeoIP 规则**、**域名分流**（DOMAIN-SUFFIX, IP-CIDR）、**HTTPS 解密**。
- **模块支持**：**证书模块**、**URL 重写**、**DNS 劫持**，兼容 **Quantumult X** 和 **Surge**。
- **懒人配置**：一键导入 **lazy_group.conf**，支持 **iCloud 同步** 和 **流量统计**。

## 安装与使用
1. **订阅添加**：复制 URL（如 `https://example.com/subscribe`），在 Shadowrocket 中导入。
2. **规则导入**：下载 **ruleset** 文件，启用 **全局路由** 或 **场景模式**。
3. **配色主题**：安装 **模块**，自定义 **NavigationBarColor** 等。

示例配置（YAML 格式）：
```yaml
proxies:
  - name: "免费节点"
    type: socks5
    server: example.com
    port: 1080
rules:
  - DOMAIN-SUFFIX,google.com,PROXY
  - GEOIP,CN,DIRECT
