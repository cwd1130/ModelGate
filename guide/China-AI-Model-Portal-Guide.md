# 🪴 China AI Model Portal Guide

> Compiled from official platform documentation · May 2026
> Covers: Chat / API / Agent / Multimodal / Coding / Account requirements

---

## 🟦 Alibaba · Qwen (Tongyi Qianwen)

**Models**: Qwen3-Max / Qwen3.5 (397B MoE) / Qwen3.6-Plus / Qwen3-Coder-Next / Qwen3.5-Omni

| Feature | URL |
|---------|-----|
| 💬 Chat | https://tongyi.aliyun.com/qianwen |
| 🔧 API Key | https://bailian.console.aliyun.com |
| 📦 API Docs | https://help.aliyun.com/zh/model-studio |
| 🤖 Agent | https://bailian.console.aliyun.com |
| 🖼 Image Generation | https://tongyi.aliyun.com/wanxiang |
| 💻 Coding (Qwen3-Coder-Next) | https://bailian.console.aliyun.com |

**⚠️ Account Notes**

Three domains, one ecosystem — easy to confuse:
- `qianwen.com` = `tongyi.aliyun.com/qianwen` (chat alias)
- `qwen.com` (model showcase page, not a service entry point)
- `bailian.console.aliyun.com` (API / Agent console — the real developer entry)

→ Requires an **Alibaba Cloud account** with real-name verification. API Keys are created inside the Bailian console.

---

## 🟧 Baidu · ERNIE (Wenxin Yiyan) / Qianfan

**Models**: ERNIE 5.0 (2.4T unified multimodal) / ERNIE 4.5 Turbo / ERNIE X1 / ERNIE-Image (8B open-source)

| Feature | URL |
|---------|-----|
| 💬 Chat | https://yiyan.baidu.com |
| 🔧 API Key | https://console.bce.baidu.com/qianfan |
| 📦 API Docs | https://cloud.baidu.com/doc/WENXINWORKSHOP |
| 🤖 Agent | https://console.bce.baidu.com/qianfan |
| 🖼 Image Generation (ERNIE-Image) | https://aistudio.baidu.com/ernieimage |
| 🆓 Free API Alternative | https://aistudio.baidu.com |

**⚠️ Account Notes (Three separate account systems)**

- **Chat**: Standard Baidu account
- **API**: Requires a separate **Baidu Intelligent Cloud account** with real-name verification. You must create a Qianfan application to obtain an API Key + Secret Key. Authentication requires an extra step: exchange Key + Secret Key for an `access_token` (valid 30 days) before each session — one more step than other platforms
- **AI Studio**: A third independent account system aimed at researchers, with free access to some models

→ Three account systems with no cross-login — a long-standing legacy issue.

---

## 🟩 Tencent · Hunyuan / Yuanbao

**Models**: Hunyuan Hy3 preview (295B MoE) / Hunyuan T1 / HY-World 2.0 (3D world model) / CodeBuddy

| Feature | URL |
|---------|-----|
| 💬 Chat | https://yuanbao.tencent.com |
| 🔧 API Key | https://console.cloud.tencent.com/hunyuan |
| 📦 API Docs | https://cloud.tencent.com/document/product/1729 |
| 🤖 Agent | https://yuanqi.tencent.com (Tencent Yuanqi) |
| 🖼 Image Generation | https://console.cloud.tencent.com/hunyuan |
| 💻 Coding | https://copilot.tencent.com (Codebuddy) |

**⚠️ Account Notes (Two separate systems)**

- **Chat (Yuanbao)**: WeChat or QQ account
- **API**: Requires a separate **Tencent Cloud account** with real-name verification and post-pay billing enabled

→ Chat and developer accounts are completely separate with no link between them.

---

## 🟥 ByteDance · Doubao / Jimeng / Volcano Engine

**Models**: Doubao-pro / Doubao-Seedance-2.0 (video) / Seed 2.0 Pro / Coze Agent

| Feature | URL |
|---------|-----|
| 💬 Chat | https://www.doubao.com |
| 🔧 API Key | https://console.volcengine.com/ark |
| 📦 API Docs | https://www.volcengine.com/docs/82379 |
| 🤖 Agent | https://www.coze.cn (Coze) |
| 🖼 Image / Video Generation | https://jimeng.jianying.com (Jimeng AI — Seedance 2.0) |
| 💻 Coding | https://www.trae.ai (Trae AI IDE) |

**⚠️ Account Notes — Jimeng (most confusing)**

- **Doubao chat**: Douyin (TikTok CN) account or phone number
- **Jimeng web**: Douyin account scan-to-login or phone number
- **Jimeng App**: CapCut account / Douyin authorization / Apple ID (Apple ID purchases are not cross-platform — must bind a Douyin account to sync across devices)
- **Volcano Engine API**: Requires a separate **Volcano Engine account** (ByteDance enterprise cloud), real-name verification + service activation

→ Jimeng's mobile and web versions are now synced — logging in with the same CapCut / Douyin account works across both platforms.

---

## 🟪 DeepSeek

**Models**: DeepSeek-V4-Pro (1.6T MoE) / V4-Flash (284B) / V3.2 / R1-0528 / Coder V2 (fully open-source, MIT license)

