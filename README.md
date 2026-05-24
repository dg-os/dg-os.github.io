# 🖥️ DG_OS (Decentralized Gateway Operating System)

> **欢迎来到母体。一个纯前端、零信任、基于 Nostr 协议的密码学极客终端。**

[![Protocol](https://img.shields.io/badge/Protocol-Nostr-purple.svg)](https://nostr.com/)
[![Encryption](https://img.shields.io/badge/Encryption-AES--GCM--256-blue.svg)]()
[![Architecture](https://img.shields.io/badge/Architecture-Zero--Backend-success.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

🌐 **Live Terminal (在线体验入口):** [https://dgos.github.io](https://dgos.github.io)

---

## 💡 什么是 DG_OS？

**DG_OS** 并不是一个传统的操作系统，而是一个为**“绝对隐私捍卫者”**打造的去中心化应用 (DApp) 网关枢纽。

在这个“系统”中，没有中心化服务器来窥探你的数据，没有需要手机号注册的账号，也没有会被审查的明文日志。你的身份就是你的**密钥**（Nostr Private Key）。所有的加解密、文件粉碎、打包操作，均100%在你的浏览器本地内存中完成。

服务器在这里被“物理致盲”，它只能看到毫无意义的二进制密文碎片。**你，且只有你，掌握着解开一切的钥匙。**

---

## 🧩 核心模块 (System Modules)

DG_OS 搭载了三个由原生 HTML/JS 编写的硬核密码学单页面应用（SPA），它们部署在相同的路径下，彼此独立且功能互补：

### 🔐 [MODULE 01] DGCHAT :: 极客加密通讯端
一款基于 Nostr 协议构建的全场景加密通讯工具。
* **无后端架构**：无注册、无服务器、身份完全匿名。
* **军事级加密**：支持标准的 NIP-04 和高级的 NIP-59 (Gift Wrap) 协议，本地数据二次 AES-GCM 加密。
* **幽灵群组**：独创共享密钥的匿名群组，实现物理层面的身份混淆。

### 📸 [MODULE 02] DAGE_ALBUM :: 零信任金库相册
抛弃传统的“中心化信任”模型，防封禁、抗审查的云相册。
* **AES-GCM 碎流加密**：原图与缩略图在本地被粉碎为密文，服务器对用户数据“零认知”。
* **非对称分享**：通过 Diffie-Hellman 密钥交换将照片安全送达好友，无中心机构介入。
* **NIP-98 防重放鉴权**：免疫跨域拦截与中间人攻击。

### 📦 [MODULE 03] DGDROP :: 阅后即焚投递箱
带“自毁装置”的数字运钞箱，专门用于发送绝密文件的物理粉碎网盘。
* **拒绝分享链接**：无提取码，直接基于 Nostr 公钥单点建立绝密投递通道。
* **原子级实体抹除**：一旦文件到期或被撤回，不仅销毁授权，更在底层硬盘执行实体抹除，无法恢复。
* **锯齿状内存调度**：纯前端实现数百兆加密碎片的流水线解密与打包，防 OOM 崩溃。

---

## 👨‍💻 系统管理员 (SYS_ADMIN)

* **Creator:** **BTCDAGE**
* **Nostr PubKey:** `npub17ahz4xa3hvkvvhh4wguzzqknp8p7l5nyzzqc3z53uq538r5qgn0q40z7pw`
* **Donate BTC:** `bc1qzemaa3lc92f2x0q72e5jdx045ss6rm4hzazgde`

*(If these tools helped you reclaim your digital sovereignty, consider buying the dev a coffee via BTC or Lightning Network.)*

---

## ⚠️ 免责声明 (Cypherpunk Manifesto)

1. **无担保声明 (As-Is)**: 本程序按“原样”提供，不附带任何形式的保证。开发者不对数据丢失、系统崩溃或第三方节点引发的通讯中断承担责任。
2. **私钥即一切 (Not your keys, not your data)**: DG_OS 是纯客户端架构，我们无法访问或恢复你的私钥。**私钥一旦丢失，数据将化为永久无法解开的宇宙噪音。**
3. **物理致盲机制**: 虽然内容被端到端加密且服务器不可见，但在计算机领域没有绝对的安全性。建议在高敏感场景下配合 VPN 或使用完全私有的自建中继器 (Relays)。
4. **合规使用**: 开发者不监控、不干涉用户数据，也不对用户传播的内容负责。请遵循所在地法律法规。

> *"隐私是基本人权，通讯自由属于每一个人。" — Cypherpunk*
