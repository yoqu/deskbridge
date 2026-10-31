---
title: DeskBridge 隐私政策 / Privacy Policy
permalink: /privacy/
---

# DeskBridge 隐私政策 / Privacy Policy
更新日期 / Last updated: 2026-10-30

## 中文

DeskBridge 不收集、不上传、不出售任何个人数据。

- **没有服务器**：DeskBridge 只在你自己的两台 Mac 之间通信（雷电、以太网、Wi-Fi 或蓝牙局域网），不连接开发者或任何第三方的服务器，不包含统计、广告或崩溃上报 SDK。
- **键盘与鼠标**：DeskBridge 需要「辅助功能」权限，用来读取本机的键盘和鼠标输入并转发给你配对的另一台 Mac，以及在本机重放对端发来的输入。这些输入只经加密连接（Noise 协议，ChaCha20-Poly1305）发送给已配对的 Mac，不会被记录或保存。
- **剪贴板**：切换控制时，剪贴板内容（文字、图片、文件）会经同一条加密连接发送给已配对的 Mac。收到的文件暂存在应用自己的缓存目录，下一次接收时清除。
- **本机保存的数据**：设备名称、屏幕排列、已配对 Mac 的公钥，以及本机的身份密钥，只保存在本机的应用容器中，卸载应用即删除。

如有问题，请发邮件至 yoqulin@gmail.com。

## English

DeskBridge does not collect, upload, or sell any personal data.

- **No servers**: DeskBridge only talks between your own two Macs (Thunderbolt, Ethernet, Wi-Fi or Bluetooth PAN). It never contacts the developer's or any third-party servers and contains no analytics, advertising or crash-reporting SDKs.
- **Keyboard and mouse**: DeskBridge needs the Accessibility permission to read this Mac's keyboard and mouse input and forward it to the Mac you paired, and to replay input arriving from that Mac. Input travels only over an encrypted connection (Noise protocol, ChaCha20-Poly1305) to the paired Mac and is never logged or stored.
- **Clipboard**: When control switches, the clipboard (text, images, files) is sent to the paired Mac over the same encrypted connection. Received files are kept in the app's own cache folder and removed when the next ones arrive.
- **Data stored on your Mac**: the device name, display arrangement, paired Macs' public keys and this Mac's identity key stay in the app's container on this Mac and are deleted with the app.

Questions: yoqulin@gmail.com
