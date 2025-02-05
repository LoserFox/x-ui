# x-ui Misaka 魔改优化版

支持多协议多用户的 xray 面板

## 安装命令

```shell
wget -N --no-check-certificate https://raw.githubusercontents.com/Misaka-blog/x-ui/main/install.sh && bash install.sh
```

快捷方式：`x-ui`

## 建议系统

* CentOS 7+
* Ubuntu 16+
* Debian 9+

## 功能介绍

* 系统状态监控
* 支持多用户多协议，网页可视化操作
* 支持的协议：vmess、vless、trojan、shadowsocks、shadowsocks 2022、dokodemo-door、socks、http
* 支持配置更多传输配置
* 流量统计，限制流量，限制到期时间
* 可自定义 xray 配置模板
* 支持 https 访问面板（请自行准备域名 + ssl 证书）
* 支持纯IPv4、纯IPv6及原生双栈VPS
* 支持 amd64、arm64、s390x CPU架构的VPS
* 支持 Telegram Bot 提醒面板，SSH登录信息、流量使用情况

## 常见问题

1. 关于SS2022无法启动，面板提示error情况

详细见 https://github.com/Misaka-blog/x-ui/issues/15

## 感谢列表

X-ui 原作：https://github.com/vaxilu/x-ui

FranzKafkaYu 魔改版：https://github.com/FranzKafkaYu/x-ui