| Feature | URL |
|---------|-----|
| 💬 Chat | https://chat.deepseek.com |
| 🔧 API Key | https://platform.deepseek.com/api_keys |
| 📦 API Docs | https://api-docs.deepseek.com |
| 🤖 Agent | No official platform — build via Coze / n8n using the API |
| 🖼 Image Generation | Not officially supported |
| 🌐 Stable Alternatives | https://bailian.console.aliyun.com (Alibaba Bailian) / https://console.volcengine.com/ark (Volcano Engine) |

**⚠️ Account Notes (Simplest among the eight)**

- Chat + API: **Same account** — register with a phone number
- `chat.deepseek.com` and `platform.deepseek.com` share the same login
- New users receive ¥10 in free API credits

→ From sign-up to first successful API call: approximately 5 minutes.

---

## ⬜ Moonshot AI · Kimi

**Models**: Kimi K2.6 (1T MoE) / K2.5 / k1.5 / moonshot-v1

| Feature | URL |
|---------|-----|
| 💬 Chat | https://kimi.moonshot.cn |
| 🔧 API Key | https://platform.moonshot.cn/console/api-keys |
| 📦 API Docs | https://platform.moonshot.cn/docs |
| 🤖 Agent | https://kimi.moonshot.cn (built-in Agent mode) |
| 💻 Coding | https://kimi.moonshot.cn (Kimi Code, in-page) |
| 🖼 Image Generation | Not supported |

**⚠️ Account Notes**

- Chat + API: **Same account** — register with a phone number
- `kimi.moonshot.cn` and `platform.moonshot.cn` share the same login

→ Clean account structure — tied with DeepSeek as the simplest setup.

---

## 🌊 MiniMax / Hailuo AI

**Models**: M2.7 (230B MoE) / M2.5 / Speech 2.8 / Music 2.6 / Hailuo 2.3 (video) / Hailuo 02

| Feature | URL |
|---------|-----|
| 💬 Chat (China) | https://hailuoai.com |
| 🌍 Chat (International) | https://hailuoai.video |
| 🔧 API Key | https://platform.minimaxi.com |
| 📦 API Docs | https://platform.minimaxi.com/document |
| 💳 Token Plan | https://platform.minimaxi.com/plan |
| 🤖 Agent | https://www.minimaxi.com/agent |
| 🎬 Video Generation | https://hailuoai.video (Hailuo 2.3 / Hailuo 02) |
| 🌟 Character / Companion | https://www.xingyewl.com (Xingyewl / Talkie) |

**⚠️ Account Notes (Four separate systems)**

- **Hailuo AI chat** (hailuoai.com): Phone number, standalone account
- **API platform** (platform.minimaxi.com): Separate registration, not linked to chat account
- **International API** (intl.minimaxi.com): Another separate system for overseas developers
- **Xingyewl** (xingyewl.com): Character roleplay app, fully independent account

→ For developers: focus only on `platform.minimaxi.com`.

---

## 📱 Xiaomi · MiMo

**Models**: MiMo-V2.5-Pro (1T MoE) / V2.5-Omni (multimodal) / V2.5-TTS / V2-Flash

| Feature | URL |
|---------|-----|
| 💬 Chat | https://aistudio.xiaomimimo.com |
| 🔧 API Key | https://platform.xiaomimimo.com |
| 📦 API Docs | https://platform.xiaomimimo.com/document |
| 💳 Token Plan | https://platform.xiaomimimo.com/plan (from ¥39/mo) |
| 🌐 Third-party (OpenRouter) | https://openrouter.ai/xiaomi/mimo-v2-pro |
| 🤖 Agent | MiMo Claw (integrates with OpenClaw / Cline / KiloCode) |
| 🔊 Voice Synthesis | V2.5-TTS via API (emotional TTS, dialects, singing) |
| 💻 Coding | V2.5-Pro (compatible with Claude Code / Cursor / Cline) |

**⚠️ Account Notes (Clean structure)**

- Chat + API: **Same account** — register with a phone number
- `aistudio.xiaomimimo.com` and `platform.xiaomimimo.com` share the same login
- Token Plan API Key and pay-as-you-go API Key are **independent** — create separately
- Supports both OpenAI-compatible and Anthropic-compatible API protocols

→ API pricing is approximately 1/5 of Claude at the same tier — strong value for coding use cases.

---

## 📊 Account Complexity Comparison

| Platform | Chat Account | API Account | Same Login? | Complexity |
|----------|-------------|-------------|-------------|------------|
| DeepSeek | Phone number | Phone number | ✅ Yes | ⭐ Simplest |
| Kimi | Phone number | Phone number | ✅ Yes | ⭐ Simplest |
| Xiaomi MiMo | Phone number | Phone number | ✅ Yes | ⭐⭐ Clean |
| MiniMax | Phone number | Separate signup | ❌ No | ⭐⭐⭐ Medium |
| Tencent Hunyuan | WeChat / QQ | Tencent Cloud | ❌ No | ⭐⭐⭐ Medium |
| ByteDance Doubao | Douyin / Phone | Volcano Engine | ❌ No | ⭐⭐⭐⭐ Complex |
| Alibaba Qwen | Alibaba Cloud | Alibaba Cloud | ⚠️ Same but multi-step | ⭐⭐⭐⭐ Complex |
| Baidu ERNIE | Baidu account | Baidu Cloud account | ❌ Completely separate | ⭐⭐⭐⭐⭐ Most complex |

---

*Maintained by: Wendy Chen · https://github.com/cwd1130/ModelGate*
*Data as of May 2026 — please check each platform's official site for the latest updates*
