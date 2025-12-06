[**中文**](https://github.com/PlayboyGorilla/maxwave/blob/main/README.md)

# What is Maxwave Proxifier
Maxwave Proxifier is a rule-based tunneling application. It offers flexible configuration capability that allows users to fully control the network traffic on their device. Specifically it offers following system-wide features:

```
1. Certain sites or destination addresses can be blocked, allowing users to block malicious sites.
2. Traffic to certain sites or destination addresses can go through a designated proxy server, allowing privacy protection or censorship circumvention
3. A new DNS server can be specified by a user.
```

Maxwave Proxifier applies different actions to network traffic strictly based on the rule deployed by the user.

As a hub to forward designated network traffic through user-designated proxy servers, Maxwave Proxifier currently supports following proxy protocols:

```
1. SSH Tunnel
2. HTTPs/HTTP Connect
3. SOCKS5
4. SOCKS5 over TLS
5. SOCKS4/4a
6. Shadowsocks
7. VMESS
8. Trojan
9. IMAP Tunnel (A home-made tunneling protocol that will soon be open-source)
```

As of now, Maxwave Proxifier runs on **Android** devices, including phones, tablets and TVs, **Windows for x86_64** and **MacOS for arm64 and x86_64**. Support for Linux is on its way.

# Tutorial
[**Crash Course**](tutorial/101_zh.md)

# What is Maxwave VPN
Maxwave VPN is a simplified version of the proxifier. Rule sets are actively maintained by the developer team, sparing users of efforts to maintain their own rule sets. Also proxy servers are provided by the developers who collect and scrutinize free proxy servers on the Internet. The scrutinization is run by both programs and humans, so as to ensure their safety.

Maxwave VPN aims to minimize user efforts on configuration. The only configuration capability it provides is for users to specify their own DNS server.

Maxwave VPN provdes support for Android devices, including phones, tablets and TVs. In addition, it supports Windows and ***Mac OS, including both X86-based and the M1/M2-based Mac computers***.

# Why would you choose Maxwave Proxifier/VPN
1. Maxwave is completely free and Ad-free.
2. Maxwave has decent support of SSH tunnels, a protocol that is usually left out by similar products.
3. Maxwave supports proxy chains defined by any number of proxy servers of any types.
4. Core codes are written in C, which brings highly efficient data processing, low memory consumption and extended battery life on mobile devices.
5. Strict privacy safety - DNS resolve is done strictly on the proxy server. 
6. The projects are being actively maintained.

# Latest releases
|Release name|Support OS|Version|Download|External link|
|---|---|---|---|---|
|Maxwave Proxifier for Windows|Windows for x86_64|1.2.1|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveProxifier_for_PC_v1.2.1)|N/A|
|Maxwave Proxifier for MacOS|MacOS for arm64 and x86_64|1.2.1|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveProxifier_for_PC_v1.2.1)|N/A|
|Maxwave Proxifier for Linux amd64|Debian/Ubuntu for amd64|1.2.1|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveProxifier_for_PC_v1.2.1)|N/A|
|Maxwave Proxifier for Linux arm64|Debian/Ubuntu for arm64|1.2.0|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveProxifier_for_PC_v1.2.0)|N/A|
|Maxwave Proxifier for Android|Android|1.6.9|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveProxifier_for_Android_v1.6.9)|[Google Play](https://play.google.com/store/apps/details?id=com.gorillakanzi.catrious)|
|Maxwave VPN for Mac|MacOS for arm64 and x86_64|1.6.0|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveVPN_for_Mac_v1.6.0)|N/A|
|Maxwave VPN for Windows|Windows for x86_64|1.6.0|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveVPN_for_Windows_x64_v1.6.0)|N/A|
|Maxwave VPN for Android|Android|1.4.5|[Download](https://github.com/PlayboyGorilla/maxwave/releases/tag/MaxwaveVPN_for_Android_v1.4.5)|[Google Play](https://play.google.com/store/apps/details?id=com.maxwave.vpn)|
