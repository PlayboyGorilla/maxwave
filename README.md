[**English**](https://github.com/PlayboyGorilla/maxwave/blob/main/README_en.md)

# 关于Maxwave Proxifier
Maxwave Proxifier是一个基于规则的隧道/代理客户端。它与流行的系列软件clash具有相同的功能，而Maxwave Proxifier使用C语言构造自身的内核，并以C++构造了自身的图形界面。技术栈的选择似的Maxwave Proxifier与同类产品相比具有很高的执行效率，并占用更小的内存。

Maxwave Proxifier当前支持如下协议：

```
1. SSH Tunnel
2. HTTPs/HTTP Connect
3. SOCKS5
4. SOCKS5 over TLS
5. SOCKS4/4a
6. Shadowsocks
7. VMESS
8. Trojan
9. IMAP Tunnel (自制的代理协议，即将开源)
```

Maxwave Proxifier支持导入.conf格式，以及clash YAML格式的规则。

目前为止, Maxwave Proxifier支持的操作系统包括：**Android**, **x86_64的Windows**, 以及**Intel以及苹果M系列处理器的MacOS**. 对于Linux系统的支持很快就会释出。

# 使用指南
[**基本用法快速上手**](tutorial/101_zh.md)

# Maxwave Proxifier的优势
1. 支持SSH隧道
2. 支持任意类型、任意数量组成的多级代理
3. 同时支持.conf格式以及clash YAML格式的配置文件
4. 数据引擎由C代码写成，界面由C++写成。具有极高的执行效率和相对很小的内存使用
5. 更好的安全性 - 全远端代理解析DNS, 杜绝DNS泄漏

# 关于 Maxwave VPN
基于Maxwave Proxifier同款引擎的VPN引用。免费、免配置，下载可用的VPN. 目前支持的操作系统包括**Android**, **x86_64的Windows**, 以及**Intel以及苹果M系列处理器的MacOS**。

# 下载
|Release|操作系统|版本|下载链接|外部链接|
|---|---|---|---|---|
|Maxwave Proxifier for Windows|Windows for x86_64|1.2.0|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveProxifier_for_PC_v1.2.0)|N/A|
|Maxwave Proxifier for MacOS|MacOS for arm64 and x86_64|1.2.0|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveProxifier_for_PC_v1.2.0)|N/A|
|Maxwave Proxifier for Linux amd64|Debian/Ubuntu for x86_64|1.2.0|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveProxifier_for_PC_v1.2.0)|N/A|
|Maxwave Proxifier for Linux arm64|Debian/Ubuntu for aarch64/arm64|1.2.0|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveProxifier_for_PC_v1.2.0)|N/A|
|Maxwave Proxifier for Android|Android|1.6.9|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveProxifier_for_Android_v1.6.9)|[Google Play](https://play.google.com/store/apps/details?id=com.gorillakanzi.catrious)|
|Maxwave VPN for Mac|MacOS for arm64 and x86_64|1.6.0|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveVPN_for_Mac_v1.6.0)|N/A|
|Maxwave VPN for Windows|Windows for x86_64|1.6.0|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveVPN_for_Windows_x64_v1.6.0)|N/A|
|Maxwave VPN for Android|Android|1.4.5|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveVPN_for_Android_v1.4.5)|[Google Play](https://play.google.com/store/apps/details?id=com.maxwave.vpn)|
