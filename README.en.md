---
---

# Giles Client · Giles VPN GUI

> A modern VPN client built with **Flutter**, powered by the **sing-box** universal proxy platform,  
> natively available on **Android / iOS / macOS / Windows** — with **full support for all sing-box protocols**.

---

## 🪔 Overview

**Giles Client** (brand: **Giles VPN GUI**) is a next-generation proxy client crafted for users and businesses who demand performance, security, and deep customization.

- **Cross-platform**: A single Flutter codebase compiles natively to Android, iOS, macOS, and Windows — with Linux & Web on the roadmap.
- **Battle-tested core**: Integrates [sing-box](https://sing-box.sagernet.org/), supporting **all** of its inbounds, outbounds and protocols out of the box.
- **Protocol coverage**: Shadowsocks, VMess / VLESS, Trojan, Hysteria / Hysteria2, TUIC, WireGuard, NaïveProxy, Brook, ShadowTLS, SSH — everything sing-box supports.

> 💡 This repository is intended for **business demos & custom-development inquiries**.  
> The author accepts **full-stack custom development** engagements — branding, UI, protocols, subscription flow, routing rules, bundled nodes, store packaging and submission.

---

## ✨ Key Features

| Category | Capability |
| --- | --- |
| **All platforms** | Android, iOS, macOS, Windows — one codebase, native UX |
| **Flutter** | Dart + Flutter rendering, native FFI bridge to the sing-box C core |
| **Full sing-box protocol set** | Every protocol & transport that sing-box ships |
| **Subscription / Import** | Subscription URLs, QR codes, file import, one-tap clipboard import |
| **Routing rules** | Built-in geo-split, ad-blocking, bypass LAN / China mainland presets |
| **Visual topology** | Graphical server topology, latency testing, traffic statistics |
| **i18n** | Simplified Chinese, Traditional Chinese, English, العربية, more on request |
| **Deeply customizable** | Theme colors, logo, splash screen, app name, signing / certificates, store metadata — anything you need |

---

## 📸 Screenshots

Screenshots are organized by platform:

| Platform | Directory |
| --- | --- |
| Android | [`android/`](./android/) |
| iOS | [`ios/`](./ios/) |
| macOS | [`mac/`](./mac/) |
| Windows | [`win/`](./win/) |

> Sample data shown in screenshots (server names, traffic values, etc.) is **for UI demonstration only** and does not represent real production nodes.

---

## 🛠 Tech Stack

- **Client**: Flutter 3.x / Dart 3.x
- **Proxy core**: [sing-box](https://sing-box.sagernet.org/) (C / Go) — integrated as a dynamic library / sidecar
- **State management**: Provider / Riverpod
- **Local storage**: Hive / SQLite (subscriptions, traffic, settings)
- **i18n**: Flutter's built-in localization
- **Build**: Flutter Build / Fastlane (mobile) / electron-builder-style scripts (desktop)

---

## 🧩 Supported Protocols (full sing-box coverage)

> All listed protocols are validated against the bundled sing-box core. Availability depends on the sing-box version you ship.

- **VMess**
- **VLESS** (incl. Reality, XTLS Vision)
- **Trojan**
- **Shadowsocks** (incl. SIP002 / 2022)
- **Hysteria / Hysteria2**
- **TUIC**
- **WireGuard**
- **NaïveProxy**
- **Brook**
- **ShadowTLS**
- **SSH**

---

## 🚀 Quick Start

> ⚠️ This repository is currently a **business demo / inquiry** package — it does not include a directly buildable full source tree.  
> Client deliverables ship with complete `flutter pub get` / build / packaging scripts and CI configuration.

### What a client deliverable includes

- ✅ Complete Flutter source for Android / iOS / macOS / Windows
- ✅ sing-box integration module & build scripts
- ✅ Branding customization (logo / splash / theme / app name / package id / signing)
- ✅ Private subscription service integration (if needed)
- ✅ Store submission & packaging guide (App Store / Google Play / Mac App Store / Microsoft Store / self-host)
- ✅ 30 / 180 / 365-day support tiers

---

## 💼 Commercial · Custom Development

I offer **full-stack custom development** for the Giles VPN client — from prototype to store submission.

### What I can do for you

1. **Branding**: Logo, splash, theme colors, app name, package id, signing certificates, store assets
2. **UI / UX**: Custom design language, motion, interaction flow, multi-language
3. **Features**: Custom protocol wrappers, private subscription schemes, exclusive routing rules, built-in DNS, ad filtering
4. **Server-side integration**: Subscription services, payments, license / activation, device authorization, user portal
5. **Distribution**: App Store, Google Play, Mac App Store, Microsoft Store, self-hosted web distribution
6. **Ops**: Kernel upgrades, protocol adaptation, security audits

### Ideal for

- VPN / proxy providers with their own node infrastructure who need an independent brand
- Enterprises needing internal cross-border / remote-access tooling
- Developers looking to embed proxy capability into an existing product
- Individuals / teams wanting a bespoke VPN client

### Contact

- 💬 Telegram: **[@tallotang](https://t.me/tallotang)** (fastest response)
- 🤝 Quotes & business: please reach out via Telegram

---

## 📜 License

- The promotional content, docs and screenshots in this repository are **for business-demo use only** and may not be reused without written permission.
- The license of any client-delivered source tree is governed by the agreement signed between both parties.

---

## 🪔 About the name

"Giles" comes from *One Thousand and One Nights* — rub the lamp, summon the genie, and your wish is granted.  
The product aims to deliver that same one-tap magic: **one tap to connect — instantly, reliably, anywhere**.

---

© Giles VPN GUI. All rights reserved.