```markdown
# v2ray-agent

> Xray-core / sing-box 一键脚本快速安装 —— 专业级代理工具集，支持多协议、多核心、自动 TLS 等丰富功能。

## 功能一览

- 多核心支持：无缝切换 Xray-core 与 sing-box，灵活适配不同网络环境
- 多协议支持：VLESS、VMess、Trojan、Hysteria2、Tuic、NaiveProxy 等主流协议
- 自动 TLS：自动申请与续订 SSL 证书，安全无忧
- 简易管理：提供交互式菜单，轻松管理用户、端口、配置
- 订阅系统：一键生成并管理订阅链接，方便客户端同步
- 分流管理：内置 WireGuard、IPv6、Socks5、DNS、VMess(ws)、SNI 反向代理，助力解锁流媒体、规避 IP 验证
- 目标域名管理：域名黑名单机制，精准屏蔽指定网站
- BT 下载管理：有效禁用 P2P 及 BT 下载，保障服务器资源

## 相关资源

- 官网广告：欢迎访问 [FreeShell.CC] (https://freeshell.cc) —— 免费、好用的 SSH 终端软件。
- 项目许可证：本脚本项目基于 [AGPL-3.0 许可证](LICENSE) 授权，请遵守相应条款。

```

## 快速开始

安装脚本版（推荐）

```bash
wget -P /root -N --no-check-certificate "https://freeshell.cc//shell/install.sh" && chmod 700 /root/install.sh && /root/install.sh
```

安装完成后，使用以下命令打开管理菜单：

```bash
vasma
```

安装 Docker 版

```bash
wget -P /root -N --no-check-certificate "https://freeshell.cc/shell/docker_reality.sh" && chmod 700 /root/docker_reality.sh && /root/docker_reality.sh
```

安装完成后，同样使用以下命令管理：

```bash
vasma
```

## 提示

- 脚本运行环境建议为 Ubuntu 20.04+ / Debian 10+ / CentOS 7+
- 需要 root 权限 执行安装
- 首次安装会自动配置防火墙、时间同步等基础环境
