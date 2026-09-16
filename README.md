---
---

# Giles 客户端 · Giles VPN GUI

> 一款基于 **Flutter** 跨端开发、底层集成 **sing-box** 内核的现代化 VPN 客户端，  
> 原生支持 **Android / iOS / macOS / Windows** 四大平台，**支持 sing-box 全部协议**。

---

## 🪔 项目简介

**Giles 客户端**（英文品牌：**Giles VPN GUI**）是一款为追求极致体验、安全与可定制性的客户打造的下一代网络代理客户端。

- **跨端框架**：使用 Flutter 一套代码同时编译到 Android、iOS、macOS、Windows，未来可平滑扩展至 Linux 与 Web。
- **代理内核**：内置 [sing-box](https://sing-box.sagernet.org/) 通用代理平台，支持其全部入站 / 出站 / 协议。
- **协议覆盖**：Shadowsocks、VMess / VLESS、Trojan、Hysteria / Hysteria2、TUIC、WireGuard、NaïveProxy、Brook、ShadowTLS、SSH 等 sing-box 已支持的协议均可开箱即用。

> 💡 本仓库为**客户定制版本 / 商务演示**使用，作者可承接**全套定制开发**——品牌、UI、协议、订阅、路由规则、内置节点、客户端打包与上架全流程。

---

## ✨ 核心特性

| 分类 | 能力 |
| --- | --- |
| **全平台** | Android、iOS、macOS、Windows 一套代码，原生体验 |
| **Flutter** | Dart + Flutter 高性能渲染，原生 FFI 桥接 sing-box C 核 |
| **sing-box 全协议** | 支持 sing-box 当前已发布的所有协议与传输方式 |
| **订阅 / 导入** | 支持订阅链接、二维码、扫码、文件导入、剪贴板一键导入 |
| **路由规则** | 内置国内外分流、广告拦截、绕过局域网 / 中国大陆 IP 段等规则集 |
| **可视化拓扑** | 图形化服务器拓扑、延迟测试、流量统计 |
| **多语言** | 简体中文、繁體中文、English、العربية 等 |
| **可深度定制** | 主题色、Logo、启动屏、应用名、签名 / 证书、商店元数据等均可按需定制 |

---

## 📸 界面预览

截图位于各平台目录下：

| 平台 | 目录 |
| --- | --- |
| Android | [`android/`](./android/) |
| iOS | [`ios/`](./ios/) |
| macOS | [`mac/`](./mac/) |
| Windows | [`win/`](./win/) |

> 宣传图片中包含的部分演示数据（节点名、流量数值等）仅用于 UI 展示，非真实生产节点。

---

## 🛠 技术栈

- **客户端**：Flutter 3.x / Dart 3.x
- **代理内核**：[sing-box](https://sing-box.sagernet.org/)（C / Go 实现，作为动态库 / 子进程集成）
- **状态管理**：Provider / Riverpod
- **本地存储**：Hive / SQLite（订阅、流量、设置）
- **国际化**：Flutter 内置 i18n
- **构建**：Flutter Build / Fastlane（移动端）/ electron-builder（桌面端打包脚本）

---

## 🧩 支持的协议（sing-box 全覆盖）

> 以下协议均已通过 sing-box 内核验证可用，具体可用性以你使用的 sing-box 版本为准。

- **VMess**
- **VLESS**（含 Reality、XTLS Vision 等）
- **Trojan**
- **Shadowsocks**（含 SIP002 / 2022）
- **Hysteria / Hysteria2**
- **TUIC**
- **WireGuard**
- **NaïveProxy**
- **Brook**
- **ShadowTLS**
- **SSH**

---

## 🚀 快速体验

> ⚠️ 本仓库当前为**商务演示与定制洽谈**用途，未包含可直接编译运行的完整源码；  
> 客户版本交付时附带完整 `flutter pub get` / 编译 / 打包脚本与 CI 配置。

### 客户版交付内容

- ✅ 完整 Flutter 源码（含 Android、iOS、macOS、Windows 四端）
- ✅ sing-box 内核集成模块与构建脚本
- ✅ 品牌定制（Logo / 启动屏 / 主题 / 应用名 / 包名 / 签名）
- ✅ 私有订阅服务对接（如需）
- ✅ 上架与打包指南（App Store / Google Play / 各自官网分发）
- ✅ 30 / 180 / 365 天不同等级的售后支持

---

## 💼 商务合作 · 定制开发

提供 **Giles VPN 客户端**的**全栈定制开发**服务，覆盖从原型设计到上架分发的全流程。

### 我能为你做什么

1. **品牌定制**：Logo、启动屏、主题色、应用名、包名、签名证书、商店素材
2. **UI / UX 定制**：界面风格、动效、交互流程、多语言
3. **功能定制**：新增自定义协议包装、私有订阅协议、专属路由规则、内置 DNS、广告过滤策略
4. **服务端对接**：自建订阅服务、支付、激活码、设备授权、用户中心
5. **上架分发**：App Store / Google Play / Mac App Store / Microsoft Store / 官网分发
6. **运维支持**：内核版本升级、协议适配、安全审计

### 适合谁

- 拥有自有节点资源、需要独立品牌的机场 / VPN 服务商
- 想做内网代理 / 跨境办公工具的企业
- 需要为现有产品嵌入代理能力的开发者
- 想定制一款专属 VPN 客户端的个人 / 团队

### 联系方式

- 💬 Telegram：**[@tallotang](https://t.me/tallotang)** （点击直达）
- 🤝 商务洽谈 / 报价：Telegram 上线更快回复

---

## 📜 许可证

- 本仓库宣传页 / 文档 / 截图：**仅供商务洽谈演示使用，未经作者书面授权不得用于其他用途**。
- 客户定制版本的源码许可以双方签署的合作协议为准。

---

## 🪔 关于 Giles

"Giles" 寓意轻轻一擦、灯灵即现——象征**一点即通的连接体验**。  
希望这款产品能像 Giles 一样，**一点即开、即开即用、即用即稳**。

---

© Giles VPN GUI. All rights reserved.